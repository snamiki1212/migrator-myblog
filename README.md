# Migration script for my blog (only one used)

This migrator is tool for [GitHub - snamiki1212/myblog: Lunash 🌙](https://github.com/snamiki1212/myblog). Changing directory structure.

```zsh
## before ----------------------
/posts
  /post1.md
  /post2.md
  /post3.md

/img
  /post1-img1.jpg
  /post1-img2.jpg
  /post2-img2.jpg

## After -----------------------
/contents
  /post1
    /index.md
    /img1.jpg
    /img2.jpg
  /post2
    /index.md
    /img2.jpg
  /post3
    index.md
# 正確にはディレクトリ・ファイルの名前は違う名前で生成してた
```

## dir

```zsh
/myblos
  /scripts
    /migrator # this repository
```
