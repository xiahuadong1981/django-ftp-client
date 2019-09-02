安装
将文件夹ftp_client复制到项目中

修改项目settings.py。像这样添加到INSTALLED_APPS ftp_client应用程序：

INSTALLED_APPS = (
    ..., 
    'ftp_client'
)
包括项目urlconf url(r'^ftp-client/', include('ftp_client.urls', namespace='ftp_client'))
