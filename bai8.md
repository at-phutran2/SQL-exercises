###8. Lấy 3 blog bất kỳ (random)
```
SELECT title, content FROM blog
ORDER BY RAND()
LIMIT 3
```