# 2020_OO

## 班級:資管三甲

## 組長:C107118107郭弘逸

### 小組成員：C107118107郭弘逸 C107118118邱宏嘉 C107135126劉彥圻
```
工作分配:  郭弘逸:製作甘特圖、PERT圖、
              邱宏嘉:主題討論、報告
              劉彥圻:主題討論、報告
```
 ***
# 主題:智慧手錶應用


## 內容:新世代的智慧手表功能介紹與整合




 
 
#### 甘特圖:

![甘特](甘特.jpg "甘特")
```
gantt
    title 智慧手錶
    dateFormat  YYYY-MM-DD
    section 日程
    主題討論           :a1, 2020-10-13, 7d
     甘特圖            :after a2, 2020-10-20,5d
     PERT/CRM圖       :afte 2020-10-20,5d
     收集資料          :a2 ,2020-10-23,14d
     內容撰寫          :a3 ,2020-11-01,31d
     內容檢查          :a4,2020-11-16,19d
     報告              :a5,2020-12-06,10d       
     

```
 




#### PERT圖:


![PERT圖](PERT圖.PNG "PERT圖")

```graphviz
digraph {
	node[shape=record];
	rankdir="LR";
    no1 [label = " 主題制定| 編號:1 | 開始:第1天 | 結束:第10天 | 需時:10天"]
    no2 [label = "規劃工作 | 編號:2 | 開始:第11天 | 結束:15 | 需時:4天"]
    no1->no2
    no3 [label = "系統規劃 | 編號:3 | 開始:第16天 | 結束:第45天 | 需時:25天"]
    no4 [label = "資源收集 | 編號:4 | 開始:第16天 | 結束:第65天 | 需時:14天"]
    {rank=same;no3 no4}
    no2->no3
    no2->no4
    no5 [label = "最後整合 | 編號:5 | 開始:第66天 | 結束:第95天 | 需時:30天"]
    no3->no5
    no4->no5
}
```
 *** 
 功能性需求: 
 * 庫存查詢
 * 客戶購買資料
 * 購買作業
 
 非功能信需求:
 * 反應時間:1秒內
 * 使用度:高
 * 可靠度:極高


