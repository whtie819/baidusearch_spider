# baidusearch_spider
🐊//   百度搜索爬虫，爬取百度搜索结果<br/><br/>
一个小脚本而已，主要爬取主站首页url<br/><BR/>
geturl('XX XX 首页')  //这里填写关键字，支持多个关键字搜索<br/>
建议采用三个关键字搜索，保证搜索结果准确性<br/><BR/>
eg.geturl('北京 公司 首页')<br/><BR/>
爬虫结果自动导出为result.txt<br/>
格式：url+title<br/>
eg.http://www.baidu.com 百度一下，你就知道<br/><BR/>
for page in range(10):   //这里修改爬取搜索结果页数<br/>
