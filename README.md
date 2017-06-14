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
【sum();
undefined
function sum() {
    var total = 0;
    for (var counter = 1; counter <= 10; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefinedfunction sum(rangeTo) {
    var total = 0;
    for (var counter = 1; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefinedfunction sum(rangeFrom, rangeTo) {
    var total = 0;
    for (var counter = rangeFrom; counter <= rangeTo; counter++) {
        total += counter;
    }
    window.alert(total);
}
undefinedsum(2, 5);
undefined】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【なんとなく使い方が分かった】

### 疑問・分からないこと（もしあれば）

【まだ、よく深いところまでわかりません】

--------------------------------------

以下、教科書の自分で読んだ・実行した箇所について書く。

## 4-3 (p.83)

### Consoleの実行ログ

```
【if (window.innerWidth < 1000) {
    window.alert('狭いです');
} else {
    window.alert('狭いです');
}
undefinevar ampleArray = [];
undefineddvar examinationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65 ,81, 63, 45
    function calculateTotal(scores) {
    var total = 0;
    for (var index = 0; index < scores. length; index++) {
        total += scores[index];
    }
    return total;
}
undefinedexaminationScores[0];   // 情報のテスト結果　(の配列)
59】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【自分で書いたものは大体わかりました。】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】
