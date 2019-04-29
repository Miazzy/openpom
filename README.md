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
<br/>
系统支持WEB、H5方式浏览，使用webview方式可以发布成小程序。<br/><br/>
<font color="red">本软件为单机版舆情系统，不支持分布式部署。</font>支持window和linux系统。建议部署服务器配置如下：<br/><br/>
<table>
  <tr>
    <td>主要参数</td>
    <td>最低配置</td>
    <td>推荐配置</td>
  </tr>
    <tr>
    <td>CPU</td>
    <td>P4 2.0</td>
    <td>双核2.2以上</td>
  </tr>
    <tr>
    <td>内存</td>
    <td>4G</td>
    <td>8G</td>
  </tr>
    <tr>
    <td>硬盘</td>
    <td>500G</td>
    <td>1T</td>
  </tr>
   <tr>
    <td>带宽</td>
    <td>共享100M或独享4M</td>
    <td>不限</td>
  </tr>
  </table>
  <br/><br/>
  <font color="red">代码有一定复杂度，建议购买的朋友有一定的编程能力</font>，需要演示请联系：<br/><br/>
  QQ:1602752282<br/>
  eMail:marketing@netterfly.com<br/>
  Tel:13405884859
  <br/>
  <br/>
  
如果您对使用有更高要求，比如需要分布式采集、多账号访问、存储数据量更大(千万级以上)，建议考虑<a href="http://www.yuqing008.com" target="_blank">舆情008</a>系统。


