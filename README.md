### tulis ke README.md
echo "# markdown_tutorial" >> README.md


### membuat inisialisasi jika belum ada
###### jika anda mengclone, inisialisasi sudah ada
git init

### menambahkan file
git add README.md

### membuat commit 'keterangan'
git commit -m "first commit"

### remote ke origin repository
git remote add origin https://github.com/moeclay/markdown_tutorial.git

### push ke server repository
git push -u origin master