---
layout: post
title:  "データの可視化"
author: bouquet_diagram
categories: アンケート関係
image: assets/images/Hanataba_diagram.jpg
lang: 'ja'
---
収集したアンケート調査データを綺麗に可視化するサービスです。

提供いただいたデータから、「花束ダイアグラム」をはじめとして、様々な可視化を提供いたします。

## 花束ダイアグラム
### 簡単な説明
「30代の男性のうちで、クリスマスを祝う人の割合」や「クリスマスを祝わない40代の人のうちで、女性の割合」のように、属性で分岐させた先に円グラフ（pie chart）を表示する図です。いろんな条件のもとで、結果の特徴を見渡すことができます。

### 詳しい説明
多次元分割表を、デンドログラムと円グラフで表現した図です。通常のデンドログラムは元々階層構造がありますが、ここではそれぞれの属性自体には階層構造がないので、デフォルトではすべての分岐の組み合わせを描画します。
異なる枝たちはすべて独立ではなく、条件付けの組合せが同じものは同じ分布になります（超幾何分布の対称性）。裏ではp値を正確検定orカイ2乗検定で算出しているので、それで分岐の枝を“剪定“することもできます（多重検定の問題を孕んでいるので、統計的有意性の評価は注意が必要です）。具体的に注目したい絞り込み条件があれば、それに応じて“剪定“もできます。

## サンプル
インスタグラムにカタログを掲載しております。ぜひご参照ください。

[https://www.instagram.com/hanataba_diagram/](https://www.instagram.com/hanataba_diagram/)


## ご注文
企業の調査・卒業研究・修士論文で実施したアンケートの集計結果を綺麗に分かりやすくビジュアライズしたいという方は、ご注文ください。
ご指定の色・フィルタリング条件に応じて、SVGファイル（ベクトルデータ）とPNGファイル（画像データ）を各１点ずつ納品いたします。
（注：インスタグラムに掲載しているものは、背景等の装飾を施しておりますが、納品は花束ダイアグラム本体のみとなります）


<script async
  src="https://js.stripe.com/v3/buy-button.js">
</script>

<stripe-buy-button
  buy-button-id="buy_btn_1OS9uRDo8uVOKmA4E7dmgnim"
  publishable-key="pk_live_51NqUGqDo8uVOKmA4DtdZ9oO9YwBtkt1dZQ0Qc1DQtjypo6Z2wVXXU9ftcghkFhA7dccnyfIJZ7Jz91a1t0StNCsF00gm5qcv37"
>
</stripe-buy-button>

## お問合せ・ご相談
花束ダイアグラムに関するお問合せ・ご相談は、<a href="{{site.baseurl}}/contact">お問合せフォーム</a>より承っております。
