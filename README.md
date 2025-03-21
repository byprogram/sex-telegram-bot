# sex-telegram-bot

基于 Telegram 的成人内容分享与互动机器人，支持视频上传、积分系统和分类浏览功能。

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

3. 配置环境变量
将 <kbd>config.example.json</kbd> 重命名为 config.json，并填写必要的信息，例如 Telegram 机器人令牌、数据库连接等。

4. 启动机器人
使用以下命令启动机器人：

```bash
nodemon
```
