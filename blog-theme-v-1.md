theme: BlueFresh

```css

:root{
    /* 1 */
    /* --theme-color: #172532; */
    /* 2 */
    /* --theme-color: #505a68; */
    /* 3 */
    /* --theme-color: #766865; */
    /* 4 */
    /* --theme-color: #7cb6e6; */
    /* 5 */
    /* --theme-color: #6d7a83; */
    /* 6 */
    /* --theme-color: #426ba3; */
    /* 7 */
    --theme-color: #4068a0;
    --light-bg-color: rgba(255,255,255,.6);
    --light-header-color: rgba(255,255,255,1);
    --light-text-color:  rgba(0,0,0,1);
    --dark-bg-color: rgba(0,0,0,.6);
    --dark-header-color: #000;
    --dark-text-color: #fff;
}
@keyframes avatarAnimate{
    from {transform: rotate(0deg);}
    to {transform: rotate(360deg);}
}
/* 滚动条 */
::-webkit-scrollbar {
  width: 5px;
  height: 5px;
  background: #ffffff88;
  border-radius: 5px;
  border: none;
  outline: none;
}

/* 滚动条两端按钮 */
::-webkit-scrollbar-button {
  width: 0;
  height: 0;
}

/* 外层轨道 */
::-webkit-scrollbar-track {
  border-radius: 5px;
  border: none;
  outline: none;
}

/* 内层轨道，它会覆盖外层轨道的样式 */
::-webkit-scrollbar-track-piece {
  width: 4px;
  margin: 0 -2px 0;
  border: none;
  outline: none;
}

/* 滑块 */
::-webkit-scrollbar-thumb {
  background-color: var(--theme-color);
  min-height: 60px;
  min-width: 60px;
  border-radius: 5px;
}

/* 纵向滑块悬浮 */
::-webkit-scrollbar-thumb:vertical:hover {
  background-color: var(--theme-color);
}

/* 横向滑块悬浮 */
::-webkit-scrollbar-thumb:horizontal:hover {
  background-color: var(--theme-color);
}

canvas#live2dcanvas {border: 0 !important;right: 0;}
body{
    width: 100%;
    height: 100%;
    margin: 0;
    /* background-image: url('https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180458532.jpg'); */
    /* background-image: url('https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180500155.jpg'); */
    /* background-image: url('https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180500043.jpg'); */
    /* background-image: url('https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180459041.jpg'); */
    /* background-image: url('https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180500224.jpg'); */
    background-image: url('https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180842296.jpg');
    /* background-image: url('https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180850197.jpg'); */
    background-size: 100% auto;
    background-position: top left;
    background-repeat: no-repeat;
    background-color: var(--theme-color);
    background-attachment:fixed;
}
a:hover , .postTitle a:hover{color: var(--theme-color);text-decoration: none;text-shadow: 0px 1px 2px var(--theme-color);}
input:focus-visible{outline: none;cursor: pointer;}
#home{width: 100%;max-width: 100%;}
#header{margin-top: 0;display: flex;justify-content: space-between;/*height: 60vh;*/}
#blogTitle{padding: 30px;}
#blogTitle h1 a, #blogTitle h2{color: var(--light-header-color);text-shadow: 0px 0px 0px transparent;font-size: 20px;}
#navigator{margin-top: 0;background-color: transparent;}
#navList a{padding: 30px 5px 5px 5px;font-size: 17px;font-weight: 100;margin: 15px 20px;}
#navList a:link, #navList a:visited, #navList a:active{text-shadow: 3px 3px 3px var(--light-header-color);}
#navList a:hover{border-bottom: 1px solid var(--light-header-color);transition: all 2s ease;text-decoration: none;}
#main{max-width: 1400px;margin: 0 auto;padding: 20px 0;background-color: var(--light-bg-color);border-radius: 10px;}
#mainContent{width: 1100px;background-color: transparent;}
#sideBar{padding: 0 15px 0 10px;}
.postTitle{border-left: 5px solid var(--theme-color);}
.postDesc{color: var(--theme-color);}
div#blog-calendar , #sidebar_scorerank {margin-bottom: 20px;}
#sidebar_news h3 , .catListEssay h3, .catListLink h3, .catListNoteBook h3, .catListTag h3, .catListPostCategory h3, .catListPostArchive h3, .catListArticleArchive h3, .catListImageCategory h3, .mySearch h3, .catListComment h3, .catListView h3, .catListFeedback h3, #blog-sidecolumn .catListTitle{
    background: var(--theme-color);
    border-bottom: none;
    border: none;
    color: #fcfcfc;
    margin: 0;
    font-weight: 300;
}
#sidebar_news , #blog-calendar , #sidebar_scorerank , .catListEssay, .catListLink, .catListNoteBook, .catListTag, .catListPostCategory, .catListPostArchive, .catListArticleArchive, .catListImageCategory, .mySearch, .catListComment, .catListView, .catListFeedback, #blog-sidecolumn .catListTitle{
    border: 1px solid var(--theme-color);
}
table#blogCalendar th, table#blogCalendar td {
    color: #152532;
}
td.CalNextPrev {
    padding: 0 5px;
}
td[colspan="7"] , table#blogCalendar .CalTitle td , table#blogCalendar .CalTitle td a , table#blogCalendar .CalTodayDay {
    color: #f1f1f1;
    background-color: var(--theme-color);
}
.mySearch .input_my_zzk{width: 100%;}
.div_my_zzk {
    height: 30px;
    margin: 10px auto;
    width: 100%;
    display: flex;
}
div#nav_next_page , div#sidebar_search_box input[type="button"] {
    background-color: var(--theme-color);
    color: #f1f1f1;
    padding: 0 10px;
    border-radius: 4px;
    margin-right: 10px;
}
div#sidebar_search_box input {
    background-color: transparent;
    border: none;
    border-bottom: 1px solid var(--theme-color);
    margin-left: 10px;
    height: 2em;
}
div#nav_next_page {display: inline-block;}
div#nav_next_page a{color: #f1f1f1;line-height: 30px;}
div#nav_next_page a:after {content: '>>>';color: #f1f1f1;}
#footer{color: #c6c5c5;font-size: 12px;}
div[id*="ad"] {display: none;}
.under-post-card {display: none;}
div#sidebar_postcategory ul {
    display: flex;
    flex-wrap: wrap;
}
div#sidebar_postcategory ul li {
    border: 1px solid var(--theme-color);
    padding: 3px 8px;
}
.author_avatar{border-radius: 50%;margin-right: 20px;}
.author_avatar:hover{animation: avatarAnimate 0.8s linear infinite;transition: all 1s ease;}
@media screen and (max-width: 1400px){
    #header{height: 40vh;}
    #sideBar{display: none;}
    #main{min-width: 100%;}
    #mainContent{width: 100%;min-width: 100%;}
}

@media screen and (max-width: 700px){
    #navList a{margin: 15px 5px;}

}

@media screen and (max-width: 500px){
    #header{flex-direction: column;height: 28vh;}
    #blogTitle{padding: 30px 5px;}
    #navigator{height: 40px;}
    #navList a{margin: 0 5px;padding: 0 5px;}
}

@media screen and (max-width: 400px){
    #header{height: 25vh;}
}

@media screen and (max-width: 300px){
    #header{height: 23vh;}
}
```

