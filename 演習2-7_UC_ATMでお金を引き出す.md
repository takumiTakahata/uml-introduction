### ATMで「お金を引き出す」
### 銀行のATMを利用して、自分の口座からキャッシュカードで必要なお金を引き出します。
### 利用者
### アクターが口座とキャッシュカードを持っていること。
### アクターの口座から指定された金額が引き出されること。
### 【基本フロー】
* キャッシュカードを入れます。
* お引き出しを押します。
* 暗証番号を入力します。(E-1)
* 引出す金額を入力します。
* 金額を確認します。
* 利用明細の「要/不要」を選びます。
* カード・利用明細・現金を受取ります。
### 【代替フロー】
* E-1:暗証番号の再入力を促す
### 【例外フロー】
### ATMで「お金を引き出す」
### 【基本シナリオ】
1. 引き出しが成功する場合
2. ATMにキャッシュカードを入れる
3. お引き出しを選択する
4. 暗証番号「1111」を入力する
5. 引き出したい金額「10000円」を入力する
6. 金額を確認する
7. 利用明細「要」を押す
8. カード、利用明細、現金を受け取る
### 【例外シナリオ】