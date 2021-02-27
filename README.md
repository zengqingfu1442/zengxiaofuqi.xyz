# zengxiaofuqi.xyz

# 使用 docker-compose 部署自己的 wordpress 博客

## 先购买自己的域名和服务器, 并将域名映射到自己的服务器
略

## 克隆本项目，将 zengxiaofuqi.xyz 替换成自己的域名（docker-compose.yml, nginx-conf/nginx.conf）
grep -Ri 'zengxiaofuqi' ./

## 部署 wordpress 博客
1. 服务器上安装 docker, docker-compose
2. docker-compuse up -d 
