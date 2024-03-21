---
title: DenoでBlog始めました
publish_date: 2024-03-22
tags: ["deno"]
---

deno_blogを使ってブログを始めました。

https://github.com/denoland/deno_blog

考えたことや、やったことのアウトプットする場がほしくて作りました。
開発関連のことばかりだとZennやQiitaでも良いかなと思っていましたが、本の感想とか考えたことなども気軽に書ける場がほしかったのです。

しずかなインターネットとかでも良かったかもしれません。
ただdeno_blogがMarkdownで書けて、サッと始めれそうだったのでやってみました。

気軽に更新していこうと思います。

## deno_blogについて

ブログを始めるにあたり、ホスティング含めてどうするかは迷いました。

以下を条件に検討しました。

- 自動デプロイでホスティング
- Git管理できる
- Markdownで書ける
- すぐ始めれる
- 無料

CloudFlare Pagesかdeno_blog(Deno Deploy)で迷いましたが、最終的にdeno_blogにしました。
Denoのアイコンかわいい。

CloudFlareは簡単そうで魅力的でしたが、自分でやっぱりデザインとかやるの面倒だなあと思ってしまいました。deno_blogはコマンド一発でテンプレート作成してくれてすぐに始めることができて良かったです。

CloudFlareはHonoを使ってみたいので、何か機会があれば使ってみようと思っています。

### deno blogの始め方

こちらと同じ方法でやりました。

https://zenn.dev/k41531/articles/9897a0f8fce1b3

denoコマンドが動けばこれだけでカレントディレクトリに配置できて、めちゃくちゃ簡単でした。

```sh
deno run -r --allow-read --allow-write https://deno.land/x/blog/init.ts ./

deno task dev
```

これからマイペースに更新していきたいと思います。
