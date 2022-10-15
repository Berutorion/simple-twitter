
# ALPHA CAMP  Simple-Twitter
此為ALPHA CAMP 學期三多人協作畢業專案 Simple-Twitter，以 Twitter 產品為原形，按其內容及功能所開發之簡易版。
專案採前後分離的模式開發，小組成員共四人，兩位前端專修，兩位後端專修。

**後端Github Repository網址：** [twitter-api-2020](https://github.com/Berutorion/twitter-api-2020)


---
## 🔎目錄

- [ALPHA CAMP  Simple-Twitter](#ALPHA-CAMP-Simple-Twitter)
  - [目錄](#目錄)
  - [專案使用說明](#專案使用說明)
  - [專案功能介紹](#專案功能介紹)
  - [專案畫面預覽](#專案畫面預覽)
  - [專案檔案結構說明](#專案檔案結構說明)
  - [專案採用技術](#專案採用技術)
---



## 💡專案使用說明

1. 使用git複製本專案
```
git clone https://github.com/yoyo030/simple-twitter.git
```

2. 下載完畢後，進到專案資料夾
```
cd simple-twitter
```

3. 操作以下指令安裝所需的套件
```
npm install
```

4. 在專案根目錄執行以下指令，在本地啟動專案
```
npm run serve
```
5. 網頁成功連接後可使用`Local`或者`Network`的網址資訊在瀏覽器中開啟


6. 開發完成後，於專案根目錄下使用此指令打包專案用於佈署
```
npm run build
```

7. 另可使用以下指令對專案程式碼進行程式碼風格檢查
```
npm run lint
```

### 提供測試帳號

* 一般使用者
    * account: `user1` / password: `12345678`
    * account: `user2` / password: `12345678`
    * account: `user3` / password: `12345678`
    * account: `user4` / password: `12345678`
    * account: `user5` / password: `12345678`
* 後臺管理員
    * account: `root` / password: `12345678`

👉 專案由此進入[線上入口]( https://yoyo030.github.io/a/#/login)

---

## ✅專案功能介紹

**前台登入 :**
- 註冊/登入/登出功能
- 推文留言功能
    - 瀏覽所有的推文
    - 回覆別人的推文
- 使用者互動
    - 對別人的推文按Like/Unlike
    - 追蹤/取消追蹤其他使用者 
- 用戶功能
    - 使用者能編輯自己的account、name、email和password
    - 編輯自己的名稱、自我介紹、個人頭像與封面
    
**後台登入 :**
- 瀏覽及編輯功能
    - 管理者可以瀏覽站內所有的使用者清單
    - 管理者可以瀏覽全站的Tweet清單

---

## 💻專案畫面預覽



**使用者登入頁**
![使用者登入頁](https://imgur.com/fOhOrbt.jpg)

**使用者註冊頁**
![使用者註冊頁](https://imgur.com/vNECnro.jpg)

**網站首頁**
![網站首頁](https://imgur.com/YwG1SPV.jpg)

**個人資料頁**
![個人資料頁](https://imgur.com/W4hyMPi.jpg)

**個人資料設定頁**
![個人資料設定頁](https://imgur.com/nWPe0Ja.jpg)

**後台登入頁**
![後台登入頁](https://imgur.com/e1AHggd.jpg)


---



## 📁專案目錄結構說明

```
./src               - 程式碼根目錄
./src/apis          - 與後端串接API
./src/assets        - 網頁樣式/styles與圖片/images
./src/router        - 路由設定
./src/views         - 網頁主頁面
./src/componenets   - 網頁子元件頁面
./src/store         - Vuex設定
./src/utils         - 共用Function
```


---


## 🛠專案採用技術

- [Vue.js](https://vuejs.org/)
- [Vue Router](https://router.vuejs.org/)
- [Vuex](https://vuex.vuejs.org/)
- [npm](https://www.npmjs.com/)
- [axios](https://github.com/axios/axios)
- [SASS/SCSS](https://sass-lang.com/)
- [Sweetalert2](https://sweetalert2.github.io/)



---