# S2J Site Policy Manager - CHANGELOG

## unreleased

## 0.0.1 - 2026-09-29

* リポジトリ名を `s2j-site-policy-manager` とした。スラッグの `s2j-site-policy` だけでは、プラグインが何をするものかが伝わらないためである。`package.json` の name と GitHub の URL を合わせた。

* 製品の方向性を検討メモ `docs_mod/product-direction.md` に記録した。表示名、台帳、段階を含み、仕様本文ではない。
* `docs_mod/specs.md` から検討メモに案内し、仕様本文は方向性を確定したあとに書くとした。
* リポジトリ名を `s2j-site-policy` とし、`package.json` の name と GitHub の URL を合わせた。

## 0.0.1 - 2026-09-28

* `package.json` を追加し、description は暫定文言にした。
* npm@12の EALLOWGIT に対応するため、`.npmrc` で Git 依存の取得を許可した。
* `@s2j/docs-linter` を導入し、ドキュメント lint と install script を設定した。
