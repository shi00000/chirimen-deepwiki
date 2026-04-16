[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/shi00000/chirimen-deepwiki)


# chirimen-deepwiki

CHIRIMENのAIアシスタント（[DeepWiki](https://deepwiki.com/shi00000/chirimen-deepwiki)）用のリポジトリです。

各リポジトリから必要なソースコードを自動で収集し、毎日同期します。

## 収録内容

| フォルダ | 取得元 |
|---|---|
| `sources/pizero-src` | [chirimen-oh/chirimen.org](https://github.com/chirimen-oh/chirimen.org) `pizero/src` |
| `sources/chirimen-drivers-packages` | [chirimen-oh/chirimen-drivers](https://github.com/chirimen-oh/chirimen-drivers) `packages` |
| `sources/node-web-gpio` | [chirimen-oh/node-web-gpio](https://github.com/chirimen-oh/node-web-gpio) |
| `sources/node-web-i2c` | [chirimen-oh/node-web-i2c](https://github.com/chirimen-oh/node-web-i2c) |
| `sources/remote-connection` | [chirimen-oh/remote-connection](https://github.com/chirimen-oh/remote-connection) |

## 同期

GitHub Actionsにより毎日UTC 0:00（日本時間 9:00）に自動同期されます。
