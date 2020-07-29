# Virtualbox 開啟後遇到錯誤碼 E_FAIL

>[參考連結](https://dotblogs.com.tw/d___s/2018/08/02/virtualboxruntimeerror)

1. 使用管理者權限打開終端機
2. 輸入 bcdedit 可以看到 hypervisorlaunchtype 狀態為預設的 Auto 
3. 輸入 bcdedit /set hypervisorlaunchtype off 之後重新開機
