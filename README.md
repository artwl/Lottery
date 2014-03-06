Lottery
=======
一个刮奖小程序，可以在移动设备上和PC端网页（浏览器要支持canvas）上运行

can run in handheld device and pc-web(need support canvas)

##使用说明


    var lottery = new Lottery(id, cover, coverType, width, height, drawPercentCallback);
    
    lottery.init(lottery,lotteryType);
    
    function drawPercentCallback(percent) {
        //some code here
    }

##构造方法参数解释

`id`:刮奖容器，必须

`cover`:涂层内容，可以为图片地址或颜色值，可空，默认为 #ccc

`coverType`:涂层类型，值为 image 或 color，可空，默认为 color

`width`:刮奖区域宽度，默认为300px，可空

`height`:刮奖区域高度，默认为100px，可空

`drawPercentCallback`:刮开的区域百分比，可空

##init方法解释

`lottery`:刮开后显示的内容，可以为图片地址或字符串，必须

`lotteryType`:刮开后显示的内容类型，值为 image 或 text，要跟`lottery`匹配，默认为 image


##DEMO

[http://jsfiddle.net/artwl/L6D63/10/embedded/result,js,html,css/](http://jsfiddle.net/artwl/L6D63/10/embedded/result,js,html,css/)

