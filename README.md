# 8085 CPUボード

EMUZ80-57Qに組み合わせて8085を動作させるためのCPUボードです。  

SBC8080やMYCPU80でCP/M 2.2を動作させるための  
ファームウエア開発用テスト基板として試作しました。  

![F](https://github.com/Gazelle8087/8085-CPU-BOARD/blob/main/CPU8085_F.jpg)
![B](https://github.com/Gazelle8087/8085-CPU-BOARD/blob/main/CPU8085_B.jpg)

##設計データ
8085_CPU_1109.zip にてJLCPCB発注実績ありです。  

##特長

ステータスLEDによりCPU動作状況把握可能  

コントロールバスを3線制御(IO/M, RD, WR)と4線制御(IORD, IOWR, MEMRD, MEMWR)に  
ジャンパ設定でいずれにも設定可能  

クロック源として、水晶発振子、セラロック、水晶発振器、外部入力が選択可能

SOD, SIDをコネクタに引き出し済

## EMUZ80-57Qとの組み合わせ

![stacked](https://github.com/Gazelle8087/8085-CPU-BOARD/blob/main/DSC_0028.JPG)  

この組み合わせにてCP/M 2.2が動作します。
ファームウエアは以下リポジトリご参照ください。
https://github.com/Gazelle8087/SBC8080-CPM

