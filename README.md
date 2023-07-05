# Azure Open API Service GPT3 AI Bot 作成チュートリアル

## 概要

このチュートリアルは **Microsoft [Azure OpenAI Service](https://learn.microsoft.com/ja-jp/azure/cognitive-services/openai/overview)** に含まれるモデル GPT3.5 と **[Azure Bot Service](https://learn.microsoft.com/ja-jp/azure/bot-service/?view=azure-bot-service-4.0) ([Microsoft Bot Framework SDK](https://learn.microsoft.com/ja-jp/azure/bot-service/bot-service-overview?view=azure-bot-service-4.0))** を組み合わせて文章生成を行う Bot を作成する手順を説明するものです。

このチュートリアルでは、Azure での Open AI リソースの作成から Microsoft Bot Framework を使用したローカル環境でのチャットボットの作成、Azure Bot Service へのデプロイまでを行います。


## 要件

このチュートリアルを実施するには以下の環境が必要です。

- **[Microsoft Azure サブスクリプション](https://azure.microsoft.com/ja-jp/free/) と Azure Open AI サービスの[利用資格](https://aka.ms/oaiapply)**

    【重要】

    現在、Azure Open AI の利用は Microsoft と既存のパートナーシップ関係があるお客様、リスクの低いユース ケース、軽減策の取り入れに取り組んでいるお客様に制限されており、**利用には申請が必要**です。

    申請については、以下の申請フォームに記載されています。 利用を開始するにはこちらからお申し込みください。
    
    [Azure OpenAI Service へのアクセス申請](https://aka.ms/oaiapply)


- [**Visual Studio Code**](https://code.visualstudio.com/)

    Visual Studio Code から Azure のリソースを作成するための以下の拡張もインストールしてください。
    - [Azure Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack)


- [**Node.js**](https://nodejs.org/ja/)

    【重要】

    現状、Node.js のバージョンの 17 以降では、Bot Framework SDK が正常に動作しないため、[**Node.js のバージョンは 16 以前**](https://nodejs.org/download/release/v16.20.1/)を使用してください。

    ローカル環境で Node.js のバージョンを任意で切り替えるには Windows では [nvm-windows](https://github.com/coreybutler/nvm-windows) 、Mac では [nvm](https://github.com/nvm-sh/nvm) を使用すると便利です。

    詳しくは以下のドキュメントを参照してください。

    - [nvm-windows のインストール](https://learn.microsoft.com/ja-jp/windows/dev-environment/javascript/nodejs-on-windows#install-nvm-windows-nodejs-and-npm)
    - [nvm のインストール](https://learn.microsoft.com/ja-jp/windows/dev-environment/javascript/nodejs-on-wsl#install-nvm-nodejs-and-npm)

- [**Bot Framework Emulator**](https://github.com/microsoft/BotFramework-Emulator)

<br>

## 演習

1. [**Azure Open AI リソースの作成**](Ex01.md)
2. [**Microsoft Bot Framework と Azure OpenAI チャット ボットの統合**](Ex02.md)








