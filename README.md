# DALL-E-3 による画像生成アプリ

## 概要

[DALL-E-3](https://help.openai.com/en/articles/8555480-dall-e-3-api)の API を利用した画像生成 AI とお題の画像の類似度を比較して算出するアプリ

- 参考資料<br>
  [Open AI](https://platform.openai.com/docs/api-reference)

## インフラ構成図

<img src="streamlit-ai-app-aws.drawio-complete.png" width="450px">

## 環境構築

1. Open AI アカウント作成
2. [Open AI の API キーを発行する](https://nicecamera.kidsplates.jp/help/feature/ai-kata/openapi_apikey/)
3. git clone する
4. .env を作成し API キーの値を記述

```
OPENAI_API_KEY="your api key"
```

5. streamlit を起動

```
streamlit run main.py
```

## 技術スタック

<img src="https://img.shields.io/badge/-TypeScript-111111.svg?logo=typescript&style=#3178C6&logoColor=#3178C6" height="30px">

<img src="https://img.shields.io/badge/-Python-111111.svg?logo=python&style=#3178C6&logoColor=#3178C6" height="30px">

<img src="https://img.shields.io/badge/-Streamlit-111111.svg?logo=streamlit&style={バッチのスタイル}&logoColor=#FF4B4B" height="30px">

<img src="https://img.shields.io/badge/-Amazon AWS-111111.svg?logo=amazonaws&style=#412991&logoColor=#412991" height="30px">

<img src="https://img.shields.io/badge/-Docker-111111.svg?logo=docker&style={バッチのスタイル}&logoColor=#2496ED" height="30px">

<img src="https://img.shields.io/badge/-Github Actions-111111.svg?logo=githubactions&style=#3178C6&logoColor=#3178C6" height="30px">

<img src="https://img.shields.io/badge/-OpenAI-111111.svg?logo=OpenAI&style=#412991&logoColor=#412991" height="30px">
