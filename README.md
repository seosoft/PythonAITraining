# Python + AI で最新プログラミング

人気のプログラミング言語のひとつであるPythonの基本を演習を通して学習します。  
Python は読みやすく拡張性が高いことから、機械学習から Web アプリケーションまで幅広く使用されています。

Python の利用例として AI プログラミングもあわせて体験します。 

この体験学習では次の内容を扱います。

- Pythonの基本文法と演習
- 事前構築済みの画像分析 (Computer Vision) の演習
- 事前構築済みの自然言語処理 (Text Analytics) の演習

---

この演習は以下の構成です。上から順番に進めてください。  
ただし演習の前にいくつか準備が必要です。準備についてはこの後のセクションで補足します。

0. [演習の環境構築](0_Setup.ipynb)
1. [Notebook の理解](1_AboutNotebook.ipynb)
2. [Python の基礎](2_PythonBasic.ipynb)
3. [Azure Cognitive Services で AI プログラミング](3_AIBasic.ipynb)

補足0. [JupyterLab Desktop App のインストール](a00_install_jupyter.md)  
補足1. [Cognitive Services リソースの作成方法](a01_createcog.ipynb)  
補足2. [Cognitive Services リソースの削除方法](a02_deletecog.ipynb)

この演習は [JupyterLab Desktop App](https://github.com/jupyterlab/jupyterlab-desktop) で実行することを前提としています。  
初心者、入門者などでも環境構築しやすいこと、および集合形式の演習時に事前の環境構築がしやすいことが理由です。  
その他の Python 開発環境でも特に問題なく実行できるはずですが、それらについてはここでは触れません。

---

演習の前にいくつか準備が必要です。  
集合形式の演習の場合には準備が完了していることがあります。その場合は講師やスタッフの指示に従ってください。

- Jupyter Notebook/Lab、JupyterLab Desktop App などがインストールされていない場合は [JupyterLab Desktop App のインストール](a00_install_jupyter.md) から始めてください。

- 演習3 "Azure Cognitive Services で AI プログラミング" の演習で利用する Cognitive Services のリソースがまだない場合は [Cognitive Services リソースの作成方法](a01_createcog.ipynb) でリソースを作成してください。  
演習3 を実施しない場合は、Azure サブスクリプションや Cognitive Services のリソース作成は不要です。

- Cognitive Services のリソースを作成するには、[**Azure サブスクリプション**](https://azure.microsoft.com/ja-jp/) が必要です。  
アカウントを持っていない場合は [無料の評価版アカウントを取得](https://azure.microsoft.com/ja-jp/free/) することができます。

これらが完了したら演習0 から始めてください。

---

この演習は [OCA 大阪デザイン＆ITテクノロジー専門学校](https://www.oca.ac.jp/) の [オープンキャンパスでの体験学習](https://www.oca.ac.jp/opencampus/24265/) 教材として開発したものです。  
同校の許可をいただき一般にも公開します。

プログラミング経験が少ない高校生を対象として想定してるため、スキルによっては非常に簡単な内容かもしれません。  
その点を理解した上でご利用ください。