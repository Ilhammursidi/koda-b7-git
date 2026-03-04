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
**4. Remote Repository**
- Add remote repository
```sh
$ git remote [command] [argument]
```
```sh
# view remote list
$ git remote
# add remote repository
$ git remote add [remote_name] [remote_ur]
# view remote url
$ git remote get-url [remote_name]
```

- Sinkronisasi dengan ``push`` dan ``pull``
```sh
# sinkronisasi dari lokal ke remote
$ git push [remote_name] [branch_name]
# sinkronisasi dari remote ke lokal
$ git pull [remote_name] [branch_name]
```