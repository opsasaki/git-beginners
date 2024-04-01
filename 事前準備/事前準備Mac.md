# Macの場合

既に入っている場合は飛ばしてください。

## 1. brewのインストール

コマンドは、ターミナルアプリを使って実行してください。

[macOS（またはLinux）用パッケージマネージャー — Homebrew](https://brew.sh/ja/)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

echo 'eval $(/opt/homebrew/bin/brew shellenv)' >> ~/.zprofile
eval $(/opt/homebrew/bin/brew shellenv)
```

## 2. gitのインストール

```bash
brew install git
# 設定
git config --global init.defaultBranch main
```

## 3. VSCodeのインストール

```bash
brew install --cask visual-studio-code
```

## 4. VSCodeの拡張機能のインストール

VSCodeを開き、拡張機能のボタンを選択してください。


![VSCodeサイドメニュー拡張機能.png](../ScreenShots/VSCode/VSCodeサイドメニュー拡張機能.png)

![VSCode拡張機能.png](../ScreenShots/VSCode/VSCode拡張機能.png)

検索窓から次の拡張機能を検索してインストールしてください。

- [Japanese Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ja)
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
- [GIt History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

## 5. nanoのインストール(推奨)

Vimの操作が出来る方は不要です。

```bash
brew install nano
```

```bash
echo "EDITOR=/usr/bin/nano" >> ~/.zshrc
echo "export EDITOR" >> ~/.zshrc
source ~/.zshrc
```

## 6. 最後に

当日は、Visual Studio Codeを使って操作を行うため、
ファイルの開き方、作り方、編集の仕方を使って慣れておいてください。