```html
<script type="text/javascript" charset="utf-8" async=""
        src="https://cdn.jsdelivr.net/npm/live2d-widget@3.0.4/lib/L2Dwidget.min.js"></script>
<!-- 右下角live2d效果 -->
<script type="text/javascript">
        setTimeout(()=>{
        L2Dwidget.init({
                "model": {
                        "scale": 0.5  //#模型与canvas的缩放
                        // hHeadPos: 0.5	#模型头部横坐标
                        // vHeadPos: 0.618	#模型头部纵坐标
                },
                "display": {
                        // "superSample": 2	//超采样等级
                        "width": 100,   //画布的宽度，显示模型画布的长度
                        "height": 180,  //画布高度显示模型画布的高度
                        "position": "right",	//显示位置：左或右
                        "hOffset": 0,    //水平偏移
                        "vOffset": -20   //垂直偏移
                },
                "mobile": {
                        "show": false,  //是否在移动设备上显示
                        "scale": 0.5   //移动设备上的缩放
                },
                "react": {
                        "opacityDefault": 0.7,  //默认透明度
                        "opacityOnHover": 0.2   //鼠标移上透明度
                }
        });
},0)
</script>
<!-- <script src="https://cdn.staticfile.org/jquery/1.10.2/jquery.min.js"></script> -->
<!-- <script src="https://blog-static.cnblogs.com/files/blogs/700930/o0olele.js"></script> -->
<!-- <script src="https://blog-static.cnblogs.com/files/blogs/700930/love.js"></script> -->
<!-- <script src="https://blog-static.cnblogs.com/files/blogs/700930/foreach_.js"></script> -->
<!-- <script src="https://blog-static.cnblogs.com/files/blogs/700930/enjoy.js"></script> -->
<!-- <canvas id="canvas" style="height:220px;width:220px;position:fixed;bottom:0;left:0;" width="220" height="220"></canvas> -->
<script>
        var animationTurn = 0;
        // document.getElementById("canvas").onclick = function (e) {
        //     var state = skeletons[activeSkeleton].state;
        //     var skeleton = skeletons[activeSkeleton].skeleton;
        //     var animationName = skeleton.data.animations[animationTurn].name;
        //     skeleton.setToSetupPose();
        //     state.setAnimation(0, animationName, true);
        //     animationTurn = animationTurn == skeleton.data.animations.length - 1 ? 0 : animationTurn + 1;
        // };

        (function () {
        //     init();
        }
        )();
        function randomColor() {
            return "rgb(" + (~~(Math.random() * 255)) + "," + (~~(Math.random() * 255)) + "," + (~~(Math.random() * 255)) + ")";
        }
        window.onload = function(){
            let cats = document.querySelectorAll('div#sidebar_postcategory ul li a');
            for(let i = 0 ; i < cats.length ; i++){
                cats[i].style.color = randomColor();
            }
        }
</script>
```
