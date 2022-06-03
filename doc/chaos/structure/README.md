## 项目结构  :id=config

```
Chaos  
├── CHANGELOG.md                    更新日志
├── README.md                       项目介绍 
├── README_EN.md                    项目介绍(英文)
├── build.gradle                    构建配置
├── chaos-bom                       bom模块 
│ ├── README.md                         模块介绍
│ └── build.gradle                      模块构建配置
├── chaos-core                      基础模块
│ ├── README.md                         模块介绍 
│ ├── build.gradle                      模块构建配置
│ └── src                               源码目录  
├── chaos-extra                     扩展模块
│ ├── README.md                         模块介绍 
│ ├── build.gradle                      模块构建配置
│ └── src                               源码目录  
├── chaos-logger                    日志模块
│ ├── README.md                         模块介绍 
│ ├── build.gradle                      模块构建配置
│ └── src                               源码目录  
├── chaos-spring-boot-starter       starter模块
│ ├── README.md                         模块介绍 
│ ├── build.gradle                      模块构建配置
│ └── src                               源码目录  
├── chaos-storage                   存储模块
│ ├── README.md                         模块介绍 
│ ├── build.gradle                      模块构建配置
│ └── src                               源码目录  
├── chaos-web                       web模块
│ ├── README.md                         模块介绍 
│ ├── build.gradle                      模块构建配置
│ └── src                               源码目录  
├── docs                            文档
│ ├── chaos.sql                         代码相关sql
│ ├── design                            设计文档  
│ ├── img                               图片   
│ └── version.txt                       版本日志 
├── git.sh                          git命令
├── gradle                          gradle配置
│ ├── publish-bom.gradle                publish-bom 配置
│ ├── publish.gradle                    publish 配置
│ ├── sonar.gradle                      sonar 配置
│ └── wrapper                           gradle wrapper 配置
├── gradle.properties               gradle配置
├── gradlew              
├── gradlew.bat
└── settings.gradle                  
```

## 核心文件

> SQL脚本：`chaos.sql` [查看](https://raw.githubusercontent.com/DandelionAdmin/chaos/master/docs/chaos.sql)。
