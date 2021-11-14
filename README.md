# 20211111 作業：終極密碼 (guessing.cpp)

在程式裡預先定義好一個介於 1~100 的一個整數做為題目，讓使用者重複猜測直到猜出正確解答。

若使用者猜的數字不是正解，就在畫面上更新數字的猜測範圍。

例如題目為 75，一開始使用者從 1~100 猜測 50，則程式在畫面上呈現新的一輪猜測範圍是 50~100。

接著，如果使用者猜測 80，則程式在畫面上呈現新的一輪猜測範圍是 50~80，依此類推，直到使用者正確猜出數字為 75。

進階一點的同學可以試著自由加上額外的內容，以下是一些舉例：

* 檢查使用者輸入的範圍是不是合法範圍，不是的話請他重新輸入
* 每次的題目是隨機的數字（需要有 `rand` 的先備知識）
* 兩個使用者輪流猜測，看是誰猜到就是勝利者
* 改由電腦猜測，或是電腦跟使用者互猜


作業繳交連結：https://github.com/nanshan-high-school/20211111-homework-basic

---

Pull Request 前請確認以下事項：

* 已閱讀 [作業繳交方式](https://hackmd.io/@nssh/nscsc/%2F%40nssh%2Fsummit-homework)
* 在下方附上 Repl 連結
* 檔案放在自己學號的目錄下
* 標題以「班級座號、學號、姓名」作為開頭
* 其他說明事項可以在下面補充
