��޳������t��(Petition)
Struts2
��Ʈw�]�w�Gsrc/com/rifartek/Database/database.properties
��L�]�w�Gsrc/project.properties

�~���l���Ʈw(SQL Server)
    Schema
        doc/DB/SQLServer/PTITDB/PTITDB.sql
    ���
        doc/DB/SQLServer/PTITDB/data
    �פJ���
        bcp_import_mail_tables.bat
        �ק�H�U��T
        IP�BDB�BUSER�BPASSWORD

�����t�θ�Ʈw(SQL Server)
    Schema
        doc/DB/SQLServer/petition/petition.sql
    ���
        doc/DB/SQLServer/petition/data
    �פJ���
        bcp_import_petition_tables.bat
        �ק�H�U��T
        IP�BDB�BUSER�BPASSWORD

��x(petition-backend)
SSO �]�w
src/project.properties

    SSO.LINK=http://10.201.80.115/most-backend
    SSO.USERPROFILE.LINK=http://10.201.80.115/most-backend/api/sso/1.0/userProfile
    SSO.LOGIN.LINK=http://10.201.80.115/most-backend/sso/login
    SSO.ISLOGIN.LINK=http://10.201.80.115/most-backend/api/sso/1.0/islogin
