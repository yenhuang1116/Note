# bsdiff 原始碼建置問題 

>[參考連結](https://www.twblogs.net/a/5b7c698b2b71770a43dadce9/?lang=zh-cn)

>[下載連結](https://github.com/mendsley/bsdiff)

1. 找不到 bzlib.h : 下載 bzip2 安裝, <> 修改成 ""
2. Make in bsdiff folder : undefined reference to BZ2_bzWriteOpen 
    -> 編譯 bzip2 的 so檔, 加入 /usr/lib, /sbin/ldconfig
    -> makefile 的選項 LIBS = -lbz

