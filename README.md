# go-wiki

## 学んだこと
- Go言語 は class の代わりに **struct** を利用する
- 他言語で言うインスタンスメソッドは以下のように定義できる
  - `func (p *Page) save() error {`
    - func と save の間にある `(p *Page)` が大事
    - **p は Page へのポインタを受け取る**
    - Page データ構造があれば、それは save メソッドを呼ぶことができる
- エラーは投げるのではなく返す方針
- & 演算子 を使うことで、作成した Page データ構造への参照を取れる
