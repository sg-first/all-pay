# all-pay
支持Python3.6的all-pay

## 部署
1. 先创建一个Django模板云函数
2. 进入djangodemo，打开settings.py，将第46行'django.middleware.csrf.CsrfViewMiddleware'注释掉
3. 回到src目录
4. pip3.6 install all-pay==1.0.3 -t .
5. 删除all-pay的两个文件夹
6. 拉取本all-pay库，并将两个文件夹复制到src目录下