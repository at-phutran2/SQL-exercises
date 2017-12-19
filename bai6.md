###6. Set is_active = 0 của user có id = 3
```
SELECT is_active, full_name FROM user
where id = 3;
UPDATE user
SET is_active = 0
WHERE id = 3
; 
```