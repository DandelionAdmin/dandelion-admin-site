## 更新日志   :id=log

**当前版本：** [![Sonatype Maven Release](https://img.shields.io/nexus/r/https/oss.sonatype.org/club.gclmit/chaos-bom.svg?style=flat-square)](https://search.maven.org/search?q=g:%20club.gclmit%20AND%20a:%20chaos-bom)
[![Sonatype Maven Snapshots](https://img.shields.io/nexus/s/https/oss.sonatype.org/club.gclmit/chaos-bom.svg?style=flat-square)](https://oss.sonatype.org/content/repositories/snapshots/club/gclmit/)

### 2.4.4

- 🎨: 优化获取文件后缀的逻辑和新增上传文件白名单🎨: 优化获取文件后缀的逻辑和新增上传文件白名单
- ✨: 新增springdoc支持
- 🎨: 新增jackson工具类和修复map to object🎨: 新增jackson工具类和修复map to object
- 🐛: 修复bom依赖bug
- 🐛: 修复UserAgentUtils 加载依赖错误
- 🔊: 更新日志

### 2.4.3

- feat: 新增随机成功UserAgent方法
- fix: 优化提供的文件上传方法
- build: 采用最小依赖的方法优化依赖
- fix: 修复chaos-bom模块缺少本项目依赖
- style: 调整javadoc参数
- style: 调整错误命名
- style: 基于idea格式化代码

### 2.4.2

- ci: 修复自动发布包异常

### 2.4.1

- ci: 修复github action
- ci: 使用sonar 优化代码
- fix: 修复Make sure not setting any maximum content length limit is safe here
- style: 规范Javadoc

### 2.4.0

- feat: maven to gradle
- feat: 合并bom代码到当前项目
- build: 升级依赖
- docs: 取消同步Javadoc文档到gitee
- style: 修改返回类型风格
- style: 删除注解@date
- style: 删除多余的.gitignore文件

### 2.3.7

- 新增`DefaultFileService`基于id删除的方法
- 新增`CHANGELOG.md`版本记录管理
- chaos.sh -> chaos.py
- requestClient 新增上传文件参数支持
- 优化GlobalExceptionHandler、RestApiController类注解
- 修复chaos-storage中阿里云失效的bug
- 优化函数注释
- 升级依赖

### 2.3.6

- 优化请求参数
- 修改参数命名
- 优化查看相关注解

### 2.3.5

- 优化通用Build参数
- 新增Github Action 生成JavaDoc 功能
