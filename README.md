# 6/14 課題 学んだ記録

自身が学んだ記録を作りましょう。

- 関数(`function` で始まるコード)は全て function.js に書きます
- その他をREADME.md（このファイル）に書いていきます
    - 書き方は README-example.md (同じフォルダに同梱) を参考にしてください
- 書き方は自身でアレンジしてもかまいません


--------------------------------------

## 授業スライドの説明（4時間目～5時間目）

説明の中で実行したログ、分かったこと、疑問などがあればここに書く。

### Consoleの実行ログ

```
function sum() {
    var total = 0;
	for (var counter = 1; counter <= 10; counter++) {
        total += counter;
    }
	window.alert(total);
}
undefined
sum();
undefined
function sum(rangeTo) {
    var total = 0;
    for (var counter = 1; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefined
function sum(rangeFrom,rangeTo) {
    var total = 0;
	for (var counter = 2; counter <= 5; counter <= 5; counter++) {
		total += counter;
    }
	window.alert(total);
VM864:3 Uncaught SyntaxError: Unexpected token ;

    var total = 0;
	for (var counter = 2; counter <= 5; counter <= 5; counter++) {
		total += counter;
    }
	window.alert(total);
VM897:3 Uncaught SyntaxError: Unexpected token ;
var total = 0;
for (var counter = 2; counter <= 5; counter <= 5; counter++) {
	total += counter;
}
window.alert(total);
VM914:2 Uncaught SyntaxError: Unexpected token ;

    var total = 0;
	for (var counter = 2; counter <= 5; counter++) {
		total += counter;
    }
	window.alert(total);
undefined
function sum(rangeFrom, rangeTo) {
    var total = 0;
	for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefined
sum(1,10);
undefined
sum(2,5);
undefined
var total = 0;
for (var counter = rangeFrom; counter <= rangeTo; counter++) {
    total += counter;
}
window.alert(total);
VM1318:2 Uncaught ReferenceError: rangeFrom is not defined
    at <anonymous>:2:20
    var total = 0;
for (var counter = 2; counter <= 5; counter++) {
	total += counter;
}
window.alert(total);
undefined
function sum(rangeFrom,rangeTo = 10) {
    var total = 0;
	for (var counter = rangeFrom; counter <= ranfgeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefined
function sum(rangeFrom,rangeTo = 10) {
    var total = 0;
	for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefined
sum(1);
undefined
function sum(rangeFrom = 1, rangeTo) {	// エラー
}
undefined
function sum(rangeTo, rangeFrom = 1) {
    var total = 0;
	for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefined
sum(10);
undefined
function sum(rangeTo, rangeFrom = 1) {
	var total = 0;
	for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefined
sum(10);
undefined
total;
14
sum(2,5);
undefined
total;
14
var hoge = 5;
function testScope() {
    window.alert(hoge);
}
undefined
testScope();
undefined
function sum(rangeFrom, rangeTo) {
    let total = 0;
	for (let counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefine
function sum(rangeFrom, rangeTo) {
    let total = 0;
	for (let counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefined
sum(1,10);
undefined
function sum(rangeFrom,rangeTo,withDialog) {
    var total = 0;
	for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    if(withDialog){
        window.alert(total);
    }else{
        console.log(total);
    }
}
undefined
var total = 0;
function sum(rangeFrom, rangeTo) {
	for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
}
undefined
sum(1,10);
undefined
window.alert(total);
undefined
sum(1,10);
undefined
window.alert(total);
undefined
function sum(rangeFrom,rangeTo) {
    var total = 0;
	for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    return total;}
undefined
sum(1,10);
55
window.alert(sum(1,10));
undefined
```

### Console以外の動き（もしあれば）

このページの内容５５がでた
このページの内容１４がでた
このページの内容５５がでた
このページの内容１４がでた
このページの内容１４がでた
このページの内容５５がでた
このページの内容５５がでた
このページの内容５５がでた
このページの内容１４がでた
このページの内容５がでた
このページの内容５５がでた
このページの内容５５がでた
このページの内容１１０がでた
このページの内容５５がでた
### 分かったこと

【ここに書く】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】

--------------------------------------

以下、教科書の自分で読んだ・実行した箇所について書く。

## 4-x ○○ (p.xx)

### Consoleの実行ログ

```
【ここに書く】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【ここに書く】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】
