hayashi.dental
========

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [References](#references)
	- [Photo](#photo)
- [Develop](#develop)
	- [Color](#color)
- [Deploy](#deploy)
	- [using Git-FTP](#using-git-ftp)
		- [Install](#install)
			- [MacOS](#macos)
		- [Initialize](#initialize)
		- [Upload](#upload)
- [ToDo](#todo)
	- [HIGH / FIXME](#high-fixme)
	- [MID / TODO](#mid-todo)
	- [LOW / XXX](#low-xxx)

<!-- /TOC -->

## References
### Photo
* http://hayashi.dental/photo/

## Develop
### Color
Green: #188080
Blue: #304080
Red: #801818

## Deploy
### using Git-FTP
#### Install
##### MacOS
```
$ brew install git-ftp
```

#### Initialize
```
$ git config git-ftp.url ftp://ホスト名/該当するフォルダまでのパス
$ git config git-ftp.user ユーザー名
$ git config git-ftp.password パスワード
$ git ftp init -v
```

#### Upload
```
$ git ftp push
```

## ToDo
### HIGH / FIXME

### MID / TODO

### LOW / XXX
