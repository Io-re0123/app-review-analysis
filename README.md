# app-review-analysis
学習の成果物として、アプリケーションのレビュー分析を行いました。  
使用言語には生データをさまざまな観点で可視化・集計しながら探索できること、機械学習・自然言語処理などの高度な処理が可能であることからPythonを採用しました。  
環境はGoogle Colaboratory（GPU環境）を利用しました。
## 内容
GooglePlay上のInstagramのレビューをスクレイピングし、BERTによるネガポジ分類と共起ネットワーク等の可視化、ロジスティック回帰を用いたキーワードがネガポジへ及ぼす影響度の算出を行いました。  
GooglePlay上にあるアプリでレビューが一定数取得可能であれば、どのアプリでも機能させることができます。  
解説と考察はnlp-review-analysis.pdfに記述しているので、そちらをご覧ください。  
また、初学者ゆえ拙いコード等が多くありますが参考になれば幸いです。
## 主なライブラリ
__ML__  
・[scikit-learn](https://scikit-learn.org/ "scikit-learn")  
・[PyTorch](https://pytorch.org/ "PyTorch")  
・[Tansformers](https://huggingface.co/docs/transformers/index "Transfomers")  

__データ操作__  
・[NumPy](https://numpy.org/ja/ "NumPy")  
・[Pandas](https://pandas.pydata.org/ "Pandas")  

__可視化__  
・[nlplot](https://github.com/takapy0210/nlplot "nlplot")  
・[Matplotlib](https://matplotlib.org/ "Matplotlib")  

__スクレイピング__  
・[google-play-scraper](https://github.com/facundoolano/google-play-scraper "google-play-scraper")  
