# ZMK Config roBa

## References

- ZMK docs: https://v0-3-branch.zmk.dev/docs/keymaps/behaviors
  - behavior や設定を調べる際はこの URL を参照する
- roBa ビルドガイド: https://github.com/kumamuk-git/roBa/blob/main/doc/v3/buildguide_v3.md
  - ハードウェアの仕様や組み立て手順を調べる際はこの URL を参照する

## Project Overview

roBa カスタム分割キーボードの ZMK ファームウェア設定。

- **MCU**: Seeeduino XIAO BLE（左右）
- **Central（右）**: PMW3610 トラックボール（25mm ボール）、ZMK Studio 有効
- **フォームファクタ**: ロープロファイル
- **Peripheral（左）**: EC11 エンコーダ
- **ビルド**: GitHub Actions（`build.yaml`）
