---
title: SDLC - Overview
date: 2020-05-06 00:00:00
tags:
categories:
	- 讀書心得
author: 嘉鼎智能
---

>SDLC 觀念發展起源於60年代，為實證過的學理，每個環節緊密相連，專注一項任務，目的就是要交付可以實用(上線)的產品。沒有過縝密計畫、思考就貿然開發，就會面臨到各式各樣的災難後果。無限的延宕完成日期，預算當然也跟著節節上升。或是產品上線後才發現一大堆當初沒有料想到的瑕疵等。
>
>![SDLC](/img/SDLC.png)

> 本文為 [嘉鼎智能](#關於我們) 內部讀書心得整理後分享，我們不定期會分享各種幫助擴增心智的學習文章，歡迎加入LINE社群參與討論。
>
> [點此加入擴增心智學習群](https://line.me/ti/g2/asPFU-0w4o9MIRSBdb4gtg)
> ![擴增心智學習群](/img/擴增心智學習群.jpg)

---
## 文章資訊
SDLC - Overview 
Software Development Life Cycle (SDLC) 

[文章連結](https://www.tutorialspoint.com/sdlc/sdlc_overview.htm)

---
## 目錄
- [文章資訊](#文章資訊)
- [目錄](#目錄)
- [前言](#前言)
- [文章討論](#文章討論)
	- [步驟一：規劃與需求規格分析](#步驟一)
	- [步驟二：定義需求規格（Defining Requirements）](#步驟二)
	- [步驟三：設計產品結構（Designing the Product Architecture）](#步驟三)
	- [步驟四：建構 / 開發產品](#步驟四)
	- [步驟五：產品測試](#步驟五)
	- [步驟六：部署和維護](#步驟六)
	- [SDLC-Models](#SDLC-Models)
		- [Waterfall-Model](#Waterfall-Model)
		- [Iterative-Model](#Iterative-Model)
		-  [Spiral-Model](#Spiral-Model)
- [其他連結](#其他連結)
- [關於我們](#關於我們)
---
## 前言

軟體開發生命週期 (Software Development Life Cycle -SDLC)，亦即一個有品質的軟體從設計、開發、測試直到完成的流程。

“我們應該算是運作一輪了，至少應該有接近、或即將要到部署（Delpoyment）的階段。由於我們有BTO的性質”，”目前的努力，是在於將原型（Prototyping）確立”

“如果用電腦硬體來類比的話，我們比較偏向戴爾（Dell）的BTO模式，故等於是每個客戶都要運作一個生命週期（Life Cycle）。”

---
## 文章討論

流程也包含了顧客的需求規格 (Planning、Defining)，產品開發 (Designing、Building)，以及最後的安裝測試，帶回家接上電源使用 (Testing 、Deployment)

軟體開發生命週期，也可以說是流程 (Process)，或是一種模式 (Model)，目的不外乎希望在一定的時間與預算內，循序漸進地完成成符合期望的產品。此一流程雖然主要用於軟體產業，但也可以廣泛地運用來開發服務產品，這些步驟( Life Cycle)背後是以科學方法 (Methodology) 逐步地建構、改進產品。

SDLC 觀念發展起源於60年代，為實證過的學理，每個環節緊密相連，專注一項任務，目的就是要交付可以實用(上線)的產品。沒有過縝密計畫、思考就貿然開發，就會面臨到各式各樣的災難後果。無限的延宕完成日期，預算當然也跟著節節上升。或是產品上線後才發現一大堆當初沒有料想到的瑕疵等。


### 步驟一
**規劃與需求規格分析**

軟體開發週期 Software Development Life Cycle (SDLC) 流程的第一步驟是 [規劃與需求規格分析] ，為最重要的階段，決定整個開發計畫成功。這階段決定最終產品要具備那些明確功能，一一列舉出來，日後驗收的階段依照這些規格逐一檢驗，是否達到當初所設定的要求。 這些需求規格通常是由顧客決定，或由資深的開發團隊成員、行銷業務部門，以及該領域專家參與討論，共同決定。規劃的階段同時有包含了品質確保，以及辨識此計畫中的可能風險，也必須一併整合列入上述需求規格細項當中，在測試中進行檢驗。

計劃和需求分析，由顧客、資深團隊成員、行銷業務、領域專家討論後，在經濟性，營運層次和技術領域進行產品可行性研究。 這些研究無非是想要確認成品不會未達到預期的效果、超出預算，甚至無法完成。


### 步驟二
**定義需求規格（Defining Requirements）**

需求規格分析的任務完成後，接著就是明確定義，做成書面資料 - [ 軟體需求規格] SRS，並且由顧客和市場分析師核可。此階段溝通確認非常重要。如果在制定需求規格項目是由某些高階管理部門來草擬，那麼就必須要經由使用單位確認。採取這一種模式無非是要加速產品完成時程，另外當產品過於龐大時，基層的使用者往往無法在工作之餘，額外挪出時間來規劃。至少設計此需求規格的小組，必須非常了解該軟體或是服務產品的細節流程，才不會製作出無法實用的產品，或是必須要經過第二回合的修改、測試。

### 步驟三
**設計產品結構（Designing  the Product Architecture）**

由階段2 所製作的  [ 軟體需求規格] SRS 是提供給產品架構設計師的參考，設計出最理想的產品架構。產品架構設計師通常會提出幾個不同的產品架構方案，並且記錄在 Design Document Spectfication (DDS) 的文件。 DDS，包含數種可能提議方案，同時也會各方人士來評估風險、產品穩健性、設計模塊化、預算和時間限制。DDS 中也明確定義了架構、模組，以及數據流 (Data flow) 的所有細節。

### 步驟四
**建構 / 開發產品**

此階段真正開始進行程式寫作 (或是服務產品開發)，如果設計文件規格(DDS) 詳細而有組織性完整，則可以輕鬆完成產品的開發工作。


### 步驟五
**產品測試**

測試階段類似於產品開發流程(或生命週期) 一樣的循環，經由產品缺失報告、列入追蹤、修正缺失、再次測試的步驟，直到產品品質達到 [ 軟體需求規格] Software Requirement Specification (SRS) 中所訂下的標準。測試包含軟體產品驗證和確認。

如何區別軟體產品驗證和確認?

Validation:
"Building the product right" checks that the specifications are correctly implemented by the system。 正確地建構產品是指產品是否依照規格需求

Verification:
"building the right product" refers back to the user's needs.  建構正確的產品是指符合顧客需求

### 步驟六
**部署和維護**

產品經過測試後，最後的階段就是上市。少數的情況下，可能會進行小規模市場試驗，以取得顧客回饋。如果需要大幅改變，可能是重新修改需求規格，執行新一輪的開發流程 (SDLC)

### SDLC-Models

#### Waterfall-Model

Waterfall Model 是很經典的模式，一階段完成後才啟動下一階段，不過這可以能需要規劃完善，沒有太多出錯的空間。而且一旦發現問題而中止，可能浪費許多資源

這種流程最大的優點是架構、需求明確，開發之前就已完成，工程師不需要花太多時間溝通就能順利完成工作。

Waterfall 模式也有其缺點，如果產品規劃不佳，或是需求規格不明確，需要一再溝通釐清，或是開發過程不斷地修改規格，工作效率自然降低。

![Waterfall.png](/img/Waterfall.png)

#### Iterative-Model 

Iterative Model 迭代(反覆、重複性) 的開發模式，不要求一次性地開發出完整的系統或是完美的產品，而是將開發視為一個逐步獲取用廣需求、完善產品的過程。符合先求有，再逐步改善的開發方式。適用於需求規格經常變更的產品。

![Iterative.png](/img/Iterative.png)

#### Spiral-Model
 	
Spiral (螺旋) 開發模式兼具迭代的特徵以及瀑布模型的系統化檢視。最大的特點在於加入風險分析，使軟體在無法解決重大風險時有機會停止，以減小損失。在每個循環會經過內部或顧客測試評估，確保產品符合需求的功能要件，適用於大型的昂貴的系統級軟體或產品服務。可以降低產品全盤失敗造成損失的可能性。

![Spiral](/img/Spiral.png)


---
## 其他連結

[讀書心得](/categories/讀書心得)

[產品共學群](https://line.me/ti/g2/Dj4AkbdDsY6o4D_CdDUB6Q?utm_source=invitation&utm_medium=link_copy&utm_campaign=default)

[所得科技討論群](https://line.me/ti/g2/asPFU-0w4o9MIRSBdb4gtg?utm_source=invitation&utm_medium=link_copy&utm_campaign=default)

[擴增心智學習群](https://line.me/ti/g2/asPFU-0w4o9MIRSBdb4gtg?utm_source=invitation&utm_medium=link_copy&utm_campaign=default)


---
## 關於我們
嘉鼎智能(股)公司為美商嘉鼎智能團隊（Magnific Intelligence Collective, LLC ），於台灣設立之服務據點，成立於1999年，以「嘉惠人群、穩如鐘鼎」的信念，追求所得科技的進化。 

為幫助更多人與團隊合作，共享人心智能，嘉鼎智能推出「ACIS擴增集智系統」，協助大家學習如何透過有系統的運作：

 收集成果->調配擴增->驗收更新

三階段，獲取實質所得，持續擴增未來所需的動力能量。 

[👉 了解更多](https://act.magnific.biz)

