# Japanese Text Similarity

This repository provides a Jupyter Notebook to calculate text similarity in Japanese using TF-IDF and cosine similarity. The notebook uses MeCab for tokenization and compares custom queries with reference texts.

## How to Use
- Edit the `reference_texts` and `query` variables in the notebook.
- Run the notebook to find the most similar reference text based on the query.

## Example Output
```
類似度スコア:
スコア: 0.5774 - テキスト: 商品の返品について説明します。返送料は当社負担です。
最も類似度の高いテキスト:
スコア: 0.5774
テキスト: 商品の返品について説明します。返送料は当社負担です。
```
