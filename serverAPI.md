# ServerBankSoal

### Terdiri dari 4 lvl
1. admin
2. validator soal
3. user
4. ban

### perm
1. admin
	1. bisa menambahkan data katagori seperti bahasa,mapel,lvltoken,permuser,grupuser,permgrup **(done)**
	2. bisa menghapus data katagori seperti bahasa,mapel,lvltoken,permuser,grupuser,permgrup
	3. bisa update data katagori seperti bahasa,mapel,lvltoken,permuser,grupuser,permgrup
	4. bisa memvalidasi soal **(done)**
	5. menghapus soal **(done)**
	6. mengedit soal
	7. membuat soal **(done)**
	8. membuat soalset **(done)**
	9. menghapus soalset **(done)**
	10. 
2. validator soal
	1. bisa memvalidasi soal **(done)**
	2. mengedit soal 
	3. membuat soal **(done)**
	4. membuat soalset **(done)**
	5. mengaupdate soalset 
	6. 
4. user
	1. mengedit soal
	2. membuat soal **(done)**
	3. membuat soalset **(done)**
	4. mengaupdate soalset
	5. 
5. ban
	1. nuuu cuma bisa read aja gak bisa ngapain2

### TODO
- [x] add bahasa
- [x] add mapel
- [x] add lvltoken
- [x] add permuser
- [x] add grupuser
- [x] add permgrup

- [x] del bahasa
- [x] del mapel
- [x] del lvltoken
- [ ] del permuser
- [ ] del grupuser
- [ ] del permgrup

- [ ] update bahasa
- [ ] update mapel
- [ ] update lvltoken
- [ ] update permuser
- [ ] update grupuser
- [ ] update permgrup


bila soal di edit soal baru akan di buat
- soal
- pejelasan
- jawaban benar salah123
- detail soal (bahasa,soalset,lvl,mapel,)
- edited (bila true maka soal akan di hide)

log edited akan di rec
- siapa yang edit
- id soalsoal
- kapan



soal id1
1+1
karena
2,3,51,2
id,public,1,mtk
0

**mau di edit**
soal id1
1+1
karena
2,3,51,2
id,public,1,mtk
1 (soal akan di hide)

**jadi soal baru**
soal id2
1+1
karena 1+1
2,3,51,2
id,public,1,mtk
0

db edites log
id 1 (user itu sendiri)
id soal 1
id soal yang baru 2
unixtime

**melihat apa yang berubah**
detail soal yang asli
detaill soal yang baru
kapan dan oleh siapa


```SQL
SELECT * FROM `auth_groups_permissions` LEFT JOIN auth_groups ON auth_groups_permissions.group_id = auth_groups.id LEFT JOIN auth_permissions ON auth_groups_permissions.permission_id =auth_permissions.id;
```


http://localhost:8080/api/v1/randomsoal?lvl=1&mapel=General
http://localhost:8080/api/v1/randomsoal?lvl=1&mapel=General

