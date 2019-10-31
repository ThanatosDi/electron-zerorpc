# electron-zerorpc
放置 nodejs 的 package.json 用以快速建立 electron 開發環境  

| Platform |   Run  |
|:--------:|:------:|
|  Windows |    ○   |
|   MacOS  | unknow |
|   Linux  | unknow |

在進行安裝之前建議先進行安裝 zeromq 確認是否編譯成功  
如編譯失敗請先安裝 windows-build-tools (Visual Studio 2015)
```
npm install --vs2015 --global windows-build-tools
```
注意：windows-build-tools 將會安裝 Python 2.7 如原本系統已有 Python 請記得要將其他版本的 python.exe 加上版號以區隔  
