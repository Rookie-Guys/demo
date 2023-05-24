# Readme

## nginx 命令
### 1. 启动nginx: 
  > sudo nginx
### 2. 关闭nginx: 
  > sudo nginx -s quit -- 待nginx进程处理任务完毕进行停止
  > sudo nginx -s stop -- 先查出nginx进程id再使用kill命令强制杀掉进程
### 3. 重启nginx: 
  > sudo nginx -s reload