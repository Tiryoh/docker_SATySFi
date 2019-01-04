# docker_SATySFi

## Usage

* `Makefile`がある場合
  ```bash
  docker run --rm --volume "${PWD}":/source tiryoh/satysfi
  ```
* 手動でビルドする場合
  * 手動で実行するコマンド例: `satysfi doc.saty -o output.pdf`
  ```bash
  docker run --rm --volume "${PWD}":/source tiryoh/satysfi satysfi doc.saty -o output.pdf
  ```

## 参考

* https://github.com/odanado/SATySFi-docker
* https://github.com/pandaman64/SATySFi-docker
* https://gist.github.com/zr-tex8r/bf38067a0d302eba5ab52acb8c0f9f30
