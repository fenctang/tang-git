gitk
mkdir tang-git
cd tang-git
git config --global user.name "fenctang"
git config --global user.name "tang@cfp.fenc.com"
git init
touch index.htm
git add index.htm
git commit -a "first commit"
windows ssh 教學 https://ithelp.ithome.com.tw/articles/10205988
git push -u origin tang-git
git push tang-git // 與remote 同步
