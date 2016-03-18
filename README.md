# PttAutoPush
PTT自動推文 推文機器人(Python) For Linux and Windows
* [Demo Video](https://www.youtube.com/watch?v=vyLUPSfCprc) - Linux 
* [Demo Video](https://youtu.be/eRA4m2rRIDw) - Windows

## 特色
* 推文機器人
* 持續至特定看板對最新文章推文

## 使用方法
請將下列程式碼修改為自己的PTT ID 以及 Password
```
user = 'Your PTT ID'
password = 'Your PTT Password'
```
```
$ python PttAutoPush.py [版名] [內容] [標題數] [推文tag]

```
說明:

[版名] : 不分大小寫，EX. gossiping

[內容] : 推文內容

[標題數] : 對最新的[標題數]筆文章推文，不包含至底文

[推文tag] : 1 = 推文 or 2 = 噓文 or 3 = 註解

## 執行範例 
``` 
$ python PttAutoPush.py gossiping 別再發文了，趕快出門運動吧  10 1
```
該範例為在PTT gossiping(八卦)板  自動對最新的10篇文章推文（不包含至底文）

推文的內容為 別再發文了，趕快出門運動吧 (推文內容不要有空白或特殊字元)

程式永遠不會停止

除非使用 任何軟體登入PTT，使程式執行錯誤 或 輸入Ctrl + C '強制終止程式

## 執行過程
![alt tag](http://i.imgur.com/sRMIyag.jpg)
輸出 (使用pcman觀看)
![alt tag](http://i.imgur.com/hgKup56.jpg)

##執行環境
Ubuntu 12.04
Python 2.7.3

## License
MIT license

