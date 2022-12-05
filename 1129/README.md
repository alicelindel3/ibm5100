## 実行順序
FROM  
ON / JOIN  
WHERE  
GROUP BY  
COUNT / SUM / AVG / MAX / MIN  
HAVING   
SELECT / DISTINCT  
ORDER BY  
LIMIT

## 4つの構文
### 取得
SELECT カラムA,カラムB  
FROM テーブル名;
### 挿入
INSERT INTO テーブル名(カラム名A,カラムB...)  
VALUES (値1,値2...);
### 更新
UPDATE テーブル名  
SET カラムA=値1,カラムB=値2  
WHERE 条件;
### 削除
DELETE FROM テーブル名  
WHERE 条件;
