# IOS-Developer-Tools  
##一、 Mac版APP
###1.simpholders  
快速查看模拟器中app的沙盒内部文件结构  
![image](http://7xotrj.com1.z0.glb.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-05-12%2000.50.16.png)

 [official website](https://simpholders.com)  
 [free down](http://pan.baidu.com/s/1pKPZ9dL)  
  ***
###2.NetWork Link  
模拟各种复杂的网络环境，很方便调试APP在各种网络环境下的UI和交互逻辑是否正常。  
    
![image](http://7xotrj.com1.z0.glb.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-05-12%2022.53.37.png)  
[free down](http://pan.baidu.com/s/1slMNYPJ)  
***
###3.Reveal“偷窥”别人的APP      
1.iphone越狱（没有越狱就不用往下看了）  
2.iphone越狱后，在Cydia中安装Reveal Loader  
3.iphone设置Reveal Loader对某个App生效    
4.官网下载Mac版[Reveal](http://revealapp.com)  
5.iphone和mac处在同一个局域网内 （连同一个wifi，查看ip）  
6.打开Mac上的Reveal，启动手机中药偷窥的App，点击Reveal左上角的no connection，下拉列表中选中一项。  
附图：  
![第三步](http://7xotrj.com1.z0.glb.clouddn.com/reveal_1.PNG)  
![激动人心的时刻](http://7xotrj.com1.z0.glb.clouddn.com/reveal_2.png)  
**备注**   
如果没有抓到UI图层很有可能是一下几种原因：  
1.iphone中的Reveal Loader插件和Mac中的Reveal版本不一致。  
解决方案：去官网下载最新版本的Mac版Reveal      
2.iphone和mac连同一个wifi，如果是公司的局域网，就很有可能被监控和拦截，不允许局域网下传输数据（我曾经就遇上了，折腾了好久，无意中发现的）    
解决办法：用iphone开热点，mac连接iphone的热点，确保在同一局域网下。 
*** 
### 4.破解Reveal 
4.1[Reveal破解补丁](http://pan.baidu.com/s/1skPpUUh)  
4.2安装原版并运行一次 －－ 假设安装到 /Applications/Reveal.app/  （如果已安装，跳过这一步）  
4.3打开/Applications/Reveal.app/Contents/MacOS/Reveal 改名为 Reveal_  
4.4将附件复制进来（ChinaPYG.dylib和Reveal）  
4.5重新启动Reveal  
***  
### 5.iFunBox  
Mac与越狱iphone之间的文件传送神器：  
1.Mac文件复制到越狱iphone  
2.iphone中文件复制到Mac  
3.删除iphone中的文件  
4.查看和操作整个iphone文件系统  
![iFunBox](http://7xotrj.com1.z0.glb.clouddn.com/iFunBox.png)
***