# Kiddochan

[README](/README.md)

Kiddochan 是 [Hexo](http://hexo.io) 的一款簡單, 彈性且適合所有螢幕尺寸的主題樣式，是基於[Jacman](https://github.com/wuchong/jacman)修改而来。 最底部有一些樣式個人化設定的範例。

[更多關於Kiddochan](http://blog.hsihohuang.info/tags/Kiddochan/) 

[主題預覽](http://blog.hsihohuang.info) 


##截圖
### PC
![kiddochan-pc](screenshots/kiddochan_pc.png)

### Pad
<img src="screenshots/kiddochan_pad.png" width="650">

### Phone
<img src="screenshots/kiddochan_phone1.png" width="400">
<img src="screenshots/kiddochan_phone2.png" width="400">


##安裝教學
###安裝
```
$ git clone https://github.com/hsihohuang/kiddochan.git themes/kiddochan
```
**Kiddochan 需要 Hexo 2.7 及以上版本** 
###啟用
修改部落格根目錄底下的設定文件 `_config.yml`，把`theme`的值修改成 `kiddochan`.
###更新
```
cd themes/kiddochan
git pull origin master
```
**請先備份您主題目錄下的 `_config.yml` 文件後再升级。**

##設定

修改  `/themes/kiddochan/_config.yml` 中的設定。


##樣式個人化設定之範例
### 範例 1
theme: '#403D3D'       
background: '#DBDBDB'  
footer: '#403D3D' <br>
Font-style: cool
![example1](screenshots/example1.png)

### 範例 2
theme: '#D07272'       
background: '#FCC'  
footer: '#4A4848' <br>
Font-style: cute
![example2](screenshots/example2.png)

### 範例 3
theme: '#279BAB'       
background: '#15464C'  
footer: '#15464C' <br>
Font-style: cool
![example3](screenshots/example3.png)

### 範例 4
theme: '#ECA70C'       
background: '#EEE'  
footer: '#7B5705' <br>
Font-style: cute
![example4](screenshots/example4.png)

### 範例 5
theme: '#2D9853'       
background: '#D3DCDA'  
footer: '#111F1A' <br>
Font-style: custom<br>
**注意：預設的custom字型是"ReenieBeanie"，你可以換成你要的字型** <br>
**更換方法: 你必須要放把字體的檔案(共四種檔.woff2, .woff, .ttf, .eot, 你可以用[這個工具](http://www.fontsquirrel.com/tools/webfont-generator)去產生) 放入`kiddochan/source/font`資料夾中，**
**然後把`/kiddochan/source/css/_base`中的`variable.styl`裡面的`font-custom-family`和`font-custom-filename`改成你自己的字體檔名.**
![example5](screenshots/example5.png)

##Google 自訂搜尋頁面
##### 範例(搜尋: quicksort)
![googleCustomSearch](screenshots/google_custom_search.png)

##License
[MIT](/LICENSE)
