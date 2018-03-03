# BaiDuMusic
> 百度随心听网页端解析的数据，具体的抓包过程就不啰嗦了，还是要费点小时间。 
用swift写的一个简单的播放器，可在线播放音乐电台，支持后台播放，封面信息，可显示歌手名，专辑名，当前播放时间等，项目用到了第三方开源框架，有OC的，也有纯swift的，可以当做学习swift的例子。
# 说明  
以下接口数据是本人分析百度随心听网页端来的  
1. 获取频道列表数据  
`http://fm.baidu.com/dev/api/?tn=channellist`  
2. 根据频道id获取频道音乐数据列表信息  
`http://fm.baidu.com/dev/api/?tn=playlist&id=public_tuijian_rege`    
3. 根据songIds获取歌曲信息，如果要获取多首信息，包括歌曲下载链接地址，songIds之间用逗号隔开，如songIds = 913288,872633,3388338  
`http://fm.baidu.com/data/music/songlink?songIds=913288`  
4. 根据songIds获取歌曲信息，如果要获取多首信息，songIds之间用逗号隔开，如songIds = 913288,872633,3388338
`http://fm.baidu.com/data/music/songinfo?songIds=913288`  
# 相关阅读

https://github.com/bboyfeiyu/iOS-tech-frontier/blob/master/issue-3/iOS后台模式开发指南.md   
http://www.cnblogs.com/easy-coding/p/3569227.html  
http://blog.csdn.net/u012701023/article/details/48324791   
http://www.jianshu.com/p/ce279bc773dd 

