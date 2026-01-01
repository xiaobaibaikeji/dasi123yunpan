# dasi123yunpan
# 123云盘解锁
>锐评：当初靠免费不限速画大饼吸引用户，现在流量腰斩、处处设卡，连在线播放都要算计用户那点可怜的流量额度，吃相堪称教科书级别的难看。所谓的"打击羊毛党"不过是块遮羞布——把正常用户当贼防，把免费权益当施舍，却绝口不提自己当初靠什么起家。现在摆明了就是要用最恶心的体验逼你开会员，还假惺惺搞什么签到领流量，这套既要立牌坊又要做生意的把戏，早该被网盘行业玩烂了。
<div align="center">
    <img src="https://raw.gitmirror.com/QingJ01/123pan_unlock/refs/heads/main/icon.ico" width="128px" style="border-radius: 10px"/>
    <br>
    <img src="https://img.shields.io/badge/version-1.2.0-blue?style=flat-square" alt="version">
    <img src="https://img.shields.io/github/stars/QingJ01/123pan_unlock?style=flat-square" alt="stars">
    <img src="https://img.shields.io/github/forks/QingJ01/123pan_unlock?style=flat-square" alt="forks">
    <img src="https://img.shields.io/github/issues/QingJ01/123pan_unlock?style=flat-square" alt="issues">
    <img src="https://img.shields.io/github/license/QingJ01/123pan_unlock?style=flat-square" alt="license">
    <br>
    <b>让你的123云盘体验更好</b>
</div>

## ✨ 特性

### 🎭 会员功能
- **身份显示**: 完美模拟会员/超级会员身份
- **等级提升**: 支持自定义等级(最高128级)
- **过期时间**: 自定义会员过期时间
- **广告移除**: 一键关闭所有广告显示

### 🚀 下载增强
- **容量突破**: 解除1GB下载限制
- **场景支持**: 
  - ✅ 个人网盘页面下载
  - ✅ 分享页面文件下载
  - ✅ 不限速不限流文件下载

- **链接生成**: 一键生成文件秒传链接，快速分享
- **链接保存**: 支持导入秒传链接，秒速保存文件
- **格式支持**: 
  - ✅ 纯文本格式
  - ✅ JSON格式（带文件列表预览）
- **批量操作**: 
  - ✅ 多文件/文件夹批量生成
  - ✅ 批量导入保存
- **智能队列**: 
  - ✅ 任务队列管理
  - ✅ 进度实时显示
  - ✅ 失败重试机制
  - ✅ 任务取消功能
- **文件操作**: 
  - ✅ 文件拖拽导入
  - ✅ JSON导入/导出
  - ✅ 详细结果展示

### 🎨 个性化
- **用户名称**: 自定义显示昵称
- **头像设置**: 自定义头像图片
- **界面美化**: 精心设计的设置面板
- **便捷操作**: 快速切换各项功能

## 🌈 界面预览

<div align="center">
    
![设置](https://fastly.jsdelivr.net/gh/bucketio/img8@main/2025/10/06/1759763069658-f7f083b5-03b1-462c-8a30-e4a0245ad21a.png)
  
![保存秒传文件](https://fastly.jsdelivr.net/gh/bucketio/img2@main/2025/10/06/1759763099918-f23ba5e5-f771-4b22-bdbd-a0793e3fcbcf.png)
</div>

## 📦 安装使用

### 安装步骤
1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展
2. 点击 [安装脚本]() 跳转至123云盘
3. 点击安装按钮完成安装

### 使用方法

#### 基础功能
1. 访问 [123云盘](https://www.123pan.com) 网站
2. 点击右下角 `设置面板` 按钮
3. 在面板中配置所需功能:
   - 开启/关闭会员模拟
   - 切换会员等级显示
   - 自定义用户信息
   - 调整其他设置项

#### 秒传功能
1. **生成秒传链接**:
   - 在文件列表页面，点击右下角 `⚡ 秒传` 按钮
   - 选择 `生成秒传链接`![](https://fastly.jsdelivr.net/gh/bucketio/img15@main/2025/10/06/1759762909018-0a020f92-9a01-46d1-9a32-0d329455e8db.png)
  
   - 选中要分享的文件/文件夹
   - 等待生成完成，复制链接或导出JSON
   
2. **保存秒传文件**:
   - 点击 `⚡ 秒传` 按钮
   - 选择 `保存秒传文件`![](https://fastly.jsdelivr.net/gh/bucketio/img6@main/2025/10/06/1759762827380-f0bdaabc-aa98-451f-97d5-5d9521c31aa5.png)
  
   - 粘贴秒传链接或拖入JSON文件
   - 点击保存，等待完成

## 🔄 更新日志

### v1.2.0 (2026-1-02)
- ⚡️ **重大更新**: 整合秒传功能
  - 支持生成和保存秒传文件
  - 支持纯文本和JSON两种格式
  - 实现任务队列管理系统
  - 进度条支持最小化显示
  - 文件拖拽导入功能
  - 失败自动重试机制
  - 详细的操作结果展示
- 🎨 优化UI界面，统一按钮样式
- 🔧 删除无用调试日志，提升性能
- 🐞 修复事件监听器泄漏
- 🏗️ 修复错误处理不一致
