# PaddleLabel-Test

后端API测试步骤：
1. 安装 [insomnia](https://github.com/Kong/insomnia)
2. 在insomnia主页右上角，点Create，之后Import From -> File，选择本项目所在路径，PaddleLabel-Web.json 和 PaddleLabel-ML.json都会被导入
![image](https://user-images.githubusercontent.com/29757093/192162306-5876c270-e14a-4093-8753-35470f371e0d.png)

3. 进入测试项目，在最上面选择debug，Ctrl+Enter发送API请求

注：这两个json里的openapi spec不保证是最新的，以PaddleLabel和PaddleLabel-ML里的openapi.yaml为准

![image](https://user-images.githubusercontent.com/29757093/173211697-65c873ae-5611-492a-a909-9e71fa192441.png)
