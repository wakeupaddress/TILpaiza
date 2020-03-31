D008:奇数か偶数か
```
<?php

    $input_line = fgets(STDIN);

    if($input_line%2===0){
        echo even;
    }else{
        echo odd;
    }

?>
```
D029:サイコロの裏面 
```
<?php
    // 標準入力から値を取得してinput_lineに入れる
    $input_line = fgets(STDIN);
    
    switch($input_line){
        case 1 :
            echo 6;
            break;
        case 2 : 
            echo 5;
            break;
        case 3 :
            echo 4;
            break;
        case 4 :
            echo 3;
            break;
        case 5:
            echo 2;
            break;
        case 6 :
            echo 1;
    }
    
?>
```
D102:運賃の計算
```
<?php
    // 標準入力から値を取得してinput_lineに入れる
    $input_line = fgets(STDIN);
    
    $taxi=$input_line*10;
    
    echo 100+$taxi;
    
?>
```
C051:カード並べ 
(検討中)
```
<?php
    // 標準入力から値を取得してinput_lineに入れる
    $input_line = fgets(STDIN);

    $number = rand(1,9);
    $number1 = rand(1,9);
    $number2 = rand(1,9);
    $number3 = rand(1,9);
    
?>
```