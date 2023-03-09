**[English](./README_en.md)**
## 介绍
这是一个将github上的开源项目[tweb](https://github.com/morethanwords/tweb)制作成docker镜像的一个项目，用来架设在自己的渣机上，查了dockerhub并没有找到多好用的，于是自己做了一个
## 用法
克隆本项目到本地，然后
```sh
docker build -t <镜像名字:标签> -f ./tweb_build .
#根据你自己的想法修改tweb.yml里的内容
docker-compose -f tweb.yml up -d
```
如果你没有做修改此时应该能通过127.0.0.1:8080使用了

