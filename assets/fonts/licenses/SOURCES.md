# Bundled font sources and attribution

All four bundled web fonts are redistributed under the SIL Open Font
License 1.1. The complete license text supplied by each upstream project is
stored next to this file. The WOFF2 files are format conversions of the
official full-font TTF files listed below; no glyph subsetting was performed.

Conversion was performed with FontTools 4.63.0 and Brotli 1.2.0 by loading the
official TTF and saving it with `font.flavor = "woff2"`. The conversions keep
the original family/name records. In particular, the LXGW WenKai OFL file
contains upstream's additional permission to retain its Reserved Font Names
when the original is converted to WOFF/WOFF2 solely for web-font delivery.

## Noto Serif SC

- Attribution: Google; font copyright `(c) 2017-2024 Adobe` as recorded in
  Google Fonts metadata.
- Version: 2.003-H1.
- Source: `NotoSerifSC[wght].ttf`, the complete variable font (weight 200-900).
- Official distribution commit: `google/fonts@2796410152d4f9524b68ed46e69c1b60f8e0f7c3`.
- Source URL: <https://raw.githubusercontent.com/google/fonts/2796410152d4f9524b68ed46e69c1b60f8e0f7c3/ofl/notoserifsc/NotoSerifSC%5Bwght%5D.ttf>
- Source size / SHA-256: `25,125,512` bytes / `050080d9255a86808f2945bffac582b31ef32bc36411ce29563b4961670c66f9`.
- Google Fonts blob SHA: `eab063faf229160a52d3760f5555150e4eb9e5bf`.
- Upstream project recorded by Google Fonts: <https://github.com/notofonts/noto-cjk>.
- Bundled file: `noto-serif-sc.woff2`; 31,058 glyphs and 30,928 mapped Unicode scalars.
- License: `OFL-Noto-Serif-SC.txt`; official metadata:
  `METADATA-Noto-Serif-SC.pb`.
- Official license source: <https://raw.githubusercontent.com/google/fonts/2796410152d4f9524b68ed46e69c1b60f8e0f7c3/ofl/notoserifsc/OFL.txt>.

## LXGW WenKai

- Attribution: LXGW and the Klee Project Authors, as specified in the bundled
  upstream OFL file.
- Version: 1.522 (March 17, 2026).
- Source: `LXGWWenKai-Regular.ttf`, complete static Regular font (weight 400).
- Official upstream commit: `lxgw/LxgwWenKai@ed634e2291ff8adcffbab553d6c26cc95a0e4a0c`.
- Source URL: <https://raw.githubusercontent.com/lxgw/LxgwWenKai/ed634e2291ff8adcffbab553d6c26cc95a0e4a0c/fonts/TTF/LXGWWenKai-Regular.ttf>
- Source size / SHA-256: `25,575,676` bytes / `39ad71264b588165b469e35e6afb162a378dacd1f95348160240ba9038ac3009`.
- Upstream blob SHA: `3e050e87caa5ce47f9c873079183e31f88fb8ce5`.
- Upstream project: <https://github.com/lxgw/LxgwWenKai>.
- Bundled file: `lxgw-wenkai.woff2`; 46,867 glyphs and 46,490 mapped Unicode scalars.
- License: `OFL-LXGW-WenKai.txt`.
- Official license source: <https://raw.githubusercontent.com/lxgw/LxgwWenKai/ed634e2291ff8adcffbab553d6c26cc95a0e4a0c/OFL.txt>.

## Noto Sans SC

- Attribution: Google; Adobe/Source copyright and Reserved Font Name as
  recorded in Google Fonts metadata and the bundled OFL file.
- Version: 2.004-H2.
- Source: `NotoSansSC[wght].ttf`, the complete variable font (weight 100-900).
- Official distribution commit: `google/fonts@2796410152d4f9524b68ed46e69c1b60f8e0f7c3`.
- Source URL: <https://raw.githubusercontent.com/google/fonts/2796410152d4f9524b68ed46e69c1b60f8e0f7c3/ofl/notosanssc/NotoSansSC%5Bwght%5D.ttf>
- Source size / SHA-256: `17,772,300` bytes / `a3041811a78c361b1de50f953c805e0244951c21c5bd412f7232ef0d899af0da`.
- Google Fonts blob SHA: `fb0637bafbcd804fe32152370a1225990745b4bc`.
- Upstream project recorded by Google Fonts: <https://github.com/notofonts/noto-cjk>.
- Bundled file: `noto-sans-sc.woff2`; 31,036 glyphs and 30,890 mapped Unicode scalars.
- License: `OFL-Noto-Sans-SC.txt`; official metadata:
  `METADATA-Noto-Sans-SC.pb`.
- Official license source: <https://raw.githubusercontent.com/google/fonts/2796410152d4f9524b68ed46e69c1b60f8e0f7c3/ofl/notosanssc/OFL.txt>.

## ZCOOL XiaoWei

- Attribution: designer Li Dawei and the ZCOOL XiaoWei Project Authors, as
  recorded in Google Fonts metadata and the bundled OFL file.
- Version: 1.000.
- Source: `ZCOOLXiaoWei-Regular.ttf`, complete static Regular font (weight 400).
- Official distribution commit: `google/fonts@2796410152d4f9524b68ed46e69c1b60f8e0f7c3`.
- Source URL: <https://raw.githubusercontent.com/google/fonts/2796410152d4f9524b68ed46e69c1b60f8e0f7c3/ofl/zcoolxiaowei/ZCOOLXiaoWei-Regular.ttf>
- Source size / SHA-256: `6,313,808` bytes / `a42b620140f493db42f741351dfbf343c0936d58588ee8004b8b2a218d997ff1`.
- Google Fonts blob SHA: `2d8731a231f2e6625b32d96b87f84852e24f9d82`.
- Upstream project recorded by Google Fonts: <https://github.com/googlefonts/zcool-xiaowei>.
- Bundled file: `zcool-xiaowei.woff2`; 7,019 glyphs and 7,016 mapped Unicode scalars.
- License: `OFL-ZCOOL-XiaoWei.txt`; official metadata:
  `METADATA-ZCOOL-XiaoWei.pb`.
- Official license source: <https://raw.githubusercontent.com/google/fonts/2796410152d4f9524b68ed46e69c1b60f8e0f7c3/ofl/zcoolxiaowei/OFL.txt>.

## Integrity verification

Each WOFF2 begins with the required `wOF2` signature and was successfully
decoded again with FontTools. Source-to-WOFF2 checks matched for glyph order,
Unicode cmap, variation axes, units-per-em, and horizontal-metrics count. The
Noto files remain variable fonts with their full original weight ranges. The
static LXGW and ZCOOL files remain weight 400. See `../SHA256SUMS.txt` for
checksums of every distributed file.
