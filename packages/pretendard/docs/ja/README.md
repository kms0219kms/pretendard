[한국어](/packages/pretendard/README.md) | [English](/packages/pretendard/docs/en/README.md) | [**日本語**](/packages/pretendard/docs/ja/README.md)

# Pretendard

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/orioncactus/pretendard/blob/HEAD/docs/images/thumbnail/dark/thumbnail.svg">
  <img src="https://github.com/orioncactus/pretendard/blob/HEAD/docs/images/thumbnail/light/thumbnail.svg" alt="Thumbnail">
</picture>

Pretendardは、クロスプラットフォームで製品を提供するとき、そして多言語タイポグラフィでも自然な現代的なフォントです。[Inter](https://github.com/rsms/inter)と[源ノ角ゴシック](https://fonts.adobe.com/fonts/source-han-sans-japanese)、そして[M PLUS 1p](https://github.com/coz-m/MPLUS_FONTS)に基づいて整えられたPretendardは、読み込み環境で可読性と視覚補正のために追加の作業をする必要はありません。

Pretendardは9種類の太さで提供され、可変フォントにも対応しています。

## 背景と概要

Pretendardの背景や特徴、OpenType機能などを説明する詳細な話は[こちら(韓国語)](https://cactus.tistory.com/306)で確認できます。

## ダウンロード

### [最新バージョンをダウンロード](https://github.com/orioncactus/pretendard/releases/latest)

## ファミリー

特定の環境に適したPretendardを使用するには、以下をご覧ください

-   [Pretendard JP](/packages/pretendard-jp/docs/ja/)：日本の環境に適しており、韓国の漢字環境に対応するOpenType機能があります。
-   [Pretendard Std(英語)](/packages/pretendard-std/docs/en/)：ラテン環境に適しています。
-   [Pretendard GOV(韓国語)](/packages/pretendard-gov/)：韓国の公共サービス環境に適しています。

## Webフォント

PretendardはCDNを通じてWebフォントとして使用できます。

### 推奨：可変ダイナミックサブセット

可変Weight属性をサポートし、ページに必要な文字のみを選択的にダウンロードして、**最も速く効率的**にPretendardを使用できる方法です。使用するfont-familyの名前は`"Pretendard Variable"`です。

HTMLの`<head>`タグ内に以下のコードを追加してください：

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css" />
```

そしてCSSでfont-familyを指定してください：

```css
body {
    font-family: "Pretendard Variable", Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
}
```

<details>

<summary>他の方法を見る</summary>

#### CSS importを使用

HTML `<link>`タグの代わりにCSSで直接読み込むこともできます：

```css
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css");
```

#### 他のCDNを使用

cdnjs、UNPKGなどの他のCDNを使用したい場合や、ダイナミックサブセット・可変フォント・静的フォントなどの他のオプションが必要な場合は[Webフォントガイド](/packages/pretendard/docs/ja/webfonts.md)をご参照ください。

</details>

👉 すべてのWebフォントオプションの詳細は[Webフォントガイド](/packages/pretendard/docs/ja/webfonts.md)をご参照ください。

## パッケージ

Pretendardは以下のパッケージマネージャで利用できます。

-   [npm](https://www.npmjs.com/package/pretendard)

```bash
npm i pretendard
```

-   [Yarn](https://yarnpkg.com/package/pretendard)

```bash
yarn add pretendard
```

## システムフォント

Pretendardはデバイスにインストールしてシステムフォントとして使用できます。

-   [homebrew-cask-fonts](https://github.com/Homebrew/homebrew-cask-fonts)

```bash
brew tap homebrew/cask-fonts
brew install font-pretendard
```

-   [NixOS](https://nixos.org)

```nix
# configuration.nix
{
  fonts.packages = with pkgs; [
    pretendard
  ];
}
```

-   [AUR](https://aur.archlinux.org/packages?K=pretendard)

```bash
yay -S otf-pretendard
yay -S ttf-pretendard
```

## クレジット

#### ベース

[Inter](https://github.com/rsms/inter): Rasmus Andersson

#### ハングルグリフ

[Source Han Sans](https://github.com/adobe-fonts/source-han-sans): Adobe, Google, Sandoll Communications; Jang Soo-young and Kang Joo-yeon

#### 仮名グリフ

[M PLUS 1p](https://github.com/coz-m/MPLUS_FONTS): UNDERFOREST DESIGN; 森下浩司

#### リデザインと制作

Kil Hyung-jin

## ライセンス

Pretendardは[SIL Open Font License](https://scripts.sil.org/OFL)として配布されています。フォントの単独販売を除くすべての商業行為、修正、再配布が可能です。

## コントリビューター

Pretendardにコントリビュートしていただきありがとうございます。

[@hiddenest](https://github.com/hiddenest): WebフォントサービングとCDNアップデートの自動化、サブセットとダイナミックサブセットの作業、そして可変ダイナミックサブセットの自動化を作業してくださいました。

[@leejh10003](https://github.com/leejh10003): Pretendardが使用された[例](/examples)を作成しました。

[@black7375](https://github.com/black7375): すべてのWebフォントビルド自動化、npmjsおよびYarnにPublishおよびリリースファイル生成自動化、CDN URLでブザーニング改善、monorepo対応、ビルドパフォーマンスの向上、そしてPretendard GOV CDNのドキュメンテーション作業を行ってくださいました。

[@victorrica](https://github.com/victorrica): npmとYarn パッケージの配布を作業しました。

[@kms0219kms](https://github.com/kms0219kms): すべてのWebフォントCDN配布多重化、ReadmeでのFormattingの改善、Readmeの英語及び日本語文書化を作業してくださいました。

[@Gamsake](https://github.com/Gamsake): ビルド自動化を改善しました。

[@quiple](https://github.com/quiple): 日本語Readme翻訳を改善してくださいました。

[@sudosubin](https://github.com/sudosubin): homebrew-cask-fontsとnixにPretendardを追加しました。

## Issues

解決が必要な場合は、[Issues](https://github.com/orioncactus/pretendard/issues)でIssueを登録してください。
