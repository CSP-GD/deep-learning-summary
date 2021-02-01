---
tags: 深度學習綱要
---
# Transformer
## 目錄
* **[基礎 Transformer](#基礎\&nbsp;Transformer)**
* **[Universal Transformer](#Universal\&nbsp;Transformer)**
* **[Transformer XL](#Transformer\&nbsp;XL)**
* **[Reformer](#Reformer)**
* **[Performer](#Performer)**
* **[Linformer](#Linformer)**
* **[Lambda Network](#Lambda\&nbsp;Network)**
* **[Bert](#Bert)**
* **[GPT](#GPT)**
* **[XLNet](#XLNet)**

## 基礎&nbsp;Transformer
在 2017 年，由 self attention 構成的新模型 Transformer 被提出。
最初主要使用在 NLP 的領域，
但實際上，只要能將問題轉換成「N個一維張量」，就能使用 Transformer 處理。

**優點：**
* 快速：跟 RNN 類的模型相比，可將輸入序列做平行運算。
* 長距離關注：跟 CNN 類的模型相比，可依據輸入序列長度動態改變感受野。

**缺點：**
* 記憶體使用量過大，受硬體設備限制了其關注距離。

## Universal&nbsp;Transformer
使用 Adaptive Computation Time 取代原本的固定層數

## Transformer&nbsp;XL

## Reformer

## Performer

## Linformer

## Lambda&nbsp;Network

## Bert

## GPT

## XLNet