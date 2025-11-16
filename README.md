# AuthDemo

一個簡單的 Node.js / Express 登入註冊系統，使用 MongoDB 儲存使用者資料，密碼經過 bcrypt hash 保護，並使用 session 做登入狀態管理。

---

## Features

- 使用者可以註冊、登入、登出
- 密碼自動 hash ，不存明文
- 受保護頁面：登入才能訪問 /secret、/topsecret
- session 管理使用者登入狀態
- Middleware 保護受限頁面
- 安全登出，清除 session

---

## Tech

| 類別 | 技術 |
|------|------|
| Backend | Node.js / Express |
| Database | MongoDB / Mongoose |
| Auth | bcrypt / express-session |
| View Engine | EJS |
---

##  

- 學習 Node.js / Express 後端開發
- 熟悉使用 Mongoose 管理資料庫
- 練習 session 與 middleware 的使用
- 體驗安全密碼存取與 hash

---

