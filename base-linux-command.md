> 簡單列出常用的 Linux 指令，大多數的發行版或是 macOS 都通用

```
ls
```

列出當前非隱藏檔以外的檔案和資料夾

```
ls -al
```

列出可見的檔案、資料夾並包含隱藏檔案或資料夾

> 在 Linux 發行版可以把 "ls -al" 縮寫成 "ll"

```
date
```

顯示當前時間與日期

```
rm fileName
```

刪除檔案

```
rm -r dirName
```

刪除資料夾

```
1. cp /123/file1 /456/

2. cp /123/file1 /456/file2
```

1. 複製 file1 從 123 資料夾到 456
2. 複製 file1 從 123 資料夾到 456 並改檔名為 file2

```
1. mv /123/file1 /456/

2. mv /123/file1 /123/file2
```

1. 搬移 file1 從 123 資料夾到 456 資料夾
2. 將 file1 改檔名為 file2

> mv 指令在 Linux / macOS 環境中沒有做搬移到其他資料夾行為
>
> 會是修改檔案名稱的行為

`.` & `..`

> 在 Linux / macOS 環境中一個點代表當前目錄位置
>
> 兩個點則是上一層的目錄位置

```
systemctl status ServiceName

sample :
systemctl status apache2
systemctl status mysql
```

檢查服務狀態

```
systemctl start ServiceName

sample :
systemctl start apache2
systemctl start mysql
```

啟動服務

```
systemctl stop ServiceName

sample :
systemctl stop apache2
systemctl stop mysql
```

停止服務

```
systemctl restart ServiceName

sample :
systemctl restart apache2
systemctl restart mysql
```

重啟服務 ( 包含 stop 與 start 語法 )

```
pwd
```

顯示目前的目錄