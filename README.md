これは_実践Rustプログラミング入門_の中のプログラムを写経したものをおいているれぽじとりです。

プログラムの著作権を侵害する意図はなく、純粋に学習目的でプログラムを写経しています。

#### 第4章

p.152 `use clap::Clap`を`use clap::Parser`、`#[derive(Clap, ...)]`を`#[derive(Parser, ...)]`に変更。

#### 第5章

Cargo.tomlで`actix-rt`を1.1.1にしないと動かない。

sqlite3が入っていない場合は`sudo apt install libsqlite3-dev`でsqlite3を導入
