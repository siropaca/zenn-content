---
title: "2024年エンジニアとして知っておきたいデスクトップブラウザたち"
emoji: "🌐"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["browser"]
published: false
---

最近、知り合いや同僚のエンジニアが使っているパソコン環境を見てみると、へぇそんなブラウザあるんだと感じることがしばしばあります。
多くのブラウザが Chromium ベースであるため、開発上の問題はほとんどないのですが、Web に関わるエンジニアとしては、それぞれのブラウザの特性を把握しておきたいと思い、まとめてみることにしました。

## デスクトップブラウザ

### Google Chrome

![Google Chrome](/images/2024-browsers/google-chrome.jpg)

https://www.google.com/intl/ja/chrome/

- 開発元
  - Google LLC (アメリカ)
- 初版
  - 2008年9月2日 (15年前)
- エンジン
  - Browser: Chromium 
  - HTML: Blink
  - JavaScript: V8
- 対応OS
  - Windows
  - macOS
  - ChromeOS
  - Linux
- 料金
  - 無償
- ソースコード
  - Google Git: https://chromium.googlesource.com/chromium/src/+/refs/heads/main/chrome/
  - GitHub (mirror): https://github.com/chromium/chromium/tree/main/chrome

皆さんご存知 Google Chrome は、Google が開発した Chromium ベースのウェブブラウザです。
ブラウザのシェア率としては断トツで、世界中で最も多くのユーザーに利用されています。
プライバシー保護の観点からは懸念がありますが、サードパーティクッキーの廃止などのプライバシー保護に関する取り組みも進んでいます。

#### Chrome Beta

https://www.google.com/intl/ja/chrome/beta/

Chrome Beta は、おおよそ１つ先のバージョンが毎週リリースされる Google Chrome のベータ版です。

#### Chrome Dev

https://www.google.com/intl/ja/chrome/dev/

Chrome Dev は、おおよそ２つ先のバージョンが毎週リリースされる Google Chrome の開発版です。

#### Chrome Canary

https://www.google.com/intl/ja/chrome/canary/

Chrome Canary は、Google Chrome の最新のビルドが毎日リリースされる Google Chrome の開発最新版です。

### Mozilla Firefox

![Mozilla Firefox](/images/2024-browsers/mozilla-firefox.jpg)

https://www.mozilla.org/ja/firefox/new/

- 開発元
  - Mozilla Foundation (アメリカ)
  - Mozilla Corporation (アメリカ)
  - コミュニティ
- 初版
  - 2002年9月23日 (21年前)
- エンジン
  - Browser: Quantum
  - HTML: Gecko
  - JavaScript: SpiderMonkey
- 対応OS
  - Windows
  - macOS
  - Linux
  - iOS
  - Android
- 料金
  - 無償
- ソースコード
  - Mercurial: https://hg.mozilla.org/mozilla-central/
  - GitHub (mirror): https://github.com/mozilla/gecko-dev

Mozilla Firefox は、非営利組織である Mozilla Foundation によって開発されたオープンソースのウェブブラウザです。
Firefox は、プライバシー保護に配慮したブラウザとして知られており、プライベートブラウジング機能によりトラッキングを防止し、ユーザーのプライバシーを強力に保護することができます。

#### Firefox Beta

https://www.mozilla.org/ja/firefox/channel/desktop/#beta

プレビュー版の中で最も安定したプレリリースビルドで、近日リリース予定の機能を試すことができるバージョンです。

#### Firefox Developer Edition

https://www.mozilla.org/ja/firefox/developer/

開発者用に構築されたブラウザーで、カスタマイズされた設定や開発者ツールが搭載されています。

#### Firefox Nightly

https://www.mozilla.org/ja/firefox/channel/desktop/#nightly

不安定な開発中の試験版で、最新の機能を試すことができるバージョンです。

### Microsoft Edge (Chromium)

![Microsoft Edge](/images/2024-browsers/microsoft-edge.jpg)

https://www.microsoft.com/ja-jp/edge

- 開発元
  - Microsoft (アメリカ)
- 初版
  - 2020年1月15日 (4年前)
- エンジン
  - Browser: Chromium
  - HTML: Blink
  - JavaScript: V8
- 対応OS
  - Windows
  - macOS
  - Linux
  - iOS
  - iPadOS
  - Android
  - Xbox
- 料金
  - 無償
- ソースコード
  - 非公開

Chromium 版の Microsoft Edge は、EdgeHTML ベースの Edge（Microsoft Edge Legacy）から再構築されたブラウザです。
Chromium 版の Edge は、他のブラウザと互換性ができただけでなく、縦型のタブやコレクションなどの機能が搭載され、使い勝手も向上しています。

#### Edge Canary

https://www.microsoft.com/ja-jp/edge/download/insider

プレビュー版の中で最も新しく、最新の機能が含まれていますが、安定性は低いバージョンです。

#### Edge Dev

https://www.microsoft.com/ja-jp/edge/download/insider

カナリア版よりも安定したバージョンです。カナリアビルドからの改善が含まれています。

#### Edge Beta

https://www.microsoft.com/ja-jp/edge/download/insider

プレビュー版の中で最も安定したバージョンで、開発ビルドとカナリアビルドからの改善が含まれています。

