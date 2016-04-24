#魔窗Android SDK FAQ
##(1)Jar包重复（暂未集成新浪微博分享，忽略此步）<br>
如果显示微信分享等jar包重复。（特别如果集成了shareSDK，会报微博的jar包重复）<br>
Ⅰ将微信jar包libmma.jar删除。<br>
Ⅱ初始化魔窗SDK时，启用shareSDK<br>
```java
MWConfiguration config = new MWConfiguration(this);
  config.setSharePlatform(MWConfiguration.SHARE_SDK);
```
##（2）分享弹框缺少图标<br>
将assets文件夹下的文件拷贝到相应文件夹即可。

 
