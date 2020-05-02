# 介绍

通过`docker`创建PHP开发环境. 

# 使用说明

1. 将项目`clone`到你本地的任意位置
2. 保证已经安装了git
4. 将 `config/nginx/config/default.conf/default.conf` 文件中的项目路径修改为你自己的项目路径
5. 将 `docker-compose.yml` 文件中的 `/Users/hujing/dir` 路径修改为你自己的项目路径
3. 执行命令: `docker-compose up`
4. 访问 `localhost` 测试

完成. 其中修改了其中的两个内容, 然后即可一键启动. 