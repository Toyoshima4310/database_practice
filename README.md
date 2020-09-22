# データベースの学習をまとめます。

```
SELECT class_id, COUNT(*), AVG(result), MAX(result), MIN(result)  
FROM grade GROUP BY class_id;
```
GROUP BY class_idでclass_idが等しい物で分ける。  
SELECT ~ FROM = で、=から~を表示させるという意味だから、  
クラスごとの人数(COUNT(*))、クラスごとの平均(AVG(result))、  
クラスごとの最高得点(MAX(result))、クラスごとの最低得点(MIN(result))を表示できる
