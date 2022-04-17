# NaturalLanguageProcessing Repository

## About
自然言語処理に関する実装をまとめたリポジトリです.

## 実装内容
テキストデータの前処理  
- HTMLの解析とクリーニング  
- Unicodeの正規化  
- スペル修正  
- システム固有の誤り訂正  
- 文, 単語の分割  
- ストップワードの処理  
- ステミング  
- 見出し語化  
- 日本語テキストの前処理  

テキスト表現
- One-hotエンコーディング  
- Bag of Words  
- Bag of N-grams  
- TF-IDF  
- Word2Vec  
- 単語埋め込み  

テキスト分類
- 英語テキストのPositive/Negative分類(ナイーブベイズ分類器, Logistic回帰を用いた分類器, SVM)  
- Word2Vecを用いたPositive/Negative分類  
- FastTextを用いたテキスト分類  
- Doc2Vecを用いたテキスト分類  
- BERTを用いた日本語テキスト分類  

テキスト抽出
- 条件付き確率場(CRF)を用いた固有表現認識  
- BERTを用いた固有表現認識  
- TextRankを用いたキーフレーズ抽出  
- Azure APIを用いたエンティティリンキング  

チャットボット
- CNN, RNNを用いた対話行為の分類  
- CRFを用いたスロットフィリング  

ディープラーニング
- Seq2Seqを用いた数字文字列の足し算  

## Reference
実践 自然言語処理, Sowmya Vajjala et al. 著 中山光樹 訳