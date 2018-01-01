---
title: 信息可视化F组期中专案<--
date: 2017-12-31 17:49:20 +0300
description: 城乡收入差距与相关因素研究
bg: "infovis.jpg"
date: 2017-12-29
tags: "infovis"
categories:
  - infovis
---


### 课题介绍：城乡收入差距与相关因素研究
##### 摘取四个相关因素：人力资本因素、产业结构因素、城市化水因素、经济水平因素；
###### 数据来源：国家数据
* 研究结果：
* 人力资本因素、产业结构因素、城市化水因素与泰尔指数均达到显著关系。
* 经济水平因素没有达到显著。




* 协调城乡收入差距应该（1） 把握城市化发展契机。城市化主要通过农业经济结构升级，对城乡收人差距产生影响 。（2） 重视农村人力资本发展。培养高水平人才，激励人才回乡发展。 从而缩小区域间 的 城乡 收人差距。



<html lang="en">
<head>
	<meta charset="utf-8">
	<title>example</title>
	<meta name="viewport" content="width=device-width">
	<link rel="stylesheet" href="/infovis/tableau/tabstyles.css">
</head>
<body>
	<div class="CenterMe">
		<h1>城乡收入差距</h1>
	</div>
<h1>城乡收入差距与相关因素研究</h1>
		<div class="tab_container">
			<input id="tab1" type="radio" name="tabs">
			<input id="tab2" type="radio" name="tabs">
			<input id="tab3" type="radio" name="tabs">
			<input id="tab4" type="radio" name="tabs">
			<input id="tab5" type="radio" name="tabs">
			<input id="tab6" type="radio" name="tabs">
			<input id="tab7" type="radio" name="tabs">
    <div class="tab_label_flex_container">
			<label for="tab1" id="tab1"><i class="fa fa-code"></i><span>城乡收入差距</span></label>      
			<label for="tab2" id="tab2"><i class="fa fa-pencil-square-o"></i><span>泰尔指数</span></label>
			<label for="tab3" id="tab3"><i class="fa fa-bar-chart-o"></i><span>因素1</span></label>
			<label for="tab4" id="tab4"><i class="fa fa-folder-open-o"></i><span>因素2</span></label>
			<label for="tab5" id="tab5"><i class="fa fa-envelope-o"></i><span>因素3</span></label>
			<label for="tab6" id="tab5"><i class="fa fa-envelope-o"></i><span>因素4</span></label>
			<label for="tab7" id="tab5"><i class="fa fa-envelope-o"></i><span>结论</span></label>

      </div>
      
			<section id="content2" class="tab-content">
				<p>泰尔指数：作为衡量群体、个体或区域之间的城乡收入差距的指标。泰尔指数越大说明城乡收入差距越大。</p>
				<p>三大区域不仅各自的 城乡 收 人差距在缩 小 ， 而且 区 域间 的 城乡 收人差 距也在缩小。
				各但是，区域的泰尔指 数序列 既具有与全国趋同 的整体发展趋势 ，但是 又有 自 身 的特 点 。 本小组将通过例举四种城乡收人差距的因素 ： 
				 经济因 素 、 城市化因 素 、 产业结构因素和人力资本因素 。
				考察其对城乡收入差距的影响程度。</p>

				<iframe src="https://public.tableau.com/views/_16012/sheet8?:embed=y&:display_count=yes&publish=yesDashboard1?:showVizHome=no&:embed=true" width="1316" height="860"></iframe>

			</section>

			<section id="content3" class="tab-content">
				<p>1.经济因素 ： 选用国内生产总值来代表经济因素 。
				<br>由经济增长率图中可以看到，东西部城市经济增长率起伏较大，在11年之后增长率均呈下降趋势。经济增速放缓。
				在经济水平中，各省生产总值均逐年上升，其中广东省生产总值最高，西藏自治区生产总值最低。
				东西部之间的省份生产总值差距较大，中部省份较为平均。
					<br>
				在经济水平与泰尔指数之间的关系中，P值0.0107984，大于0.05，不呈相关关系，所以生产总值越高的省份泰尔指数不一定低或越高。
				</p>
				<iframe src="https://public.tableau.com/views/4_478/sheet2_1?:embed=y&:display_count=yes&publish=yesDashboard1?:showVizHome=no&:embed=true" width="1316" height="860"></iframe>

			</section>

			<section id="content4" class="tab-content">
				<p>2.城市化因素 ： 借鉴万广华（ 2 0 1 3 ） 研究城镇化与 不均等 之间 关 系 时， 对 城镇化选用城 乡 人 口 比作为考察指标 。
				<br>可以看到多数省份城市化水平在平均线以下，且仅有东部省份具有高城市化水平，在高城市化之间的城市差距也非常的大。
				由城市化水平与泰尔指数的散点图可以看到，城市化水平越高，泰尔指数越小。其趋势线的P值<.0001 ，达到显著，由此可知二者具有相关关系。</p>
				<iframe src="https://public.tableau.com/views/_16012/sheet10?:embed=y&:display_count=yes&publish=yesDashboard1?:showVizHome=no&:embed=true" width="1316" height="860"></iframe>
			</section>

			<section id="content5" class="tab-content">
				<p>3.产业结构情况： 农产业发展水平 城市非农产业产值占总产值比重。
				生产总值中，西部地区的农业结构占比最大，其中新疆维吾尔族自治区占比最大，是0.2165，东部地区农业结构占比较小，其中，占比最小的为上海仅有0.0089.
				农业生产结构占比越大的城市，其泰尔指数越高。其P值为.0002991，达到显著。</p>
				<iframe src="https://public.tableau.com/views/4_478/sheet6?:embed=y&:display_count=yes&publish=yesDashboard1?:showVizHome=no&:embed=true"width="1316" height="760" ></iframe>
			</section>

			<section id="content6" class="tab-content">
				<p>4.人力资本因素 ： 郭建雄（ 2 0 0 5 ） 认为 ， 人力资本的城乡差异 ， 意味着生产函数中的单位劳动在城乡部门具有不同的产出效率 ， 
				且个人每度受一 年在校教育 ， 一般能使今后的工资 增长 1 0 ％ ， 因 此 ， 本文选取每万人 中在校大学生数作为区域人力资本因素的代表性指标
				东部的北京的受教育人数是最多的达到了46.619K，而青海的人数最少仅有9.104K，二者之比达到5倍之多。其余多数城市也为达到平均线。
				在受教育人数与泰尔指数的散点图中，受高等教育人数越多的城市，泰尔指数越低，如北京上海。
				<br>其P值<.0001 达到显著，二者成相关关系。</p>
				<iframe src="https://public.tableau.com/views/_16012/sheet7?:embed=y&:display_count=yes&publish=yes&publish=yesDashboard1?:showVizHome=no&:embed=true"width="1316" height="760" ></iframe>

			</section>
			<section id="content1" class="tab-content">
				<p>城乡收入差距：
			城乡收入都是成正增长，在2004年，农村收入增长率一直高于城市收入，在2010年被短暂反超之后，2012年农村收入
			增长高于城市，但两者，增长率开始放缓。
			<br>
			由该表得知，虽然农村收入增长率在多数年间高于城市收入增长率，但是城乡收入差距还在不断增大。</p>
				<iframe src="http://public.tableau.com/views/_15747/1?:embed=y&:display_count=yes&publish=yesDashboard1?:showVizHome=no&:embed=true" width="1316" height="760"></iframe>

			</section>
			<section id="content7" class="tab-content">
				<p>在四个因素中，人力资本因素、产业结构因素、城市化水因素与泰尔指数均达到显著关系。而经济水平因素没有达到显著。因此
				：<br>协调城乡收入差距应该（1） 把握城市化发展契机。城市化主要通过农业经济结构升级，对城乡收人差距产生影响 。<br>
				（2） 重视农村人力资本发展。培养高水平人才，激励人才回乡发展。 从而缩小区域间 的 城乡 收人差距</p>

			</section>
		</div>

<p class="no_wrap">
  And Of-course this paragrapgh with not wrap Tab
</p>

<p class="link">
  Just in case you want to go through the tutorial follow this link: <a href="http://www.sevensignature.com/blog/code/responsive-pure-css-tabs/">Responsive Pure CSS Tabs</a>
</p>