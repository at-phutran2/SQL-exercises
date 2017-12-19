###4. Select 10 blog mới nhất đã active
```
SELECT DISTINCT title FROM blog
WHERE is_active = 1 
ORDER BY created_at ASC
LIMIT 10;
; 
```