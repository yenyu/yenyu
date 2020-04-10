# yenyu
mkdir yenyu
cd yenyu
echo "# yenyu" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@gitpub.com:yenyu/yenyu.git
git push -u origin master
git add .
git commit -m "second commit"
git push -u origin master
git add .
git commit -m "third commit"
git push -u origin master
