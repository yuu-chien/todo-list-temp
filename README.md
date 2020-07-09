# hex-JSLC-w1
六角 JS 作品實戰班｜第一週．ToDo List

<br>

## Info
使用關注點分離的觀念完成此作業。  
提交等級：LV3，不使用課程版型完成 Todo List 功能

### User Story
* 用戶可以新增 Todo，新增後移除 input 的項目  
* 用戶可以刪除、完成 Todo  
* 用戶可以一鍵刪除所有任務  

<br>

## 助教 Feedback
#### 第一次提交
作業製作的很好哦  
助教這邊也給你一些修改建議唷~  
* 新增代辦之後可以試著將 input 欄位清空。
* 完成代辦 doneTask 與刪除 deleTask 的行為是屬於資料操作，因此會建議移出 render。
* 雙等號可以試著改三等號唷。
* 版型滿簡潔不錯的唷~
* localStorage 的部分可以參考一下其他同學唷~

#### 第二次提交
助教這邊給你幾個方向思考哦  
* 可以試著將 let todoData = []; 改成 let todoData = localStorage.getItem('task'); || [];
* 另一個方向可以試著參考有製作 localStorage 的同學作業唷
