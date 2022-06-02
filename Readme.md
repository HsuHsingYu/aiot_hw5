# AIOT組別3's New Homework #5 (in HsuHsingYu/aiot_hw5)

## Lecture 14: IoT Flask Web (github, vs code)

## Step 1 : Development Environment Setup in aiot_hw5 (前置作業)
### 1. Please install vs code, register github, install git for windows
![](picture/pic1.png) 
* 而vscode中需要安裝好此次作業所需的python相關模組，另外也需要去python官網下載相關的內容
![](picture/python.png)

![](picture/官網python.png)
### 2. 操作 check point 1
*  我們需要建立一個資料夾，點擊下圖紅框區域輸入”cmd”來開啟終端機
![](picture/pic2.png)
在裡面輸入 git clone https://github.com/huanchen1107/aiot0524.git
將老師上課所提供的gitHub內容抓下來
![](picture/pic3.png)

![](picture/pic4.png)
* 然後再開一個資料夾，將0524中的Readme.MD抓過來，此為接下來主要作業的地方
![](picture/pic5.png)
* 建立在github中的repository
  * 將剛剛建立好的資料夾利用vscode開啟
![](picture/pic6.png)
* 點擊紅框，並選擇發布到gitHub
![](picture/pic7.png)
* 選擇public的
![](picture/pic8.png)
* 發布成功
![](picture/pic9.png)

### 3. 操作 check point 2
C:> 設定下面 (不設定 branch default ='main')
   * C:> git config --global user.name "HsuHsingYu"
   * C:> git config --global user.email s108056052@smail.nchu.edu.tw

![](picture/check_point_2.png)  

### STEP2 simple flask web
1. 使用vscode開啟aiot0524的資料夾，並簽出至step2  
![](picture/pic10.png)

![](picture/pic11.png)  
完成後可以看到aiot資料夾的變化  

![](picture/pic12.png)  
2. 在aiot_hw5下面建立step2的分支(p.s step1分支內容為將readme改為我們的資料後)  

![](picture/pic13.png)  
![](picture/pic14.png)  
![](picture/pic15.png)可以由左下方看到目前已為step2分支  
3. 將aiot0524目前的內容抓到aiot_hw5的資料夾中，並發布step2分支  
![](picture/pic16.png)  
4. 將內容改完我們的資訊後重新推上去  
![](picture/pic17.png)  
完成內容請見step2
### STEP3 app.py NoAI.html (有highchart)
在這個步驟中我們需要加入indexNoAI.html檔，並修改app.py中的內容  
1. 註冊網址(“/noAI”)，進入http://127.0.0.1:5000/noAI 後，會渲染到indexNoAI.html這個template上  
![](picture/pic18.png)  
2. 加入indexNoAI.html  

3. indexNoAI.html有用到/setRandom這個網址  

4. 在app.py裡註冊”/setRandom”和定義getData function(導入到/setRandom之後會做的事)  

5. 完成後執行app.py程式，在網址後面加上/noAI即可看到此畫面  

* 完成內容請見step3
### STEP4 Logistic regression (有db互動)
在此步驟中我們會將logistic regression的model應用到作業中，亦會把程式與db互動的部分完成  
1. 註冊網址(“/”)，進入http://127.0.0.1:5000 後，會渲染到indexAI.html這個template上  
2. 加入indexAI.html檔
3. indexAI.html裡有兩個按鈕，setRandom和callAI，按下setRandom後會到入到”/noAI”，按下callAI後會導入到”/”  
4. indexAI.html有用到/getPredict這個網址  
5. 在app.py裡註冊”/getPredict”  
6. 匯入database的相關資訊  

* 完成內容請見step4
### STEP5 complete
* 完成內容請見step5



