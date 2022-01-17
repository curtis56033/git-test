* 安裝&設定git、fork  git像是快照
* 建立資料夾後到fork初始化(file>Init new Repository)
* 如果刪掉資料夾裡的.git 則會變成一般資料夾且fork會一直loading
(這時候就要再做一次第二點)、file的remove只是清除fork而已
新增檔案然後commit
(在Unstaged綠色新增、黃色修改檔案內容、紅色刪除；
 在Staged紫色重新命名(或是先刪除再新增一樣的也會變重新命名))
- 在Commit右鍵revert會做反向的事情來回復到當時的Commit且新增一個反向Commit
- 在Commit右鍵reset優先選上面兩個 最下面的會回復後清除(discard)
![圖片替代文字位置](https://i.imgur.com/PmGtlt5.png)
- 上面圖(點)
- 到C:\Users\user\.ssh 用notepay++開id_rsa.pub，複製裡面的key

![](https://i.imgur.com/ttX4MGo.png)
- 到SSH and GPG keys選SSH key 貼上內容 新增(回家用也要做這件事)
- Fetch(測試SSH)& push 就完成在github的備份
- pull (=fetch + commit右鍵checkout) & push是跟github上同步
- 從github的備份到PC： 
![](https://i.imgur.com/SCaJ9b0.png)
- 複製SSH code，到fork file > clone
- 如果要回到前幾步驟Push，要用force(盡量不要，要做的話要與團隊溝通後才執行)
---
https://hackmd.io/
類似notion
# h1
## h2
### h3
#### h4
##### h5
###### h6
---
~~Hello World~~
*Hello World*
**Hello World**
>Hello World
Hello `單字變化` 
```
多行字變化
Hello World
Hello World
Hello World
```
```python=
def hello():
    print('Hello World')
```
1. One
2. Two
3. Three

| Column 1 | Column 2 | Column 3 |Column 4 |
| -------- | :-------- | :--------: |--------: |
| Text     | 靠左對齊     | 置中     | 靠右對齊     |
|e|d|e|d|

<https://google.com>
[Google](https://google.com)

