## 目標：
基於作業中的busybox的概念實現自己的版本的『lazybox』，並瞭解有些指令一定要在shell中實作。

## 支援的功能：
1.cd 

2.soft link, hard link

3.stat，依序顯示file owner、atime、mtime、ctime

4.chown

5.sudo後的一段時間內不需要再次輸入密碼

6.建立softlink連到lazybox，包含：ln、chown、stat以及lazyshell

7.當使用者輸入ln、chown、stat等，優先執行與lazybox擺在同一個工作目錄的softlink
