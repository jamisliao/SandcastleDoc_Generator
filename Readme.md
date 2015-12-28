###**使用方式**###
產生Sandcastle shfbproj

	p:\SandcastleDoc_Generator.exe 
        -commandType createshfbproj 
        -SourceProjectPath 'C:\Users\JamisLiao\Documents\Sandcastle_Test' 
        -SandcastleTemplatePath P:\Sandcastle\SandcastleDoc\SandcastleDoc.shfbproj 
        -ConfigType Debug 
        -DllFolderName Sandcastle_Test 
        -DllStartWith Sandcastle

刪除Sandcastle shfbproj

	p:\SandcastleShfbprojGenerator.exe 
		-commandType deleteshfbproj 
		-SourceProjectPath 'C:\Users\JamisLiao\Sandcastle_Test'
        
###**參數說明**###
-CommandType : createshfbproj or deleteshfbproj

-SourceProjectPath : 專案資料夾路徑

-SandcastleTemplatePath : Sandcastle shfbproj template

-ConfigType : 專案編譯時選擇的組態設定

-DllFolderName : 要產生文件的專案資料夾位置

-DllStartWith(選項) : 過濾要產生文件的DLL檔