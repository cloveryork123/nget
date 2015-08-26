# 缘起

老家的房子很久才回去住一次，所以没有安装宽带网络。不过有一个硕大的、画面很好的、声音很震撼的电视。

特别爱看《晓松奇谈》、《鸿观》什么的。

自己动手丰衣足食吧。于是搞了这么一个玩意：

1. 给出网页地址。

2. 下载到本地。

3. 通过ffmpeg转码为电视肯定能看的mov格式。

# 运行

```npm start```

# 要求

1. nodejs 版本在0.11以后的均可，因为使用了一些ES6原生的Promise，所以要求支持启动的```--harmony```参数
2. 需要安装ffmpeg视频转码库。


# 感谢
部分思路，借鉴自python3编写的同类项目 https://github.com/soimort/you-get

