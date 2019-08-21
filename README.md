# China_Map_Tools
hosts Baidu and Amap tools, including Charging Station Map for Energy Vehicle

利用BaiduMap和Amap的JS API制作的批量地址转坐标、坐标转地址、坐标系间转换
  （只能从WGS84、GCJ02到BD09，或者WGS84、BD09到GCJ02）

由于JS的`回调函数`是`非堵塞`的，里面用了`Promise`来确保顺序执行。

**演示:**

[高德地图坐标系转换](https://st-ral.cn/AMap_Geo2Address.html "全国新能源车充电站地图")

[百度地图坐标系转换](https://st-ral.cn/BMap_Geo2Address.html "全国新能源车充电站地图")
