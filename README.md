# China_Map_Tools
hosts Baidu and Amap tools, including Charging Station Map for Energy Vehicle
利用BaiduMap和Amap的JS API制作的批量地址转坐标、坐标转地址、坐标系间转换（只能从WGS84、GCJ02到BD09，或者WGS84、BD09到GCJ02）

由于JS的回调函数是非堵塞的，里面用了Promise来确保顺序执行。
