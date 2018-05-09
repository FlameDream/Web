>本文重点描述关于HTML学习的总结

## 前言

### Web标准

Web的基本概念:

Web全称World Wide Web，在维基百科上找到对应关于Web的解释，  
  
 <br/>

	The World Wide Web (abbreviated WWW or the Web) is an information space where documents and other web 
	
	resources are identified by Uniform Resource Locators (URLs), interlinked by hypertext links, and 
	
	accessible via the Internet.（翻译：万维网（简称WWW或万维网）是一个信息空间，文件和其他网络资源由统一资源定位符（URL）
	
	标识，通过超文本链接相互链接，并可通过互联网访问。）
	
<br>	

Web标准介绍：

对于标准和准则的制定，一般都是有一些机构共同协议制定。避免各种不必要的对接和不统一的问题。接下来介绍一下

- w3c：万维网联盟组织，用来制定web标准的机构
- web标准规范的分类：结构标准、表现标准、行为标准
- 结构：HTML  表现：CSS   行为：Javascript

详细介绍一下：

WEB标准不是某一个标准，而是一系列标准的集合。网页主要由三部分组成：结构（Structure）、表现（Presentation）和行为（Behavior）。对应的标准也分三方面：结构化标准语言主要包括XHTML和XML，表现标准语言主要包括CSS，行为标准主要包括对象模型（如W3C DOM）、ECMAScript等

- 结构标准：

	1.可扩展标记

	可扩展标记语言（标准通用标记语言下的一个子集、外语缩写：XML）。和HTML一样，XML同样来源于标准通用标记语言，可扩展标记语言和标准通用标记语言都是能定义其他语言的语言。XML最初设计的目的是弥补HTML的不足，以强大的扩展性满足网络信息发布的需要，后来逐渐用于网络数据的转换和描述。
	
	2.可扩展超文本

	可扩展超文本标识语言（外语全称：The Extensible HyperText Markup Language、外语缩写：XHTML）。目前推荐遵循的是W3C于2000年1月26日推荐XML1.0。XML虽然数据转换能力强大，完全可以替代HTML，但面对成千上万已有的站点，直接采用XML还为时过早。因此，我们在HTML4.0的基础上，用XML的规则对其进行扩展，得到了XHTML。简单的说，建立XHTML的目的就是实现HTML向XML的过渡。

- 表现标准

	层叠样式表（外语缩写：CSS）。目前推荐遵循的是万维网联盟（外语缩写：W3C）于1998年5月12日推荐CSS2。W3C创建CSS标准的目的是以CSS取代HTML表格式布局、帧和其他表现的语言。纯CSS布局与结构式XHTML相结合能帮助设计师分离外观与结构，使站点的访问及维护更加容易。
	
- 行为标准
	
	文档对象模型（外语全称：Document Object Model、外语缩写：DOM）。根据W3C DOM规范，DOM是一种与浏览器，平台，语言的接口，使得你可以访问页面其他的标准组件。简单理解，DOM解决了Netscaped的Javascript和Microsoft的Jscript之间的冲突，给予web设计师和开发者一个标准的方法，让他们来访问他们站点中的数据、脚本和表现层对象。

## 一、HTML的介绍
 HTML全称HyperText Markeup Language,译为超文本标记语言；可以把HTML拆分来理解
 
 	1）超文本：超文本是用超链接的方法，将各种不同空间的文字信息组织在一起的网状文本。
	
	2）标记：不同内容区分，例如：标题、描述、图片、音频、视频、描述等等
	
	3）语言：不能理解，如：C语言、Object-C语言、Swift语言、Java语言、PHP语言、Python语言等
	
**把这些单独的概念统一在一起**

超文本标记语言：使用超级链接的方法将各种不同空间的文字信息使用“标记语言”组织在一起的网状文本
	
***这样把HTML拆分成不同部分理解超文本标记语言，就更加容易理解HTML的本质。为学习HTML奠定较好的基础***


