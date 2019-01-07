# looking-for-my-house
查找距离指定地点附近的二手房信息及交通路程

python版本：3.6.5
依赖库：bs4；request；pandas

注意：需要在高德地图申请一个web服务api key

输入：
key：高德地图api key
city：所在城市
target_address：目标地经纬度，逗号分隔
room：房型，2为两室
size：住房面积大小
3为70-90平米
price_limit:价格上限

输出：
house_info{}.xlsx 全上海所有二手房信息，包括单价、总价、描述、位置、到目标地点的交通露出
select_house_info{}.xlsx 到目标地点90分钟内的房源，按总价降序排列
