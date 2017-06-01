# 科技部陳情系統(Petition)
#### Struts2
#### 資料庫設定：src/com/rifartek/Database/database.properties
#### 其他設定：src/project.properties

#### 外部郵件資料庫(SQL Server)
*    Schema - doc/DB/SQLServer/PTITDB/PTITDB.sql
*    資料 - doc/DB/SQLServer/PTITDB/data
*    匯入資料 - bcp_import_mail_tables.bat
+        修改：IP、DB、USER、PASSWORD

#### 陳情系統資料庫(SQL Server)
*    Schema - doc/DB/SQLServer/petition/petition.sql
*    資料 - doc/DB/SQLServer/petition/data/
*    匯入資料 - bcp_import_petition_tables.bat
+       修改：IP、DB、USER、PASSWORD

#### 後台設定(petition-backend)
    src/project.properties
    SSO 設定
        SSO.LINK=http://10.201.80.115/most-backend
        SSO.USERPROFILE.LINK=http://10.201.80.115/most-backend/api/sso/1.0/userProfile
        SSO.LOGIN.LINK=http://10.201.80.115/most-backend/sso/login
        SSO.ISLOGIN.LINK=http://10.201.80.115/most-backend/api/sso/1.0/islogin
