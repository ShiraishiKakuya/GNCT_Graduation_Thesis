RS232Cの簡単な動作テストプログラムです。
M62398FP基板で送受信確認しました。

PC側からASCIIコードで文字を送付すると、リターンで
その文字がPC上に表示されます。
なお、送付文字の最後にeをつけます。
例　1e　
　　123e
　　123456789eなど

ボーレートは 9600,8ビット,パリティなし,ストップビット１
です。
PC側はハイパーターミナルでも何でも。
ちなみには’シリアルはWinで行こう’（フリーソフト）
を使いました。