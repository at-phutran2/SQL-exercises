###3. Xoá và sửa 1 dòng dữ liệu trong bất kỳ table nào

```xoa(neu k xoa duoc dung lenh SET SQL_SAFE_UPDATES = 0; de tat che do safe mode)
	DELETE FROM user 
	WHERE full_name = 'tranvietphu';
```

```update
UPDATE user
SET full_name = 'tranvietphu23'
WHERE full_name = 'tranvietphu1';
```