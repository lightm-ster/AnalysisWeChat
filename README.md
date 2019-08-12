# AnalysisWeChat


![image](https://github.com/lightm-ster/AnalysisWeChat/blob/master/images/echarts.png)
![image](https://github.com/lightm-ster/AnalysisWeChat/blob/master/images/%E5%9C%B0%E5%8C%BA%E7%BB%9F%E8%AE%A1.png)
![image](https://github.com/lightm-ster/AnalysisWeChat/blob/master/images/%E5%BE%AE%E4%BF%A1%E5%A5%BD%E5%8F%8B%E5%9C%B0%E5%9B%BE%E5%8F%AF%E8%A7%86%E5%8C%96.png)
![image](https://github.com/lightm-ster/AnalysisWeChat/blob/master/images/%E6%80%A7%E5%88%AB%E7%BB%9F%E8%AE%A1.png
)

# 依赖
使用python3，请在python3环境下运行

Python 3
PIL: pip3 install pillow
pyecharts：pip3 install pyecharts
pip3 install itchat
pip3 install jieba
地图数据包：
pip3 install echarts-china-provinces-pypkg
pip3 install echarts-countries-pypkg

# 运行
获取用户信息
需要将get_user_info.py第70行的二胖，改成随意一个好友的名字或者自己的名字

python3 get_user_info.py 执行后会在data目录下生成friends.json 会在images目录下存放所有好友的头像

# 统计用户信息
python3 analyse.py 会在analyse文件夹下生产合成后的图片以及可视化的文件

# 教程
本程序作者编写了介绍文档并且录制了相关视频讲解代码，如果有需要的朋友

请添加微信：2697599683
