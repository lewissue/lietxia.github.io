## 电脑端随意，但iOS最好用Safari，Android最好用Firefox，这2个肯定可以，不少手机浏览器禁止书签脚本

## 第一步，随便收藏一个网站到书签，再编辑这个书签，名称随便写，地址写下方

    javascript:void((function(){var e=document.createElement('script');e.setAttribute('src','https://lietxia.github.io/res/loop.js');document.body.appendChild(e);})());

![](res/p1.png)

## 第二步，进入雀魂大会室管理页

![](res/p2.png)

点开书签即可(如果是Firefox，点开地址栏，再切换到书签，再点开就能执行)

底部出现绿色工具栏，脚本就成功了

执行方法：点击绿色工具栏的按钮即可，满4人他自动开始

备注：浏览器关闭则脚本停止，自动执行必须要有设备开着浏览器  

脚本执行的是：每10秒检查一次在线人数，如果大于3人则让最上方的4人随机坐次+初始分数 开赛

脚本如果快速操作，雀魂后台只对第一个操作做反应，只能执行一个，等一秒，再执行一个……特别蛋疼  

为了防止脚本失效，他每10秒会切到其它页面，再切回来，来刷新元素

脚本详细的流程：→切回首页→切回开始页→检查人数→大于等于4则开始→切首页→切开始页→检查人数