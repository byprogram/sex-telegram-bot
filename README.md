# Telegram色色机器人

基于 Telegram 的成人内容分享与互动机器人，支持视频上传、积分系统和分类浏览功能。<br>
[在线演示]([@](https://t.me/)sese8_bot)

## 功能特点

- **视频分享**：用户可上传并分享个人制作的成人视频内容
- **积分系统**：通过分享内容/邀请用户获取积分，解锁高级功能
- **内容分类**：按多样化兴趣需求浏览筛选不同类别内容
- **用户互动**：社区交流功能支持用户分享观感和体验

## 安装与使用

### 1. 克隆仓库
```bash
git clone https://github.com/byprogram/sex-telegram-bot.git
cd sex-telegram-bot
```
### 2. 安装依赖
确保您已安装 Node.js 和 npm，然后运行以下命令：

```bash
npm install
```
### 3. 导入数据库
导入data.sql到mysql数据库

### 4. 配置环境变量
在 <kbd>config/conf.js</kbd> 填写必要的信息，例如 Telegram 机器人令牌、数据库连接等。<br>
在数据库表 <kbd>config</kbd> 插入两条数据 
```sql 
INSERT INTO `config`( `value`, `value2`, `type`, `description`) VALUES ('机器人token','机器人用户名','sese_bot_token','任意备注');INSERT INTO `config`( `value`, `type`, `description`) VALUES ('采集群ID','tg_admin_groupid','任意备注');
```

### 5. 启动机器人
使用以下命令启动机器人：

```bash
nodemon
```

5.采集视频
配置好管理群ID，将需要采集的视频转发或上传至群内，采集成功后机器人会在群内自动通知

## 联系方式
如有疑问，请通过 Telegram 联系我：[@byprogramer](https://t.me/byprogramer)

## 注意事项
#### 本项目仅供学习与研究使用，请勿用于非法用途。
#### 使用者应遵守所在地区的法律法规，确保成人内容的分享与浏览在合法范围内进行。
#### 开发者不对用户上传的内容负责，用户需对自身行为承担责任。
