我が家のUbuntuでは音声をrootではないと出力できないのでrootで実行
$ sudo apt-get install rtmpdump swftools libxml2-utils mplayer
$ ./radiko -p BAYFM78
このBAYFM78みたいなキー（文字列）は、radiko.jpの各ラジオ局のページのURLで確認できる。w3mとか使えばサーバーでもok。

自分で各ラジオ局のキーをまとめてみたら以下のようになった。

ラジオ局	キー
802	802
FMCOCOLO	CCL
NHK第1	JOAK
NHK第2	JOAB
NHK FM	JOAK-FM
FM横浜	YFM
文化放送	QRR
ラジオNIKKEI第1	RN1
ラジオNIKKEI第2	RN2
Jwave	FMJ
bayfm78	BAYFM78
TBSラジオ	TBS
NACK5	NACK5
TOKYOFM	FMT
ニッポン放送	LFR
ラジオ日本	JORF
放送大学	HOUSOU-DAIGAKU
InterFM	INT
もしバッググラウンドで動かしたいなら以下のように。

https://qiita.com/onokatio/items/86755bb3083e414f1a3a
https://mtunn.wordpress.com/2017/02/08/raspberrypi3%E3%81%A7radiko/
