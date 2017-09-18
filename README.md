# chinese-area-codes
该仓库用于收集整理中国行政区地区码。
起因是之前之前需要使用一个地区选择器，但发现地区码并没有一个标准的格式，不少选择器都使用了陈旧、格式不明的地区码，极易给后续业务升级埋下深坑。

注：台湾省、香港特别行政区和澳门特别行政区暂缺地市和区县信息
数据采集自http://www.mca.gov.cn/article/sj/tjbz/a/
更新时间`2017-09-18`

## 地区码格式
地区结构基本都为省-市-区，地区码结构为6位数字。
如浙江省杭州市西湖区地区码为`330106`，`33`表示省，`01`表示市，`06`表示区。
除此之外存在两种特列，需要特别处理：
 - 直辖市
 - 省级直辖区/县
直辖市为：北京，天津，上海，重庆。
省级直辖区/县第3，4位地区码为`90`，如`469024: 临高县`。


