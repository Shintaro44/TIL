# Javaについて（変数）
- データ型の種類が８種類ある
- int型とlong型が利用されることが多い
- 変数のデータ型を途中で変更できない「静的型付け言語」である

# replitを用いた練習
- ※Javaでは命令の最後に「;」をつけること
- 必ず必要なコードは以下になる。class Main {
  public static void main(String[] args) {
    //ここに処理を記述する
  }
}
# 計算方法
- int radius; → int型の変数radiusを宣言
- radius = 5; → 変数radiusに整数の5を代入
- ※型の宣言が必要となる
# 推論型について
- var 変数名 = 値
- 代入する値からデータ型を推論できる
- ※データ型で「int」も「Integer」も（異なるものだが）整数型を表す
- ※Javaで変数を使用する際は宣言が必要　ただし宣言と同時に初期値を代入する場合は、省略することも可能となる
# 四則演算
- replitにて　System.out.println( + );　のコードで実行する
- 加算（+） 減算(-) 乗算(*) 除算(/) 剰余(%)
#　比較演算子
- ==	a == b	aとbが等しい場合true
- <	  a < b	  aがbより小さい場合true
- >	  a > b	  aがbより大きい場合true
- <=	a <= b	aがb以下の場合true
- >=	a >= b	aがb以上の場合true
- !=	a!= b	  aとbが等しくない場合true
- 
