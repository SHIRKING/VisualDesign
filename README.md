# Interactive_Visual_201908可视化项目报告

|主题|中国博物馆分析|
|---|---|
|第一责任人|SHIRKING|
|联系方式|SHIRKING-LXY（微信）|
|最终成果展示|[pythonanywhere](http://shirkingliang.pythonanywhere.com/)|
|gitee|[链接](https://gitee.com/NFUNM045/interactive_visualization/blob/master/README.md)|

## 一、计划阶段

**基本范围：公共文化研究**

|预案|内容|相关资料|
|---|---|---|
|方案一|通过博物馆相关数据了解各地区文化底蕴，及不同地区文化吸引力。|[国家数据-分省年度-文化](http://data.stats.gov.cn/easyquery.htm?cn=E0103)|
|方案二|通过图书馆地区分布了解各地区基础文化建设情况。|同上|
|方案三|通过对胡润榜数据可视化了解中国品牌的地区分布情况。|[汇桔网·2019胡润品牌榜](http://www.hurun.net/CN/Article/Details?num=6F31B786AD94)


**最终决定**
结合方案一、方案二的提议，通过对博物馆机构数、博物馆收藏品、博物馆从业人员、博物馆参观者、GDP与博物馆的关系分析、人口数与博物馆的相关分析、博物馆收藏品与图书馆藏书量相关分析、各地公共文化财政支出与博物馆相关关系分析、各地文化体育与传媒财政支出相关关系分析、中国各地图书馆数量与博物馆数量相关分析和人均可支配收入与博物馆的相关联系进行可视化，了解中国博物馆如今的现状，加深对中国各地博物馆大局观上的认识。


## 二、实现

[中国博物馆分析](http://shirkingliang.pythonanywhere.com/)

[如果不行点这个](http://hanxingting.pythonanywhere.com)

## 三、数据故事

### 综述

通过观察交互图里面的内容，我们可以看见，近几年中国博物馆的数量呈现激增的趋势，在区域分布上东多西少的局面和我们的基础印象基本一致，国家财政支持对于博物馆起着不小的影响，但并不是决定性因素。经济水平、人们的人均可支配收入与博物馆之间也存在着一些相关关系。在与公共图书馆的对比中我们也可以看见，博物馆数量的多寡、分布和公共图书馆也存在一定量的联系。

![图5](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/p2.png)

### BaseQuantity 博物馆机构数

从这两页的数据我们可以看出近八年间，山东、河南、浙江、陕西、四川等地的博物馆机构数激增。尤其是山东省从2010年的114个狂涨到2018年的517个。从地图上看，2018年，我国博物馆机构主要集中于黄河中下游、长江下游地区。和中国文明发展的方向基本一致，历史发展比较久远且兴盛的地区能够出现更多博物馆机构。同时我们可以看见马太效应在这其中也有一定的显现，原本博物馆数量较多的地区博物馆增长量要比原本博物馆数量较少的地区要多很多，山东就是其中一个例子。

![图1](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/BQ1.png)

![图2](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/BQ2.png)

### Collection 博物馆收藏品

我国主要的博物馆收藏品分布在山东、陕西、四川三个大省，并明显呈现出东多西少的区域分布状况。这和我们对博物馆的原有印象也基本一致。但是经济发达的地区不一定是博物馆发展最多的，当然，也一定的存在有博物馆的资源集中化的现象。就像北京，绝大多数的资源都集中到了故宫博物馆以及国家博物馆中。

![图3](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/coll.png)

### Practitioner 博物馆从业人员

陕西作为旅游胜地，博物馆规模大，从业人员多是可想而知的。其次，江苏地区有大量参观者进入，也容易催生一大批从业人员。但从这里我们可以发现，从业人员的多寡与该地区机构数的多少并不是相互呼应的。同时，和博物馆的参观人数对比也可以看见两者的峰值都出现在不同的位置。这和各地区博物馆的知名度、旅游人数、单个博物馆的机构大小也有一定的关系。

![图4](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/p.png)

### Visitors 博物馆参观人数

结合我们之前学到的地理知识，我们观察到一个现象：在经济发达地区附近的比较郊区的地区会有比较多的参观者，尤其是观察长江三角洲地区。另外，历史文化底蕴丰富的陕西也是参观者众多的地区。兵马俑、古长安皆在此地。

![图6](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/v.png)

### GDP 生产总值 & Population 人口 & DisposableIncomePerCapita 人均可支配收入

从经济的角度来看，结合我们之前学到的地理知识，我们观察到一个现象：在经济发达地区附近的比较郊区的地区会有比较多的参观者，尤其是观察长江三角洲地区。另外，历史文化底蕴丰富的陕西也是参观者众多的地区。兵马俑、古长安皆在此地。同时我们也可以知道，经济对于博物馆而言影响并没有我们想象中的大，不能完全成为决定性影响。博物馆的发展是一个天时地利人和的结果，该地区原有的历史文化底蕴、时代经历在这其中有着很重要的地位。

结合我们之前学到的地理知识，我们观察到一个现象：在经济发达地区附近的比较郊区的地区会有比较多的参观者，尤其是观察长江三角洲地区。另外，历史文化底蕴丰富的陕西也是参观者众多的地区。兵马俑、古长安皆在此地。

结合我们之前学到的地理知识，我们观察到一个现象：在经济发达地区附近的比较郊区的地区会有比较多的参观者，尤其是观察长江三角洲地区。另外，历史文化底蕴丰富的陕西也是参观者众多的地区。兵马俑、古长安皆在此地。人们可支配收入的提升也会提高人们对于精神文化的追求，提高人们对于公共文化服务的重视程度。


![图7](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/GDP.png)

![图8](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/dipc.png)

### NumberOfLibraryInstitutions 图书馆 & BookCollection 图书馆藏书量

结合两个数据对比可以看见，书籍收藏分布与博物馆收藏分布之间还是有不少的重合点。可以看见，江苏、山东、四川、河南、上海等地对于公共文化服务的重视程度是比较高的。

![图9](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/book.png)

![图10](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/li.png)

### PublicCulturalFinance 公共服务财政支出 & CultureSportsMediaFinance 文化体育与传媒财政支出

再从国家对文化支持来看，我们选取了公共服务财政支出和文化体育与传媒财政支出来进行分析。

从公共服务财政支出相关图中可以看出 广东省在对于公共服务及文化输出的财政投入最大，博物馆机构数最多的山东省的投入反倒没有那么突出。从这两个图的对比我们可以充分明白，经济投入与博物馆机构建设数量之间相关性并不强，但投入较少的海南、青海、宁夏等地博物馆机构数确实比较少，这里倒是显示出一致性。
                                    
从文化体育与传媒财政支出相关图中可以看出 广东省在对于公共服务及文化输出的财政投入最大，博物馆机构数最多的山东省的投入反倒没有那么突出。从这两个图的对比我们可以充分明白，经济投入与博物馆机构建设数量之间相关性并不强，但投入较少的海南、青海、宁夏等地博物馆机构数确实比较少。

![图11](https://github.com/SHIRKING/VisualDesign/blob/master/pictures/f.png)
