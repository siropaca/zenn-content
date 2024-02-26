---
title: "エンジニアとして知っておきたい2024年デスクトップブラウザまとめ"
emoji: "🌐"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["browser"]
published: true
---

Web 関連の技術革新が目覚ましい一方で、クライアント側であるブラウザの進化も目覚ましいものがあります。
この記事では、2024年にエンジニアとして知っておきたいデスクトップブラウザについてまとめて紹介します。

## 王道ブラウザ

### Google Chrome

![Google Chrome](/images/2024-browsers/google-chrome.jpg)

- 開発元
  - Google LLC (アメリカ)
- 初版
  - 2008年9月2日 (15年前)
- エンジン
  - `Chromium` (Blink / V8)
- 対応OS
  - `Windows`
  - `macOS`
  - `ChromeOS`
  - `Linux`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - Google Git: https://chromium.googlesource.com/chromium/src/+/refs/heads/main/chrome/
  - GitHub (mirror): https://github.com/chromium/chromium/tree/main/chrome

Google Chrome は、Google が開発した Chromium ベースのブラウザです。
ブラウザのシェア率としては断トツで、世界中で最も多くのユーザーに利用されています。
プライバシー保護の観点からは懸念がありますが、サードパーティクッキーの廃止などのプライバシー保護に関する取り組みも進んでいます。

https://www.google.com/intl/ja/chrome/

#### Chrome Beta

Chrome Beta は、おおよそ１つ先のバージョンが毎週リリースされる Google Chrome のベータ版です。

https://www.google.com/intl/ja/chrome/beta/

#### Chrome Dev

Chrome Dev は、おおよそ２つ先のバージョンが毎週リリースされる Google Chrome の開発版です。

https://www.google.com/intl/ja/chrome/dev/

#### Chrome Canary

Chrome Canary は、Google Chrome の最新のビルドが毎日リリースされる Google Chrome の開発最新版です。

https://www.google.com/intl/ja/chrome/canary/

### Mozilla Firefox

![Mozilla Firefox](/images/2024-browsers/mozilla-firefox.jpg)

- 開発元
  - Mozilla Foundation (アメリカ)
- 初版
  - 2002年9月23日 (21年前)
- エンジン
  - `Quantum` (Gecko / SpiderMonkey)
- 対応OS
  - `Windows`
  - `macOS`
  - `Linux`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - Mercurial: https://hg.mozilla.org/mozilla-central/
  - GitHub (mirror): https://github.com/mozilla/gecko-dev

Mozilla Firefox は、非営利組織である Mozilla Foundation によって開発されたオープンソースのウェブブラウザです。
プライバシー保護に配慮したブラウザとして知られており、プライベートブラウジング機能によりトラッキングを防止し、ユーザーのプライバシーを強力に保護することができます。

https://www.mozilla.org/ja/firefox/new/

#### Firefox Beta

プレビュー版の中で最も安定したプレリリースビルドで、近日リリース予定の機能を試すことができるバージョンです。

https://www.mozilla.org/ja/firefox/channel/desktop/#beta

#### Firefox Developer Edition

開発者用に構築されたブラウザーで、カスタマイズされた設定や開発者ツールが搭載されています。

https://www.mozilla.org/ja/firefox/developer/

#### Firefox Nightly

不安定な開発中の試験版で、最新の機能を試すことができるバージョンです。

https://www.mozilla.org/ja/firefox/channel/desktop/#nightly

### Microsoft Edge (Chromium)

![Microsoft Edge](/images/2024-browsers/microsoft-edge.jpg)

- 開発元
  - Microsoft (アメリカ)
- 初版
  - 2020年1月15日 (3年前)
- エンジン
  - `Chromium` (Blink / V8)
- 対応OS
  - `Windows`
  - `macOS`
  - `Linux`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - 非公開

Chromium 版の Microsoft Edge は、EdgeHTML ベースの Edge（Microsoft Edge Legacy）から再構築されたブラウザです。
再構築された Edge は、縦型のタブやコレクションなどの機能が搭載され、ユーザービリティも向上しています。

https://www.microsoft.com/ja-jp/edge

#### Edge Canary

プレビュー版の中で最も新しく、最新の機能が含まれていますが、安定性は低いバージョンです。

https://www.microsoft.com/ja-jp/edge/download/insider

