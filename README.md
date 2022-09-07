# 吾爱破解自动签到Github Action 版

## 使用说明
1.FORK该仓库，然后点击你的仓库右上角的 Settings，找到 Secrets 这一项，点击action添加一个密钥。其中 POJIE 存放你的 COOKIE
 ![image](https://user-images.githubusercontent.com/30728105/165697595-302d3965-c456-4ec0-8733-533256b6041b.png)

2.设置好环境变量后点击你的仓库上方的 Actions 选项，第一次打开需要点击 I understand... 按钮，确认在 Fork 的仓库上启用 GitHub Actions 。

3.然后任意发起一次提交，可以选择修改readme文件。

4.至此自动签到就搭建完毕了，可以再次点击Actions查看工作记录，如果有52Pojie Auto Sign则说明workflow创建成功了。点击右侧记录可以查看详细签到情况
 ![image](https://user-images.githubusercontent.com/30728105/165697734-a38d6d46-db0e-40a1-8b21-e0d50443de36.png)
