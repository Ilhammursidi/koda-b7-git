# GIT BASIC

**1. Inisialisasi sistem git**
```sh
$ git init
```

**2. Save into staging area (temporary)**
```sh
$ git add [filepath...]
```

**3. Commit (Permanent changes)**
```sh
$ git commit [option] [argument]
```
option:

- ``-m`` : menambahkan pesan commit
```sh
$ git commit -m "type: description"
```

- menambahkan pesan panjang
```sh
$ git commit
```
- memperbaiki pesan commit yang baru saja terjadi
```sh
$ git commit --amend
```
