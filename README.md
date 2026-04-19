# 0216-dify-b-
实现b站视频的评论与弹幕等信息获取，并对此进行用户情绪画像分析
首先本地部署docker dify，详情可参考b站相关教学
然后本地python环境部署，调整内网端口，获取api所需的cookie，方法参考https://github.com/Nemo2011/bilibili-api
dify自定义插件，schema文件配置，接口与py文件内一致，测试通过即可
导入DSL文件，进行LLM基础配置后即可开始测试！
需要传入的参数是bid，也可说明所需数据样本的数量