### Safari

![Safari](/images/2024-browsers/safari.jpg)

https://www.apple.com/jp/safari/

- 開発元
  - Apple (アメリカ)
- 初版
  - 2003年1月7日 (21年前)
- エンジン
  - Browser: WebKit
  - HTML: WebKit
  - JavaScript: Nitro
- 対応OS
  - macOS
  - iOS
  - iPadOS
- 料金
  - 無償
- ソースコード
  - WebKit: https://webkit.org/
  - GitHub : https://github.com/WebKit/webkit

Safari は、Apple が開発したウェブブラウザで、macOS や iOS に標準搭載されています。

### Opera (Chromium)

![Opera](/images/2024-browsers/opera.jpg)

https://www.opera.com/ja

- 開発元
  - Opera Software ASA (ノルウェー)
- 初版
  - 1996年12月9日 (28年前)
- エンジン
  - Browser: Chromium
  - HTML: Blink
  - JavaScript: V8
- 対応OS
  - Windows
  - macOS
  - Linux
  - FreeBSD
  - Solaris
- 料金
  - 無償
- ソースコード
  - 非公開

Opera は、ノルウェーの Opera Software ASA によって開発されたウェブブラウザです。

#### Opera GX

![Opera GX](/images/2024-browsers/opera-gx.jpg)

https://www.opera.com/ja/gx

ゲーマー向けに設計された Opera GX は、ゲームとブラウジングの両方を快適に行うための機能が搭載されています。

### Vivaldi

![Vivaldi](/images/2024-browsers/vivaldi.jpg)

https://vivaldi.com/ja/

- 開発元
  - Vivaldi Technologies (ノルウェー)
- 初版
  - 2016年4月6日 (7年前)
- エンジン
  - Browser: Chromium
  - HTML: Blink
  - JavaScript: V8
- 対応OS
  - Windows
  - macOS
  - Linux
  - Android
  - iOS
  - iPadOS
- 料金
  - 無償
- ソースコード
  - 非公開

Operaの元開発者によって立ち上げられたブラウザ。プライバシー保護に配慮しているが、クローズドソースである。

### Brave

![Brave](/images/2024-browsers/brave.jpg)

https://brave.com/ja/

- 開発元
  - Brave Software (アメリカ)
- 初版
  - 2019年11月13日 (4年前)
- エンジン
  - Browser: Chromium
  - HTML: Blink
  - JavaScript: V8
- 対応OS
  - Windows
  - macOS
  - Linux
  - Android
  - iOS
- 料金
  - 無償
- ソースコード
  - GitHub: https://github.com/brave/brave-browser

Chromiumベースのブラウザの中で、プライバシーとセキュリティに優れている。Googleの追跡をブロックするための機能が充実している。

### Arc

![Arc](/images/2024-browsers/arc.jpg)

https://arc.net/

- 開発元
  - The Browser Company (アメリカ)
- 初版
  - 2022年4月19日 (2年前)
- エンジン
  - Browser: Chromium
  - HTML: Blink
  - JavaScript: V8
- 対応OS
  - Windows
  - macOS
  - iOS
- 料金
  - 無償
- ソースコード
  - 非公開

- Arcを開発したのはThe Browser Companyというニューヨークに拠点を置く企業。2019年にJosh Miller（CEO）とHursh Agrawal（CTO）によって設立されたスタートアップだ。

### Sidekick

![Sidekick](/images/2024-browsers/sidekick.jpg)

https://www.meetsidekick.com/ja/

- 開発元
  - PushPlayLabs (アメリカ)
- 初版
  - 不明
- エンジン
  - Browser: Chromium
  - HTML: Blink
  - JavaScript: V8
- 対応OS
  - macOS
- 料金
  - 一部機能が有料（Sidekick Pro）
- ソースコード
  - 非公開

### DuckDuckGo

![DuckDuckGo](/images/2024-browsers/duck-duck-go.jpg)

https://duckduckgo.com/

- 開発元
  - DuckDuckGo (アメリカ)
- 初版
  - 不明
- エンジン
  - Browser: Chromium (Windows) / WebKit (macOS)
  - HTML: Blink (Windows) / WebKit (macOS)
  - JavaScript: V8 (Windows) / Nitro (macOS)
- 対応OS
  - Windows
  - macOS
- 料金
  - 無償
- ソースコード
  - 非公開

検索エンジンのDuckDuckGoが開発したブラウザ。プライバシー保護を重視しているが、セキュリティは十分でない。

### Tor Browser

![Tor Browser](/images/2024-browsers/tor-browser.jpg)

https://www.torproject.org/ja/

- 開発元
  - The Tor Project
- 初版
  - 不明
- エンジン
  - Browser: Quantum
  - HTML: Gecko
  - JavaScript: SpiderMonkey
- 対応OS
  - Windows
  - macOS
  - Linux
  - Android
- 料金
  - 無償
- ソースコード
  - https://github.com/torproject/tor

Tor Browserの既定の検索エンジンは、プライバシー保護を重視している検索エンジンのDuckDuckGoである。
匿名性を重視したブラウザ。プライバシー保護機能が充実しているが、速度が遅く、使いにくい。

## まとめ
