# local_judgegirl備份

## 使用方法

1. 點選綠色code按鈕，選下面的下載zip檔
2. run一次init.exe
3. 打開problems/domain/0.html
4. 後續使用照著正常judgegirl就可以了，但只有備份主題、題目、測資頁面，有些頁面沒備份

## 與原版差異和部分註解

- 比較醜
- 有些數學式的格式會跑掉
- 不能上傳程式碼run，只能看題目和測資
- crawler.py和function.py是當初爬蟲的程式碼，雖然爬得不好看(有部分寫死的路徑)但還是放上來了

## 實作過程

1. 利用爬蟲把每個想要下載的頁面爬過存成html
   (judgegirl已經停止外網連線了，所以這步驟只能直接載我這載好的)
2. 把html中的所有連結改成local檔案的位置
   (透過init.exe執行，不然連結會是我電腦中的檔案位置)
