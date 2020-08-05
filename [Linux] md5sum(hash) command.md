# Linux shell command : md5sum

>[參考連結](https://blog.gtwang.org/linux/generate-verify-check-files-md5-sha1-checksum-linux/)

1. 產生檔案的雜湊值
    `$ md5sum target.txt > hash.md5sum `

2. 自動進行檔案的 MD5 校驗碼比對

    ` $ md5sum -c hash.md5sum `
    
    比對相同: ` hash.txt: 正確 `
    
    比對不同: ` hash.txt: 錯誤 `
    
             ` md5sum: WARNING: 1 computed checksum did NOT match ` 

3. 方法: 先在其他資料夾產生目標檔案 MD5 雜湊值, 複製到目標資料夾進行比對
