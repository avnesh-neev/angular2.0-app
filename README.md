# AngularJs2.0 Beta Boilerplate

## Description

Steps: 
1: Clone repo
```
git clone https://github.com/avnesh-neev/angular2.0-app.git
```
2: Install packages
```
npm install
```
3: Start server (includes auto refreshing) and gulp watcher
```
npm start
```

###If npm start is not working correctly, then follow given below steps:

First you need update npm, lite-server and typescript:
```
sudo npm update -g && sudo npm install -g concurrently lite-server typescript
```

Delete node_modules folder from your Angular project directory (if exist). Next run:
```
npm install
```

After that resolve ENOSPC errors:
```
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```