1. Develop Watchdog service, complete registering in Windows service; for watched application, watchdog can start it initially, restart it when it closes unnormally and let it off when it closes normally.        
2. Develop system tray application based on MFC, the tray can watch the service status of watchdog and start/close the watchdog.      
3. Watchdog service can watch the system tray application.      

Difficulties:    
1. VC++ basic thread synchronization    
https://blog.csdn.net/thefutureisour/article/details/8155888     
2. Thread used in MFC app    
https://blog.csdn.net/naibozhuan3744/article/details/78748750    
3. Windows service can start/close the windows app with UI    
https://blog.csdn.net/sslj81/article/details/8984748    
https://blog.csdn.net/weixin_44894150/article/details/89359687    

