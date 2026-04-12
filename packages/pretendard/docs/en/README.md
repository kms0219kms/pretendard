[한국어](/packages/pretendard/README.md) | [**English**](/packages/pretendard/docs/en/README.md) | [日本語](/packages/pretendard/docs/ja/README.md)

# Pretendard

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/orioncactus/pretendard/blob/HEAD/docs/images/thumbnail/dark/thumbnail.svg">
  <img src="https://github.com/orioncactus/pretendard/blob/HEAD/docs/images/thumbnail/light/thumbnail.svg" alt="Thumbnail">
</picture>

Pretendard is a Neo-grotesque typeface suitable for cross-platform applications and multilingual typography. Pretendard is designed based on [Inter](https://github.com/rsms/inter), [Source Han Sans](https://fonts.adobe.com/fonts/source-han-sans-korean), and [M PLUS 1p](https://github.com/coz-m/MPLUS_FONTS). It provides enhanced text legibility without requiring further adjustments of scaling, letter-spacing, optical adjustments.

Pretendard is available in 9 weights, and also supports variable fonts.

## Background and story

You can read a detailed story about Pretendard’s background, features, and OpenType features [here(Korean)](https://cactus.tistory.com/306).

## Download

### [Download latest version](https://github.com/orioncactus/pretendard/releases/latest)

## Family

To use Pretendard suitable for a specific environment, check below:

-   [Pretendard JP](/packages/pretendard-jp/docs/en/): Suitable for the Japanese environment and can be used for Korean Han environments with OpenType features.
-   [Pretendard Std](/packages/pretendard-std/docs/en/): Suitable for Latin/Greek/Cyrillic-only environments.
-   [Pretendard GOV(Korean)](/packages/pretendard-gov): Suitable for the public service environment in Republic of Korea.

## Webfonts

You can use Pretendard as a web font via CDN.

### Recommended: Variable dynamic subset

Supports variable weight axis and dynamically downloads only the characters included on the page, providing the **fastest and most efficient** way to use Pretendard. Provided font-family name is `"Pretendard Variable"`.

Add the following code inside the `<head>` tag in your HTML:

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css" />
```

Then specify the font-family in your CSS:

```css
body {
    font-family: "Pretendard Variable", Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
}
```

<details>

<summary>Other methods</summary>

#### Using CSS import

Instead of an HTML `<link>` tag, you can also import directly in CSS:

```css
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css");
```

#### Using other CDNs

For using other CDNs such as cdnjs and UNPKG, or for other options like dynamic subset, variable font, and static font, see the [Webfont Guide](/packages/pretendard/docs/en/webfonts.md).

</details>

👉 For a complete list of all webfont options, see the [Webfont Guide](/packages/pretendard/docs/en/webfonts.md).

## Package

Pretendard is available in the following package managers.

-   [npm](https://www.npmjs.com/package/pretendard)

```bash
npm i pretendard
```

-   [Yarn](https://yarnpkg.com/package/pretendard)

```bash
yarn add pretendard
```

## System font

Pretendard can be installed on the machine and used as a system font.

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

## Credit

#### Base

[Inter](https://github.com/rsms/inter): Rasmus Andersson

#### Hangul glyphs

[Source Han Sans](https://github.com/adobe-fonts/source-han-sans): Adobe, Google, Sandoll Communications; Jang Soo-young and Kang Joo-yeon

#### Kana glyphs

[M PLUS 1p](https://github.com/coz-m/MPLUS_FONTS): UNDERFOREST DESIGN; Coji Morishita

#### Combine and redesign

Kil Hyung-jin

## License

Pretendard is distributed under the [SIL Open Fonts License](https://scripts.sil.org/OFL), which is allowed any commercial uses, modifications, and redistribution.

## Contributors

Thank you so much for your contribution to Pretendard.

[@hiddenest](https://github.com/hiddenest): Worked serving webfonts, creating CDN assets purge automation, Providing webfonts subset and dynamic subset, and automating variable dynamic subset.

[@leejh10003](https://github.com/leejh10003): Worked making an [example](/examples) using Pretendard.

[@black7375](https://github.com/black7375): Worked automating all Webfont builds, automating release file creation, automating publish on npmjs and Yarn, improving versioning from CDN URLs, setting monorepo, and improving build performance, and documenting Pretendard GOV CDN.

[@victorrica](https://github.com/victorrica): Worked publishing npm and Yarn packages.

[@kms0219kms](https://github.com/kms0219kms): Worked all webfonts CDN multiplexing, improving formatting from documentation, and readme localization.

[@Gamsake](https://github.com/Gamsake): Worked improving build automation.

[@quiple](https://github.com/quiple): Worked improving Japanese Readme translation.

[@sudosubin](https://github.com/sudosubin): Added Pretendard to homebrew-cask-fonts and nix.

## Issues

If you have a ploblem, please open an issue on [Issues](https://github.com/orioncactus/pretendard/issues).
