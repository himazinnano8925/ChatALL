<div align="center">
  <img src="src/assets/logo-cover.png" width=256></img>
  <p><strong>全てのAIと同時にチャットし、最適解を見つける</strong></p>

[Deutsch](README_DE-DE.md) | [English](README.md) | [Español](README_ES-ES.md) | [Français](README_FR-FR.md) | 日本語 | [한국어](README_KO-KR.md) | [Tiếng Việt](README_VI-VN.md) | [简体中文](README_ZH-CN.md)

</div>

## 画像

![Screenshot](screenshots/screenshot-1.png?raw=true)

## 特徴

大規模言語モデル（LLM）ベースの AIは素晴らしいです。しかし、その回答はAIによってバラバラで、AIによって得意とする処理が異なります。最高の体験をしたいのであれば、AIを別々に毎回試すのはやめましょう！ChatALLは、同時に複数のAIにメッセージを送信することができ、各AIの回答を見て比較するのに役立ちます。ChatALLを使うのに必要なのは[ダウンロード・インストール](https://github.com/sunner/ChatALL/releases)・質問それだけです。

### あなたですか？

ChatALLのだいたいのユーザーはこんな感じ：

- 🤠**LLMのスペシャリストたち**, LLMから最高の答えや創造物を見つけたい人たち。
- 🤓**LLMの研究者**, 様々な分野のLLMの長所と短所を直感的に比較したい人。
- 😎**LLMアプリケーションの開発者**, プロンプトを素早くデバッグし、最もパフォーマンスの高い基礎モデルを見つけたい人。
### 対応するAI

| 対応AI                                                       | webアクセス | API   | メモ                                |
| ------------------------------------------------------------ | -------- | -------- | ----------------------------------- |
| [ChatGPT](https://chat.openai.com)                           | はい　　　| あり　　　|  ブラウジングを含む                    |
| [Bing Chat](https://www.bing.com/new)                        | はい　　　| なし　　　| ログイン不要 [ログインするとターン数上昇]                 |
| [Baidu ERNIE](https://yiyan.baidu.com/)                      | いいえ　　| あり　　　|                                     |
| [Bard](https://bard.google.com/)                             | はい　　　| 近日登場　|                                     |
| [Poe](https://poe.com/)                                      | はい　　　| 近日登場　|                                     |
| [MOSS](https://moss.fastnlp.top/)                            | はい　　　| なし　　　|                                     |
| [Tongyi Qianwen](http://tongyi.aliyun.com/)                  | はい　　　| 近日登場　|                                     |
| [Dedao Learning Assistant](https://ai.dedao.cn/)             | 近日登場　| なし　　　|                                     |
| [iFLYTEK SPARK](http://xinghuo.xfyun.cn/)                    | はい　　　| 近日登場　|                                     |
| [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)   | はい　　　| なし　　　| ログイン不要                     |
| [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/)          | はい　　　| なし　　　| ログイン不要                    |
| [ChatGLM](https://chatglm.cn/blog)                           | はい　　　| なし　　　| ログイン不要                     |
| [Claude](https://www.anthropic.com/index/introducing-claude) | はい　　　| なし　　　| ログイン不要                   |
| [Gradio](https://gradio.app/)                                | はい　　　| なし　　　| Hugging Face space/自己配布モデル用 |
| [HuggingChat](https://huggingface.co/chat/)                  | はい　　　| なし　　　|                                     |
| [QianWen](https://qianwen.aliyun.com/)                       | はい　　　| 近日登場　|                                     |

まだまだ続きます。[Issuesタブ](https://github.com/sunner/ChatALL/labels/more%20LLMs)でお気に入りのAIを提案してください。

### その他特徴

- クイックプロンプトモード：前のリクエストの完了を待たずに次のプロンプトを送信する機能
- チャット履歴をローカルに保存し、プライバシーを保護
- 気に入ったメッセージをピン止めし、悪いメッセージを削除
- 使いたいAIをいつでも変更することができます。
- 1列～3列の3段階の表示切替
- 最新バージョンへの自動アップデート
- ダークモード対応（@tanchekwei氏寄稿）
- `Ctrl + /` を押すと全てのショートカットキーが表示 (貢献者 @tanchekwei)
- マルチチャット対応
- 多言語対応(英語、中国語、ドイツ語、フランス語、ロシア語、ベトナム語、韓国語、日本語など...今後も言語を追加)
- Windows、macOS、Linux対応 

今後リリース予定の機能:

これらの機能への貢献は大歓迎です。

- [ ] フロントエンドをGitHub Pagesにデプロイする。

## プライバシー

すべてのチャット履歴、設定、ログインデータはコンピューターにローカルに保存されます。

ChatALLは、製品の改善に役立てるために以下の匿名の使用データを収集します。:

- どの AI ボットにプロンプ​​トが表示されるか、またプロンプトの長さ。プロンプトの内容は含まれません。

- 回答の長さ、および削除/強調表示された回答。例外として回答の内容は含まれません。

## 前提条件

ChatALL はプロキシではなく、クライアントです。そのため、以下のことが必要です:

1. ボット用のアカウントや API トークンを持っていること。
2. ボットへの信頼性の高いネットワーク接続があること。
3. VPN を使用する場合は、システム/グローバルプロキシとして設定されている必要があります。

## ダウンロード / インストール

https://github.com/sunner/ChatALL/releases から最新版をダウンロードしてください！

### Windows の場合

\*-win-x64.exe ファイルをダウンロードし、セットアップを進めてください。(x86 CPUは \*-win.exe をダウどの AI ボットにプロンプ​​トが表示されるか、またプロンプトの長さ。プロンプトの内容は含まれません。どの AI ボットにプロンプ​​トが表示されるか、またプロンプトの長さ。プロンプトの内容は含まれません。ンロードしてください)

### macOS の場合

AppleシリコンMac (頭文字にMがあるCPU)は、\*-mac-arm64.dmg ファイルをダウンロードしてください。

Intel Macは、\*-mac-x64.dmg ファイルをダウンロードしてください。

システムが悪意のあるソフトウェアかどうかを確認できないと表示した場合は、[アップルの公式ガイド](https://support.apple.com/ja-jp/guide/mac-help/mchleab3a043/mac)に従ってください。

### Linux の場合

debian ベースのディストリビューション: .deb ファイルをダウンロードし、ダブルクリックしてソフトウェアをインストールします。Arch ベースのディストリビューション: [ここで](https://aur.archlinux.org/packages/chatall-bin) AUR から ChatALL をクローンできます。手動でインストールすることも、yay や paru などの AUR ヘルパーを使用してインストールすることもできます。その他のディストリビューション: .AppImage ファイルをダウンロードして実行可能にし、クリックして実行します。[AppimageLauncher](https://github.com/TheAssassin/AppImageLauncher) を使用することもできます。

## トラブルシューティング

ChatALLをご利用中に問題が発生した場合は、以下の解決策をお試しください。：

1. **再読み込み** - "Ctrl + R" または "Cmd + R" を押す。
2. **アプリを再起動** - ChatALLを終了し、再度実行する。
3. **再ログイン** - 右上の設定ボタンをクリックし、ログイン/ログアウトリンクをクリックして、ウェブサイトに再ログインします。
4. **すべてのメッセージを削除する** - 右上のほうきボタンをクリックし"はい"をクリックする。

上記の方法でもうまくいかない場合は、**ChatALLを初期化**してみてください。この場合、すべての設定とメッセージ履歴が削除されますのでご注意ください。

ChatALLをリセットするには、以下のディレクトリを削除します：

- Windows: `C:\Users\<user>\AppData\Roaming\ChatALL\`
- Linux: `/home/<user>/.config/ChatALL/`
- macOS: `/Users/<user>/Library/Application Support/ChatALL/`

問題が解決しない場合は、[こちらに報告してください](https://github.com/sunner/ChatALL/issues).

## 開発者向け

### ボットの提供

[ガイド](https://github.com/sunner/ChatALL/wiki/%E5%A6%82%E4%BD%95%E6%B7%BB%E5%8A%A0%E4%B8%80%E4%B8%AA%E6%96%B0%E7%9A%84-AI-%E5%AF%B9%E8%AF%9D%E6%9C%BA%E5%99%A8%E4%BA%BA) があなたのお役に立つかもしれません。

### 実行

```bash
npm install
npm run electron:serve
```

### ビルド

Node.js は v16.x であること

現在のプラットフォームに合わせてビルド:

```bash
npm run electron:build
```

あらゆるプラットフォームに対応したビルド:

```bash
npm run electron:build -- -wml --x64 --arm64
```

## クレジット

### 貢献者

<a href="https://github.com/sunner/ChatALL/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=sunner/ChatALL" />
</a>

### その他

- GPT-4はコードを提供した
- ChatGPT、Bing Chat、Googleは多くの解決策を提供しています（ランキング順）
- [ChatHub](https://github.com/chathub-dev/chathub)のリスペクトです！

## 支援者

このプロジェクトが気に入った場合は、ぜひ支援にご検討ください：

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/F1F8KZJGJ)
