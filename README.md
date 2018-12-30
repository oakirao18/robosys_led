## robosys_led

LEDを点滅させるデバイスドライバ

使用したものは以下の通りです。

・raspberryPI 3 B+

　 raspbian

・抵抗 150　オーム

・赤色LED

22番ピンからON/OFFの信号を発生させるデバイスドライバを作成した。

ONの時は数度点滅するようにした。

## 

LED_ON : echo '1' > /dev/myled0

LED_OFF: echo '0' > /dev/myled0

デモ：https://youtu.be/1aJdNM585Eg
