---
layout: doc
sidebar: true
---

# Processpage 流程頁面
> 根據各服務需求，制定一致的操作流程與視覺規範，以利顧客在進行服務申請過程可以更加流暢與快速。<br>
> 本區簡單介紹現行流程頁中會使用的固定格式，但如果個別元件需要確認，請參考uikit各元件說明


## 入口頁
```
照需求選擇一/兩欄式入口頁面使用。
```
<p>一欄式</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-OneColumn.png" style="max-width:100%;">
</div>
<p>兩欄式</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-TwoColumn.png" style="max-width:100%;">
</div>

## 身份驗證頁
```
依照提供的驗證渠道來決定選擇樣式。
單一驗證頁面當中，依照填寫欄位來選擇。
＊注意此處如選擇為無icon的資料填寫形式，格式應為單欄式，且標題與輸入格為一列。
```
<p>單一驗證</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-InputVerification.png" style="max-width:100%;">
</div>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-IconVerification.png" style="max-width:100%;">
</div>
<p>複合驗證</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-MultipleVerification.png" style="max-width:100%;">
</div>

## 步驟頁
```
依照需要的步驟數量制定。
在使用時會分為已完成步驟、進行中步驟、尚未進行步驟，對應不同狀態。
＊注意步驟數量最多為六個。
```
<p>步驟圖示意</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-step.png" style="max-width:100%;">
</div>

## 資料頁
<p>資料類別選擇</p>

```
固定格式，在需要選擇辦理業務類別時使用。
```
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-CheckCategory.png" style="max-width:100%;">
</div>
<p>資料上傳</p>

```
固定格式，在需要上傳審核文件時使用，可依照需求點擊新增上傳文件欄位。
```
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-FileUpload.png" style="max-width:100%;">
</div>
<p>大量資料</p>

```
當使用者需要填寫大量資料，會採用左右雙排的資料填寫形式。
且資料表頭與內容為上下排列，以此放入更多的填寫欄位，避免頁面過長、過多。
```
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-multipleInput.png" style="max-width:100%;">
</div>
<p>少量資料</p>

```
當資料量較少時，可以選擇使用單行形式進行填寫。
建議當資料呈現單行式，可以在單一頁面中呈現時使用；
如單行呈現會超出單頁，則建議使用雙行排列，減少流程頁數。
```
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-lessInput.png" style="max-width:100%;">
</div>

## 資料確認頁
```
依照是否需要另外下載為準，如果需要提供下載檔案，會提供製作好的pdf形式，線上確認則依資料填寫頁格式。
```
<p>線上確認</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-DataCheck.png" style="max-width:100%;">
</div>
<p>下載確認</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-DataPDF.png" style="max-width:100%;">
</div>

## 服務申請
```
根據申請成功、失敗給予不同回饋，前方icon則配合不同申請類別。
目前使用類別有以下種類，詳細資訊可前往元件進行查看。
```
<img src="./img/layout/processpage/guildline-layout-processpage-IconType.png" style="max-width:100%;">

<p>申請成功</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-complete.png" style="max-width:100%;">
</div>
<p>申請失敗</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-fail.png" style="max-width:100%;">
</div>

## 彈跳視窗
```
根據跳窗顯示文字與情況，決定是否需要有Icon警示。
```

<p>標題版</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-PopupNormal.png" style="max-width:100%;">
</div>
<p>Icon版</p>
<div class="container mx-auto my-8 px-4">
<img src="./img/layout/processpage/guildline-layout-processpage-PopupIcon.png" style="max-width:100%;">
</div>

<script setup>
import Button from "../components/Button.vue";
</script>