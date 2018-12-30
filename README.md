## robosys_led

LEDを点滅させるデバイスドライバ

## Demo

https://youtu.be/1aJdNM585Eg


## Description

22番ピンからON/OFFの信号を発生させることができる。

ONの時は数度点滅する。

使用したものは以下の通りです。

・raspberryPI 3 B+

　 raspbian

・抵抗 150　オーム

・赤色LED

・ブレッドボード

・ジャンパー線

## Install

```
git clone https://github.com/oakirao18/robosys_led.git
```

## Usage

```
make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0
```


LED_ON
```
echo '1' > /dev/myled0
```
LED_OFF
```
echo '0' > /dev/myled0
```

## Licence

[GPL](https://www.gnu.org/licenses/gpl-3.0.ja.html)
