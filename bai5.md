###5. Lấy 5 blog từ blog thứ 10
```
SELECT DISTINCT title FROM blog
WHERE is_active = 1 
ORDER BY created_at ASC
LIMIT 10, 5;
; 
```