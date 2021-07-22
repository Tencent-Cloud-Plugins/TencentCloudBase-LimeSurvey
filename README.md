<p align="center">
  <img height="100px" src="./logo.svg" />
</p>

# [LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)

Limesurvey 是排名第一的开源调查软件，可以帮助您更好地了解他人的想法。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-LimeSurvey&branch=master)

### 配置
- `DB_HOST`: 数据库地址
- `DB_PORT`: 数据库端口
- `DB_NAME`: 数据库名称
- `DB_USERNAME`: 数据库用户名
- `DB_PASSWORD`：数据库密码
- `ADMIN_USER`：应用用户账号
- `ADMIN_PASSWORD`：应用用户密码

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
