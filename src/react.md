# React.js, Next.js

React.jsとNext.jsについてのナレッジを記載する。

## 環境構築

1. WSLのインストール 
    ```
    sudo apt update && sudo apt upgrade
    wsl --install
    ```
1. curlのインストール  [link](https://learn.microsoft.com/ja-jp/windows/dev-environment/javascript/nodejs-on-wsl)
    ```
    sudo apt-get install curl
    ```
1. node.jsのインストール  [link](https://learn.microsoft.com/ja-jp/windows/dev-environment/javascript/nodejs-on-wsl)
    ```
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
    nvm install node
    ```
1. npmのインストール
    ```
    sudo npm install -g npm
    ```
1. npxのインストール
    ```
    npm install -g npx
    ```
1. ホームディレクトリに移動
    ```
    cd ~
    ```
1. reposフォルダを作成
    ```
    mkdir repos
    cd repos
    ```
1. next.jsプロジェクトの生成
    ```
    npx create-next-app@latest
    ```
1. デバッグ実行
    ```
    npm run dev
    ```
1. デプロイ [link](https://https://ja.next-community-docs.dev/docs/app-router/building-your-application/deploying/)

## 参考にしたWEBサイト
https://note.com/y_renren0115/n/n3ea0e3ef2d57
- [WSL を使用して Windows に Linux をインストールする方法](https://learn.microsoft.com/ja-jp/windows/wsl/install)
- [Node.js を Linux 用 Windows サブシステム (WSL2) にインストールする](https://learn.microsoft.com/ja-jp/windows/dev-environment/javascript/nodejs-on-wsl)
- [React/Next.jsアプリケーションを作成し、AWS EC2を使って本番環境にデプロイするまで](https://qiita.com/longtime1116/items/18553e43bfb44cbc9d81)