# cursor限制国内使用claude 解决方法

提示：
Model not available
This model provider doesn't serve your region. Visit https://docs.cursor.com/account/regions for more information.

cursor限制中国地区使用 ，要使用必须设置代理


### 1. 设置clash，开tun（虚拟网卡模式）选规则模式 或 全局规则模式
clash下载
https://github.com/clash-verge-rev/clash-verge-rev/releases/tag/v2.3.1

没梯子的推荐这个，便宜稳定，几块钱一个月
[ https://xn--h5qy75o.com/index.html?register=MJ8s74oD](https://xn--h5qy75o.com/index.html?register=MJ8s74oD) 

![202507161426877.png](<202507161426877.png>)

### 2. cursor里面设置代理
文件-首选项-设置-应用程序-代理服务器 http://127.0.0.1:7897 （7897为自己梯子端口）

![20250716142555.png](<20250716142555.png>)


- 注意检查看看节点是否正常
- 如果以上还不行，打开设置（Ctrl+Shift+J）选择Network将来HTTP Compatibility Mode改成1.1或1.0试一下
  
### 如果还不行，先用auto

