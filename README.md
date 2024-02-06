# app-review-analysis
学習の成果物として、アプリケーションのレビュー分析を行いました。
## 内容
GooglePlay上のInstagramのレビューをスクレイピングし、BERTによるネガポジ分類と共起ネットワーク等の可視化、ロジスティック回帰を用いたキーワードがネガポジへ及ぼす影響度の算出を行いました。  
GooglePlay上にあるアプリで、レビューが一定数取得可能であればどのアプリでも機能させることができます。
## 主なライブラリ
_ML_  
・[scikit-learn](https://scikit-learn.org/ "scikit-learn")  
・[PyTorch](https://pytorch.org/ "PyTorch")  
・[Tansformers](https://huggingface.co/docs/transformers/index "Transfomers")  
_データ操作_  
・[NumPy](https://numpy.org/ja/ "NumPy")  
・[Pandas](https://pandas.pydata.org/ "Pandas")  
_可視化_  
・[nlplot](https://github.com/takapy0210/nlplot "nlplot")  
・[Matplotlib](https://matplotlib.org/ "Matplotlib")  
_スクレイピング_  
[google-play-scraper](https://github.com/facundoolano/google-play-scraper "google-play-scraper")  