#### Edge Dev

カナリア版よりも安定したバージョンです。カナリアビルドからの改善が含まれています。

https://www.microsoft.com/ja-jp/edge/download/insider

#### Edge Beta

プレビュー版の中で最も安定したバージョンで、開発ビルドとカナリアビルドからの改善が含まれています。

https://www.microsoft.com/ja-jp/edge/download/insider

### Safari

![Safari](/images/2024-browsers/safari.jpg)

- 開発元
  - Apple (アメリカ)
- 初版
  - 2003年1月7日 (21年前)
- エンジン
  - `WebKit` (WebKit / Nitro)
- 対応OS
  - `macOS`
  - `iOS`
  - `iPadOS`
- 料金
  - 無償
- ソースコード
  - WebKit: https://webkit.org/
  - GitHub : https://github.com/WebKit/webkit
  
Safari は、Apple が開発したウェブブラウザで、macOS や iOS に標準搭載されています。

https://www.apple.com/jp/safari/

### Opera (Chromium)

![Opera](/images/2024-browsers/opera.jpg)

- 開発元
  - Opera Software ASA (ノルウェー)
- 初版
  - 1996年12月9日 (28年前)
- エンジン
  - `Chromium` (Blink / V8)
- 対応OS
  - `Windows`
  - `macOS`
  - `Linux`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - 非公開

Opera は、中国の奇虎360傘下 の Opera Software ASA によって開発されているウェブブラウザです。
当初は独自エンジンを採用していましたが、バージョン13以降は Chromium ベースへと移行しました。
このブラウザは高速化とセキュリティ向上に焦点を当てており、広告ブロッカー、無料VPN、データ圧縮などの機能を備えています。

https://www.opera.com/ja

#### Opera GX

![Opera GX](/images/2024-browsers/opera-gx.jpg)

Opera GX はゲーマー向けに特化した Opera ブラウザの特別版で、ゲームとブラウジングの両方を快適に楽しむために設計されています。
CPU、RAM、ネットワークの使用量を制限するなど機能を搭載していたり、ユーザーのゲームセットアップに合わせて配色をカスタマイズできるほか、特別にデザインされたテーマを選択可能です。
また、2週間ブラウザを使用しなかったときに閲覧履歴を偽のものに置き換える Fake My History 機能や、F12 キーを押すだけで安全なコンテンツへ一時的に差し替えられる Panic Button 機能など、ユニークな機能も搭載されています。

https://www.opera.com/ja/gx

## その他ブラウザ

### Vivaldi

![Vivaldi](/images/2024-browsers/vivaldi.jpg)

- 開発元
  - Vivaldi Technologies (ノルウェー)
- 初版
  - 2016年4月6日 (7年前)
- エンジン
  - `Chromium` (Blink / V8)
- 対応OS
  - `Windows`
  - `macOS`
  - `Linux`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - 非公開

Opera Software の元 CEO によって設立された Vivaldi Technologies が開発したブラウザです。
ユーザーのプライバシーを重視し、DuckDuckGo、Startpage.com などがデフォルト検索エンジンに入っています。
Vivaldi は、Chromium をベースに、パワーユーザー向けの機能やカスタマイズ性を重視した機能が搭載されています。
サイトのテーマ色に合わせてウィンドウの色を変えるカメレオンカラー機能や、高度なアクセシビリティ機能など他のブラウザにはない機能を多く備えています。

https://vivaldi.com/ja/

### Brave

![Brave](/images/2024-browsers/brave.jpg)

- 開発元
  - Brave Software (アメリカ)
- 初版
  - 2019年11月13日 (4年前)
- エンジン
  - `Chromium` (Blink / V8)
- 対応OS
  - `Windows`
  - `macOS`
  - `Linux`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - GitHub: https://github.com/brave/brave-browser

Brave は、Chromium ベースでプライバシーとセキュリティに優れたオープンソースのウェブブラウザです。
Brave Software 社によって開発され、広告とトラッカーを標準でブロックし、高いパフォーマンスとユーザープライバシーの保護を提供します。
また、Brave Rewards 機能を通じて、ユーザーは広告閲覧により報酬を得ることが可能で、Brave 自身がプライベートな広告を配信し、表示された広告料の70%を仮想通貨 BAT としてユーザーに分配する新しいビジネスモデルを採用しています。

