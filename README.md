# 吾爱破解自动签到Github Action 版

## 使用说明
0.获取你的Cookie
 - 在网页浏览器中登录你的吾爱账号.然后F12打开浏览器控制台.刷新当前页面.在网络(NewWork)这一栏,找到第一个网络请求.如图
 ![image](https://user-images.githubusercontent.com/30728105/203260271-bff2cc1b-9a85-479c-8536-13bef415d20e.png)
 - 然后在Headers中找到 Request Headers 这一栏.找到其中的Cookie.鼠标右键复制值(copy value).然后就取到了你的cookie
 ![image](https://user-images.githubusercontent.com/30728105/203261131-c65c018a-6746-4a97-b1b4-6a4d2d24b811.png)

1.FORK该仓库，然后点击你的仓库右上角的 Settings，找到 Secrets 这一项，点击action添加一个密钥。其中 POJIE 存放你的 COOKIE
 ![image](https://user-images.githubusercontent.com/30728105/165697595-302d3965-c456-4ec0-8733-533256b6041b.png)

2.设置好环境变量后点击你的仓库上方的 Actions 选项，第一次打开需要点击 I understand... 按钮，确认在 Fork 的仓库上启用 GitHub Actions 。

3.然后任意发起一次提交，可以选择修改readme文件。

4.至此自动签到就搭建完毕了，可以再次点击Actions查看工作记录，如果有52Pojie Auto Sign则说明workflow创建成功了。点击右侧记录可以查看详细签到情况
 ![image](https://user-images.githubusercontent.com/30728105/165697734-a38d6d46-db0e-40a1-8b21-e0d50443de36.png)
5
