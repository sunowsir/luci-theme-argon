# luci-theme-argon
> 尊重开源，尊重原作，forked from jerrykuku/luci-theme-argon
* 跟原版相比：
    1. 将管理界面的白色背景改为图片，与登录页背景一致
    2. 调整部分样式，使其在半透明背景下更和谐
    3. 去除wallhaven，新增pexels、picsum
    4. 新增配置项如下：
        * `get_timeout`: 网络连接超时，单位秒，默认30秒，例如下载图片、获取图片地址列表等需要使用curl的时候，增加的`--max-timeout`参数
        * `reso_x`和`reso_x`: 图片分辨率，下载图片时，会增加分辨率参数，若不支持则会按照该分辨率进行筛选，默认2560x1440
* 截图：
    ![screenshot](./screenshot.png)
    ![screenshot](./screenshot1.png)
    ![screenshot](./screenshot2.png)
    ![screenshot](./screenshot3.png)
    ![screenshot](./screenshot4.png)
