![shields](https://img.shields.io/badge/Docs-Updating-red)

:smiley_cat: :dash: :heart: :smiley_cat: :dash: :heart: :smiley_cat: :dash: :heart:

:writing_hand: ***Keep Update and Continue.*** :writing_hand:

:smiley_cat: :dash: :heart: :smiley_cat: :dash: :heart: :smiley_cat: :dash: :heart:

# MarkDown

https://www.bookstack.cn/read/mpe/zh-cn-toc.md#%E7%9B%AE%E5%BD%95%E5%88%97%E8%A1%A8%EF%BC%88TOC%EF%BC%89

### R bookdown
git config --global user.email "hgyyxg@163.com"

git config --global user.name "HGY3"

git clone https://github.com/HGY3/MyScience.git

cd MyScience

#### 创建一个名为 gh-pages 的分支，并清除全部文件
git checkout --orphan gh-pages

git rm -rf .

#### 创建一个隐藏文件 .nojekyll
touch .nojekyll or R: file.create('.nojekyll')

git add .nojekyll

git commit -m "Initial commit"

git push origin gh-pages

#### 将储存库克隆到书籍输出目录 book-output
cp D:\04.MyLife\HGY3-Github\MyScience\Bookdown\_book\*  D:\04.MyLife\HGY3-Github\MyScience\MyScience\

git add --all *

git commit -m "Update the book"

git push -q origin gh-pages


### *制作 README.md*

https://github.com/darsaveli/Readme-Markdown-Syntax

https://github.com/ikatyang/emoji-cheat-sheet


徽标添加

https://app.travis-ci.com/account/repositories

https://shields.io/

https://about.codecov.io/