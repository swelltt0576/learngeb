# 測試流程整合

簡易的 Geb 測試程式只要用 Groovy Script 方式撰寫，但是對一個完整的 Web 專案測試而言，上百甚至上千行的 Script 程式碼，將會讓測試程式變得難以維護。在實務上我們必須搭配自動化專案建置工具與測試框架，讓 Geb 的測試程式也能為專案建置的一部份。

在實務經驗上可行的開發工具組合建議是：

* 搭配 `Gradle` 或 `Maven` 專案自動化建置
* 使用 `Geb Page Objects` 定義每個需要被測試的頁面
* 利用 `Spock` 或 `JUnit` 撰寫單元測試案例


