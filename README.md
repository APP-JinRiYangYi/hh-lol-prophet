# lol 对局先知

qq 群: 102158075
[下载地址](https://lol.buffge.com)
流程:
    监控lol client
    ->
    存在开始监听游戏事件
    不存在关闭游戏事件监视器
    # 游戏事件监听器
    if 英雄选择->
    进入分析程序

分析程序:
    获取队伍所有用户信息
    查询所有用户的信息并计算得分
    根据所有用户的分数判断小代上等马中等马下等马
    发送到选人界面

plan:
  sentry
  优化算法
    > 根据对位数据差 计分
  服务端
  gui
  优化lol.buffge.com网站
  单例检测(禁止重复运行)
  限制请求速率


    