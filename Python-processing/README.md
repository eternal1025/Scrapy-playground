# 数据清洗
数据路径为 ../data/Item.db 
python数据清洗，用高德地图的api（需要自己申请Key）获取城市以及具体每一条的招聘信息的经纬读，同时统计每个城市总的招聘信息。  
注意国内地图软件获取的经纬度与国际标准不同，所谓的“火星坐标”，需要进一步转换成国际标准。坐标转换api地址：http://api.zdoz.net/transgps.aspx?
