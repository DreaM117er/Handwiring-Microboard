# Handwiring Microboard 手拉線拓展板

![](pic/1-1.png)

![Front side](pic/FS.png)
![Back side](pic/BS.png)

## 詳細說明

Pro Micro、Elite-C是大部分開源分離式鍵盤使用的MCU，左右為12+12的針腳數，特別是Elite-C在Pro Micro的腳位上多增加了5個可用的針腳數，增加鍵盤的可能性。礙於開發板本身是不帶螺絲孔位，因此設計了這個將所有Pro Micro可用的針腳及Elite-C多拓展的5個針腳拉出來統合在一起，更方便製作鍵盤。

- 支援正反面安裝，MCU需對照腳位焊接。
- 支援2個不同方向的TRRS座安裝。
- 4個M2螺絲孔位。

## 大小規格

![](pic/1-2.png)
![](pic/1-3.png)
![](pic/1-4.png)
![](pic/1-5.png)

- M2螺絲孔大小: `ø2.2 mm.`
- 拓展板大小: `34.020 x 46.992 mm`
- M2螺絲孔間距: `25.697 mm`, `38.945 mm`

## 板載使用的針腳

- 重複設計了大約4次，前2次計算針腳的數量錯誤；
- 第3次在實際安裝的時候發現會有一些技術上的安裝問題；
- 最後一次設計將18個可編程的Pro Micro針腳做對稱處理，不用再擔心會有安裝上的技術問題。

### Elite-C:

![Elite-C](pic/2-2.png)

使用Elite-C腳位的MCU，板子上所有的針腳位都可以使用，請依照拓展板上的針腳代號進行編程。

### Pro Micro:

如果使用Pro Micro進行安裝，拓展板上最下方的5個拓展針腳是無法使用的，請特別留意。

## How to Use Handwiring Microboard