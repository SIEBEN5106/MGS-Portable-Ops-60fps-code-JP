# MGS-Portable-Ops-60fps-code-JP
日本版MGSポータブルオプスの60fpsコード。

壁張り付きができるUS版V3コードを移植しました。

US版コードの作者であるKabuto_Kun氏に感謝します。

PPSSPP用です。

```

_S ULJM-05193/ULJM-05227/ULJM-05284/UCAS-42087
_G Metal Gear Solid - Portable Ops [JAP/ASIA]
_C1 60 FPS v3 [Ingame only]
_L 0xE0130003 0x001F52D0
_L 0x201F52D0 0x00000001
_L 0x201F5098 0x00000005
_L 0x201F2EE0 0x00000001
_L 0x201F50A4 0x00000000
_L 0x201F50A8 0x3F800000
_L 0x201F50AC 0x3F800000
_L 0x201F50B0 0x40AE38E4
_L 0x20218F2C 0x0000003C
_L 0x200EE3E0 0x0A200D81//WallSneak60Fix,a
_L 0x200EE3F0 0x44950000//WallSneak60Fix,b
_L 0x20003604 0x2415000A//WallSneak60Fix,c
_L 0x20003608 0x0A23B8F9//WallSneak60Fix,d
_L 0x2000360C 0x44802000//WallSneak60Fix,e
_L 0x201236A8 0x00121803//ChaffGrenade,a
_L 0x201236F4 0x00125803//ChaffGrenade,b
_L 0x20124790 0x00121803//StunGrenade,a
_L 0x201247DC 0x00125803//StunGrenade,b
_L 0x201ED588 0x3F000000//Grenade
_L 0x201ED754 0x3F000000//SmokeGrenade

```


対応ソフト

`ULJM-05193/ULJM-05227/ULJM-05284/UCAS-42087`

## 使い方
* あらかじめPPSSPPでチートコードを有効にしておく。

* ゲーム一覧の`METAL GEAR SOLID PORTABLE OPS`を右クリックし、`チート`を選択する。

* `チートファイルを編集する`を左クリックし、表示されたiniファイル`ULJM-05193.ini/ULJM-05227.ini/ULJM-05284.ini/UCAS-42087.ini`に上のコードをコピペして保存する。

* チート一覧にある`60 FPS v3 [Ingame only]`のボックスにチェックを入れてゲームを起動する。



## バグ
* ミサイルの弾速が上がり、回避が難しくなっている。
* カニンガムの復帰速度が上がっている。



# 基になったコード
このコードは私が0から作ったものではなく、US版コードのアドレスと値を日本版に対応したものに書き換えて移植したものです。

オリジナル作者はKabuto_Kun氏ですが、移植の許可は取っていません。

Kabuto_Kun氏からの削除連絡があった場合は削除します。


基になったコードのURL
https://forums.ppsspp.org/showthread.php?tid=4799&pid=103947#pid103947
