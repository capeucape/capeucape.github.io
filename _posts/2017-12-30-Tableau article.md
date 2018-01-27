---
layout: article
title:  "Tableau 中的映射（map）"
date:   2018-01-01 22:07:50 +0800
categories: infovis 
image:
  teaser: timgg.png
  feature: tableau article.png
---


# Tableau 中的映射

如果要按地理位置分析数据，则可以在 Tableau 中的地图上绘制数据。本主题解释了为什么以及何时应将数据放在地图可视化项上。它还介绍了您可以在 Tableau 中创建的一些地图类型，以及指向演示如何创建每种地图的主题的链接。
如果您不熟悉 Tableau 中的地图，那么这是开始学习的好地方。
## 本文内容
> 为何将数据放在地图上？  
> 应在何时使用地图表示数据？  
> 可在 Tableau 中构建什么类型的地图？   

## 为何将数据放在地图上？
将您的数据放在地图上有很多原因。也许您的数据源中有一些位置数据？或者也许您认为地图真的可以让您的数据很受欢迎？这两个都是创建地图可视化项的足够好的理由，但一定要记住，地图像任何其他类型的可视化项一样有特定用途：它们可以回答空间问题。
您在 Tableau 中制作地图是因为您有空间问题，您需要使用地图来了解数据中的趋势或模式。
但什么是空间问题呢？下面可能是一些例子：
- 哪个州/省/市/自治区的农贸市场最多？
- 美国的肥胖率高发区在哪里？
- 我所在城市的每条地铁线路中哪个地铁站是最繁忙的地铁站？
- 风暴随着时间的推移往哪里移动？
- 人们按照当地的自行车共享计划在哪里借出和归还自行车？

所有这些都是空间问题。但是，地图是回答它们的最好方式吗？  
## 应在何时使用地图表示数据？
如果您有空间问题，那么地图视图可能是回答此问题的好方法。然而，情况可能并不总是这样。
例如，上面列表中的第一个问题：哪个州/省/市/自治区的农贸市场最多？
如果您有一个数据源，其中包含每个州/省/市/自治区的农贸市场列表，则可以创建一个地图视图，如下所示。您能轻易地说出纽约和加利福尼亚的区别吗？哪一个有更多农贸市场？

![图1](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/Img/maps_build3.1.png)

如果您改为创建条形图将会怎样？现在是不是很容易发现具有最多农贸市场的州/省/市/自治区？

![图2](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/Img/maps_build4.1.png)

上述示例是不同类型的可视化项能够比地图更好地回答空间问题的多种情况之一。
所以您什么时候知道是否应该使用地图视图？
一个经验法则是问自己是否可以更快地回答您的问题，或者使用另一个可视化项是否更轻松。如果答案是肯定的，那么或许地图视图不是您要使用的数据的最佳可视化项。如果答案是否定的，请考虑以下因素：
回答问题的地图既具有适当的数据表示形式，又具有吸引人的数据表示形式。换句话说：数据没有误导性，地图很吸引人。
如果您的地图很漂亮，但数据具有误导性，或者不够深入，那么您就会面临人们误解您的数据的风险。这就是为什么创建准确且诱人地表示数据的地图很重要的原因。
## 可在 Tableau 中构建什么类型的地图？

使用 Tableau，您可以创建以下通用地图类型：
### 比例符号地图
比例符号地图非常适合显示各个位置的定量数据。例如，您可以标绘世界各地的地震，并按震级来确定它们的大小。
有关比例符号地图的详细信息，以及若要了解如何在 Tableau 中创建这些地图，请参见[在 Tableau 中创建显示定量值的地图。](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/maps_howto_symbol.html)  
![比例符号地图](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/Img/maps_symbol6.png)

### 面量图（填充地图）
面量图在 Tableau 中也称为填充地图，非常适合显示比例数据。例如，如果您想看一看美国每个县的肥胖率，则可以考虑创建一个面量图，看看您是否可以发现任何空间趋势。
有关面量图的详细信息，以及若要了解如何在 Tableau 中创建这些地图，请参见[在 Tableau 中创建显示比例或聚合数据的地图。](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/maps_howto_choropleth.html)  
![面量图](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/Img/choropleth_maps1.png)

### 点分布图
当您要显示近似位置并且要寻找可视数据群集时，可以使用点分布图。例如，如果您想查看去年美国所有冰雹的发生地，则您可以创建一个点分布图，看看是否可以发现任何群集。
有关点分布图的详细信息，以及若要了解如何创建它们，请参见[在 Tableau 中创建突出显示可视数据群集的地图。](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/maps_howto_pointdistribution.html)  
![点分布图](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/Img/maps_build7.png)

### 流线图（路径图）
您可以使用流线图连接地图上的路径，并查看随时间发生的事件的地点。例如，您可以跟踪一段时间内世界各地的主要风暴的路径。
有关流线图的详细信息，以及若要了解如何在 Tableau 中创建这些地图，请参见[在 Tableau 中创建显示随时间变化的路径的地图。](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/maps_howto_flow.html)  
![流线图](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/Img/maps_build8.png)

### 蜘蛛图（起点-终点图）
您可以使用蜘蛛图来显示起点位置和一个或多个终点位置的交互方式。例如，您可以连接地铁站之间的路径以在图上绘制路径，或者可以跟踪从起点到一个或多个终点的自行车共享车道。
有关蜘蛛图的详细信息，以及若要了解如何在 Tableau 中创建这些图，请参见[在 Tableau 中创建显示起点和终点之间的路径的地图 。](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/maps_howto_origin_destination.html)  
![蜘蛛图](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/Img/maps_build9.png)

> 来源：[https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/help.html#maps_build.html#Why](https://onlinehelp.tableau.com/current/pro/desktop/zh-cn/help.html#maps_build.html#Why)
