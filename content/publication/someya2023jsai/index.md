---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "サッカーイベント予測における選手ベクトルの利用"
authors: ["染谷 大河", "石垣 達也", "大関 洋平", "永田 亮", "高村 大也"]
date: 2023-06-06T00:00:00+09:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-18T00:00:00+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2023年度人工知能学会全国大会（第37回）"

abstract: "サッカーは、制約が少なく複雑性が高いチームスポーツの一つであり、試合の成り行きを予測するのは非常に難しい。近年では、主に機械学習の手法を用いて、サッカーの試合においてどの選手がどこで何のアクションをしたかを示すイベントの系列の予測が試みられており、先行イベント系列を考慮したゴール期待値の計算や特定のアクションの有効性の評価への応用が見込まれている。一方で、次にどのようなイベントが発生するかは、単に先行するイベントの系列だけでなくどの選手がそのイベントを発生させるかに大きく依存すると考えられる。そこで、本研究では選手を分散表現すなわちベクトルで表現しニューラルイベント予測モデルの入力に加えることで、先行研究では考慮されていなかった選手の特性を考慮した予測を行うことを提案する。実験の結果、選手特性を考慮することでモデルの予測精度が向上することに加え、モデルを学習する過程で得られた「選手ベクトル」が選手のポジションに関する情報を含んでいることが示された。"

# Summary. An optional shortened abstract.
# summary:

tags: ["Domestic", "Refereed"]
categories: ["NLP", "Soccer"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_2M5GS1005/_pdf/-char/ja
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides:"example"`references`content/slides/example/index.md`.
#   Otherwise, set `slides:""`.
slides: ""
---
