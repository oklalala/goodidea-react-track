# React 學習檔案

## Q2 環境建立
Q2 在建立 react 的環境，顯示基本的 Hello world
如何下載專案

1. 在終端機中輸入
`git clone git@github.com:oklalala/goodidea-react-track.git YourProject`

2. 進入專案
`cd YourProject`

3. `npm install`

4. 啟動瀏覽器
`npm run serve`
並在瀏覽器上輸入 http://localhost:3000

### 使用 CRA (create-react-app)
[操作細節](https://hackmd.io/zFuNGVf-S_yJ3-Q8yAx_iQ)

### 不使用 CRA，內建 webpack babel HMR
[操作細節](https://hackmd.io/4k06WN4-TLOHZXv_IaPraw?view)

## Q3 引入靜態頁面
Q3 情境為取得某個靜態頁面 ( 購物網站 ) 後，將頁面嵌入 React。
了解 html, css, icon, image 引入的方案。

在引入專案之後，這個練習放在 Q3_shopping 的分支。

1. 創立並進入本地分支
`git checkout -b Q3_shopping`

2. 拉下遠端分支
`git pull origin Q3_shopping`

3. 合併衝突，這時候會進入 git merge 的頁面
![](https://i.imgur.com/bbf0UbM.png)
`:x` 儲存並離開

4. 更新環境
`npm install`

5. 啟動瀏覽器
`npm run serve`
並在瀏覽器上輸入 http://localhost:3000

[操作細節](https://hackmd.io/1aihGv4-QMycTTmyuzl0pA?edit)
