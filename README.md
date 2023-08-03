# git_commands
 git buyruqlar ro'yxati
### Boshlash va proyektni yaratish

| Buyruq | tavsif |
| ------- | ----------- |
| `git init` | Mahalliy git repositoryni ishga tushirish |
| `git clone ssh://git@github.com/[foydalanuvchi-nomi]/[repository-nomi].git` | Masofaviy mahalliy repositoryni nusxalash|

### boshlang'ich Snapshotting

| Buyruq | tavsif |
| ------- | ----------- |
| `git status` | repository holatini tekshirish |
| `git add [file-nomi.txt]` | repositoryga file qo'shish |
| `git add -A` | barcha yangi fayllarni qo'shish|
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-nomi.txt]` |file yoki papkani o'chirish|

### Branching va Merging

| Buyruq | tavsif |
| ------- | ----------- |
| `git branch` | branch ro'yxati |
| `git branch -a` | barcha branch lar ro'yixati |
| `git branch [branch nomi]` | Yangi branch yaratosh|
| `git branch -d [branch nomi]` | branch ni o'chirish|
| `git push origin --delete [branch nomi]` | masofaviy branch ni o'chirish|
| `git checkout -b [branch nomi]` | yangi branchni yaratish va unga o'tish |
| `git checkout -b [branch nomi] origin/[branch nomi]` | masofaviy branchni nushalash va unga o'tish|
| `git branch -m [eski nomi] [yangi nomi]` | mahalliy branchning nomini o'zgartirish |
| `git checkout [branch nomi]` | branchni almashtirish|
| `git checkout -` | oxirgi ro'yxatdan o'tgan branchga o'tish|
| `git merge [branch nomi]` |mainga belgilangan branchni birlashtirish|
| `git merge [source branch] [target branch]` |ikkita branchni birlashtirish|
| `git stash` | o'zgarishlardagi xatolarni biron papkaga saqlash|
| `git stash clear` | barcha xatoliklarni tozalash |

### Yangilash 

| Buyruq | tavsif |
| ------- | ----------- |
| `git push origin [branch nomi]` | o'zgarishlarni belgilangan branchga yuklash|
| `git push -u origin [branch nomi]` |O'zgarishlarni belgilangan branchga yuklash va oxirgi o'zgarish sifatida eslab  qolish |
| `git push` | oxirgi o'zgartirilgan branchga o'zgarishlarni yuklash|
| `git push origin --delete [branch nomi]` | branchdagi ma'lumotlarni o'chirish |
| `git pull` | Mahalliy repository ni yangillash |
| `git pull origin [branch nomi]` | o'zgarishlarni masofaviy repository dan chaqirib olish|
| `git remote add origin ssh://git@github.com/[foydalanuvchi-nomi]/[repository-nomi].git` |masofaviy repository ni o'zingiznikiga nusxalash|
| `git remote set-url origin ssh://git@github.com/[foydalanuvchi-nomi]/[repository-nomi].git` | SSH ga repository havolasini o'rnatish|

### tekshirish

| Buyruq | tavsif |
| ------- | ----------- |
| `git log` | O'zgarishlarni ko'zdan kechirish |
| `git log --summary` | O'zgarishlarni batafsil ko'rish |
| `git log --oneline` | O'zgarishlarni qisqacha ko'rib chiqish |
| `git diff [source branch] [target branch]` | birlashtirishdan eyingi o'zgarishlarni ko'rib chiqish|


Bularning barchasini bilaman lekin GitHub desktop ishlataman )
