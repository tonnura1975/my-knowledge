
# PHP のナレッジ

## 参考URL

- PHP: PHP マニュアル - Manual
https://www.php.net/manual/ja/index.php

- PHP (プログラミング言語) - Wikipedia
https://ja.wikipedia.org/wiki/PHP_(%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E8%A8%80%E8%AA%9E)

- 初心者がプログラミングを勉強するときにやってはいけない 5 つのこと - paiza 開発日誌
https://paiza.hatenablog.com/entry/2018/09/03/%E5%88%9D%E5%BF%83%E8%80%85%E3%81%8C%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E3%82%92%E5%8B%89%E5%BC%B7%E3%81%99%E3%82%8B%E3%81%A8%E3%81%8D%E3%81%AB%E3%82%84%E3%81%A3%E3%81%A6

## 標準関数

- fgets() 関数
ファイルポインタから 1 行取得する。
http://php.net/manual/ja/function.fgets.php

- trim() 関数
文字列の先頭および末尾にあるホワイトスペースを取り除く。
http://php.net/manual/ja/function.trim.php

## 条件分岐

<?php
    $name = trim(fgets(STDIN));
    if ($name == "PHP") {
        echo "Welcome\n";
    }
?>

<?php
    $name = trim(fgets(STDIN));
    echo "Hello " . $name . "\n";

    if ($name == "PHP") {
        echo "Welcome\n";
    } else {
        echo "Goodbye\n";
    }
?>

<?php
    $name = trim(fgets(STDIN));
    echo "Hello ".$name."\n";

    if ($name == "PHP") {
        echo "Welcome\n";
    } elseif ($name == "php") {
        echo "Good morning\n";
    } else {
        echo "Goodbye\n";
    }
?>

<?php
    $number = trim(fgets(STDIN));
    echo $number . "\n";

    if ($number == 10) {
        echo $number . "は10に等しい\n";
    } elseif ($number > 10) {
        echo $number . "は10より大きい\n";
    } else {
        echo $number . "は10未満\n";
    }
?>
