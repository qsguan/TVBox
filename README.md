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

git clone git@github.com:qsguan/TVBox.git  


"dtFromName":   "concat('播放源',count(preceding::div[contains(@class,'module-tab-item')])+1)",
"dtFromNameR":  "(\\S+).0",