https://brave.com/ja/

### Arc

![Arc](/images/2024-browsers/arc.jpg)

- 開発元
  - The Browser Company (アメリカ)
- 初版
  - 2022年4月19日 (2年前)
- エンジン
  - `Chromium` (Blink / V8)
- 対応OS
  - `macOS`
  - `iOS`
- 料金
  - 無償
- ソースコード
  - 非公開

Arc はニューヨークに拠点を置く The Browser Company によって開発された、Chromium を基にした新しいブラウザです。
このブラウザは、メモリ使用量を抑えた軽快な動作と、高度にカスタマイズ可能なユーザーインターフェイスが特徴です。
タブバーは横に配置され、タブの管理を簡単にし、新規タブは Today とういう領域で開かれて自動的にアーカイブされるため、タブの蓄積を防ぐことができるのが特徴です。
スペース機能で特定のアカウントを割り当てたり、スプリットビューやミニウインドウでの表示、ページのカスタマイズ、ノートやイーゼル機能でのメモ取りや画像作成など、他のブラウザにはない多彩な機能を提供しています。

https://arc.net/

### Sidekick

![Sidekick](/images/2024-browsers/sidekick.jpg)

- 開発元
  - PushPlayLabs (アメリカ)
- 初版
  - 不明
- エンジン
  - `Chromium` (Blink / V8)
- 対応OS
  - `macOS`
- 料金
  - 一部機能が有料（[Sidekick Pro](https://www.meetsidekick.com/ja/sidekick-pro/)）
- ソースコード
  - 非公開

Sidekick は、アメリカの PushPlayLabs によって開発された Chromium ベースのウェブブラウザです。
お気に入りのサイトをサイドバーに追加し、それらをアプリ化して瞬時にアクセスできる点が特徴です。
セッション機能、スプリットビュー、アカウント切り替え、集中モードなどの豊富な機能を提供していますが、無料版ではサイドバーアプリやワークスペースの数に制限があります。

https://www.meetsidekick.com/ja/

### DuckDuckGo

![DuckDuckGo](/images/2024-browsers/duck-duck-go.jpg)

- 開発元
  - DuckDuckGo (アメリカ)
- 初版
  - 不明
- エンジン
  - `Chromium` (Windows) / `WebKit` (macOS)
- 対応OS
  - `Windows`
  - `macOS`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - 非公開

2008年に設立された DuckDuckGo によって開発されたプライバシー保護を重視するブラウザです。
このブラウザは、プライバシーを守るためにトラッキングをブロックしたり、ユーザーのブラウザデータの追跡や保存をせずにプライバシー保護を行います。
DuckDuckGo の検索エンジンは、大手検索エンジンと比較してインデックスが弱いですが、ユーザーデータを収集しないため、個人化されない公平な検索結果を提供します。
また、Fire Button をタップすることで簡単にすべてのタブと閲覧データを消去できる機能を備えているのが特徴です。

https://duckduckgo.com/

### Tor Browser

![Tor Browser](/images/2024-browsers/tor-browser.jpg)

- 開発元
  - The Tor Project
- 初版
  - 不明
- エンジン
  - `Quantum` (Gecko / SpiderMonkey)
- 対応OS
  - `Windows`
  - `macOS`
  - `Linux`
  - `iOS`
  - `Android`
- 料金
  - 無償
- ソースコード
  - https://github.com/torproject/tor

Tor Browser は The Tor Project によって開発されたオープンソースのウェブブラウザで、匿名化ネットワーク Tor を利用してインターネットにアクセスします。
Mozilla Firefox を基にしており、利用者に高度な匿名性を提供し、インターネット検閲の回避やプライバシーの保護を目的として使用されます。
このブラウザはプライバシーを重視し、標準の検索エンジンとして DuckDuckGo を採用しています。
常にプライベートブラウジングモードで動作し、セッション終了時には閲覧履歴や Cookie を自動的に削除するため、閲覧情報が第三者に勝手に閲覧されるリスクを軽減します。

https://www.torproject.org/ja/

## まとめ

2024年現在、主要なデスクトップブラウザについて紹介しました。
ブラウザの進化は著しく、新しいブラウザが続々と登場しています。

エンジニアとしてこれらのブラウザの特徴を把握しておくことは重要ですが、自分に合う次の相棒も見つけられれば幸いです。
