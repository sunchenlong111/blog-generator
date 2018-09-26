---
title: git 入门
date: 2018-09-27 00:05:12
tags:
---


git init:初始化仓库，会在文件夹里面建一个 .git目录，这个子目录含有你初始化的 Git 仓库中所有的必须文件，这些文件是 Git 仓库的骨干。 但是，在这个时候，我们仅仅是做了一个初始化的操作，你的项目里的文件还没有被跟踪。


git add:在一个已经存在文件的文件夹中，应该开始跟踪这些文件，git add 将这些文件添加到暂存区，
可以一个一个添加 git add + 文件名 或者全部添加 git add .



git commit:将添加到暂存区的文件提交到线上仓库里
	可以一个一个地 commit
	git commit index.html -m '添加index.html'
	git commit css/style.css -m "添加 css/style.css"
	
	你也可以一次性 commit
	git commit . -m "添加了几个文件"

