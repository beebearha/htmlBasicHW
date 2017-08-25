

# HTML作業1 連結頁面、圖片與CSS

---

## 作業練習檔案

請下載以下連結的檔案並作練習

https://www.dropbox.com/s/sfkxrwwghtunzhp/HTML_HW1.zip?dl=0

## 作業敘述

練習檔案中的部分頁面連結、圖片與CSS皆有**路徑錯誤**而失連的現象，請修改練習檔案並更正連結，並使圖片與CSS皆能正常顯示。

1. 檢查圖片`<img>`的src屬性是否路徑錯誤並修復
2. 檢查CSS`<link>`的href屬性是否路徑錯誤並修復
3. 檢查頁面連結`<a></a>`的href屬性是否路徑錯誤並修復

## 提示
1. 使用Google Chrome開啟網頁按`右鍵 => 檢查 =>點選console`若是見到代號404錯誤即是代表這個檔案路徑錯誤，請修正正確的檔案路徑。 
![路徑錯誤](http://i.imgur.com/XP1oiHX.png)
若是使用Adobe Brackets預覽一開始檢查會有個favicon.ico的錯誤，這個錯誤訊息可以先忽略。

2. CSS檔案用link標籤的href屬性做連結 
```cssmixed=
<link rel="stylesheet" href="css檔案路徑">
```

3. 圖片檔案用img標籤的src屬性做連結 
```cssmixed=
<img src="圖片連結" alt="替代文字">
```

4. 頁面連結用a標籤的href屬性做連結 
```cssmixed=
<a href="頁面連結">連結顯示文字</a>
```

