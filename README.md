# ��޳������t��(Petition)
#### Struts2
#### ��Ʈw�]�w�Gsrc/com/rifartek/Database/database.properties
#### ��L�]�w�Gsrc/project.properties

#### �~���l���Ʈw(SQL Server)
*    Schema - doc/DB/SQLServer/PTITDB/PTITDB.sql
*    ��� - doc/DB/SQLServer/PTITDB/data
*    �פJ��� - bcp_import_mail_tables.bat
+        �ק�GIP�BDB�BUSER�BPASSWORD

#### �����t�θ�Ʈw(SQL Server)
*    Schema - doc/DB/SQLServer/petition/petition.sql
*    ��� - doc/DB/SQLServer/petition/data/
*    �פJ��� - bcp_import_petition_tables.bat
+       �ק�GIP�BDB�BUSER�BPASSWORD

#### ��x�]�w(petition-backend)
    src/project.properties
    SSO �]�w
        SSO.LINK=http://10.201.80.115/most-backend
        SSO.USERPROFILE.LINK=http://10.201.80.115/most-backend/api/sso/1.0/userProfile
        SSO.LOGIN.LINK=http://10.201.80.115/most-backend/sso/login
        SSO.ISLOGIN.LINK=http://10.201.80.115/most-backend/api/sso/1.0/islogin
