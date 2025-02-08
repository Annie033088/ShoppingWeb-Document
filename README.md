# ShoppingWeb 應用程式 #

## Warning ##

此專案為個人練習用的專案, 專案並不會持續更新

## 目錄 ##

1. 簡介
2. 還原專案
3. 功能介紹

## 簡介 ##

- 此專案的目的是開發一個網頁版購物網站的後台管理應用程式，專注於提供網站管理功能，讓管理員能夠方便地管理產品、訂單、用戶等資訊。
- 此專案採用 ASP.NET Framework MVC 技術結合 SQL Server 來開發。

## 還原專案 ##

1. 載入資料庫 [教學](https://github.com/Annie033088/ShoppingWeb-DB/blob/Main/README.md)
2. 載入 ShoppingWeb 主程式 [教學](https://github.com/Annie033088/ShoppingWeb-CMS/blob/Main/README.md)
3. 執行 Pashamao 專案的應用程式

## 功能介紹 ##

1. 登入使用者帳密
![Initialize Image](https://github.com/Annie033088/ShoppingWeb-Document/blob/Main/img/Login/Guide1.png)
2. 導覽頁的後台使用者管理底下包含兩個分頁，分別是使用者管理及角色管理
    1. 在使用者管理底下，使用者可以新增使用者、刪除使用者、修改使用者角色以及狀態 (啟用/禁用) ，每個使用者對應一個角色
    2. 在角色管理底下，使用者可以修改個個角色的權限，而一個角色對應多個權限
    ![Initialize Image](https://github.com/Annie033088/ShoppingWeb-Document/blob/Main/img/User/Guide1.png)
3. 導覽頁的會員管理底下包含三個分頁，分別是會員管理、會員地址管理以及會員點數管理
    1. 在會員管理底下，使用者可以修改會員狀態 (啟用/禁用)
    2. 在會員地址管理底下，使用者可以查看所有會員的地址
    3. 在會員點數管理底下，使用者可以重製所有會員的點數 (補充：此舉動很危險不建議開發權限給予其他管理者使用)
    ![Initialize Image](https://github.com/Annie033088/ShoppingWeb-Document/blob/Main/img/Member/Guide1.png)
4. 導覽頁的商品底下包含一個分頁，商品管理
    1. 在商品管理底下，使用者可以新增、查詢、刪除、修改商品
    ![Initialize Image](https://github.com/Annie033088/ShoppingWeb-Document/blob/Main/img/Product/Guide1.png)
5. 導覽頁的訂單底下包含兩個分頁，分別是訂單管理分頁以及運輸管理分頁
    1. 在訂單管理底下，使用者可以查詢、修改及刪除訂單
    2. 再運費管理底下，使用者可以修改運費金額以及對應的免運標準 (免運金額)
    ![Initialize Image](https://github.com/Annie033088/ShoppingWeb-Document/blob/Main/img/Order/Guide1.png)
6. 頁面右上角可以進行登出
