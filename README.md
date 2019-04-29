# OpenPom单机版舆情监控软件源码

系统使用struts+spring+hibernate框架开发，相关技术包括：redis,lucene,jms,nutch,rpc等。<br/><br/>
支持搜索引擎搜索结果、网站、论坛、博客、微博、微信公众号文章采集，支持电子邮箱、QQ聊天、微信记录监控。<br/><br/>
搜索结果自动规则化解析，提取文章标题、内容、发布时间、作者，自动生成摘要、关键词信息。自动聚类，判断文章正负面属性。<br/><br/>
整个系统分为前台与后台，前后台主要功能如下：<br/><br/>
后台管理：<br/>
<ul>
  <li>添加目标检测站点</li>
  <li>添加全网监控词</li>
  <li>添加过滤词</li>
  <li>添加微博监控词</li>
  <li>设置监测分类词</li>
  <li>设置负面词</li>
  <li>设置预警词</li>
  <li>设置预警发送邮箱</li>
  <li>设置前台用户信息</li>
  <li>设置简报生成规则</li>
  <li>控制系统采集进程</li>
  <li>采集结果管理</li>
  <li>采集数据统计分析</li>
  <li>其他功能......</li>
</ul>
<br/>
前台网站：<br/>
<ul>
  <li>门户首页(趋势图|最新舆情|最新负面|分类舆情|预警舆情)</li>
  <li>舆情汇总</li>
  <li>统计分析</li>
  <li>负面舆情</li>
  <li>微博舆情</li>
  <li>QQ舆情</li>
  <li>舆情简报</li>
  <li>我的舆情(我的关注|预警舆情)</li>
</ul>




