# TVBox Channels
## Just for fun...

git config --global user.name "your name"  
git config --global user.email "your_email@youremail.com"  
ssh-keygen -t rsa -C "your_email@youremail.com"  

cd TVBox  
git init  
git add .  
git commit -m "TVBox Channels"  
git branch -M master  
git remote add origin git@github.com:qsguan/TVBox.git  
git push -u origin master  

git add Configs/* Spiders/* TVLive/* meowcf*.json  
git commit -m "TVBox Channels"  
git push -u origin master  

git clone --depth 1 git@github.com:qsguan/TVBox.git  # git version: v2.45.2  

## Download apk from:

* https://github.com/Archmage83/tvapk
* https://github.com/youhunwl/TVAPP/tree/main
```
{
  "urls": [
    { "name": "摸鱼儿接口", "url": "http://我不是.摸鱼儿.com" },
    { "name": "肥猫接口", "url": "http://肥猫.com" },
    { "name": "饭太硬接口", "url": "http://www.饭太硬.com/tv/" },
    { "name": "神秘哥哥们备用接口", "url": "http://fty.xxooo.cf/tv/" },
    { "name": "开心接口", "url": "http://rihou.cc:55" },
    { "name": "动漫城接口", "url": "https://www.yingm.cc/dm/dm.json" },
    { "name": "PG接口", "url": "https://git.acwing.com/iduoduo/orange/-/raw/main/jsm.json" },
    { "name": "俊佬接口", "url": "http://home.jundie.top:81/top98.json" },
    { "name": "道长接口", "url": "https://cdn.gitmirror.com/bb/xduo/libs/master/index.json" },
    { "name": "宝盒接口", "url": "http://mzjk.top/禁止贩卖" },
    { "name": "王小二放牛娃接口", "url": "http://tvbox.王二小放牛娃.top" },
    { "name": "菜妮丝接口", "url": "https://tv.菜妮丝.top" },
    { "name": "HG接口", "url": "https://api.hgyx.vip/hgyx.json" },
    { "name": "dxawi", "url": "https://dxawi.github.io/0/0.json" },
    { "name": "潇洒接口", "url": "https://github.moeyy.xyz/https://raw.githubusercontent.com/PizazzGY/TVBox/main/api.json" },
    { "name": "小苹果接口", "url": "https://bitbucket.org/xduo/duoapi/raw/master/xpg.json" }
  ]
}
