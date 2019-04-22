## proc_macro について

fukuoka.rs-vol.3

---

## About me

name: nasa (近藤アサン)

所属: 福岡工業大学 ３年

Twitter: @nasa_desu

GitHub: k-nasa

---

## 何となく Rspec が書きたくなった

Rust で！

- Rspec は簡潔で読みやすいテストコードが書ける
- before,subject などのブロックで囲むだけで共通部分が抜き出せて良い
- Rust ではちまちま型を書くのがだるい,,,

---

## 暇なので作ろう！

の前に既存のがありそうなので調べた (モチベーションに関わるので)

あるにはあったけど、、、

- rspec
- speculate

---

#### rspec

名前からして完璧!!と思ったけど

記法がみびょい

全部クロージャを渡す形

![rspec](./assets/rspec.png)

---

#### speculate

いい感じだった。けど

![speculate](./assets/speculate.png)

ビルドできない(かった)

---

#### では作るぞ！

というか作った

![ruspec](./assets/ruspec.png)
