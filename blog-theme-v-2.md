theme: custom

引入第三方模板： Geek
https://www.yuque.com/awescnb/user/kyi19z

```css
    :root{
        --default-color: #7ba5cd,
    }
    canvas#live2dcanvas {border: 0 !important;left: 0;bottom: 0px;}
    
    #loading {
        bottom: 0;
        left: 0;
        position: fixed;
        right: 0;
        top: 0;
        z-index: 9999;
        background-color: #f4f5f5;
        pointer-events: none;
    }

    .loader-inner {
        will-change: transform;
        width: 40px;
        height: 40px;
        position: absolute;
        top: 50%;
        left: 50%;
        margin: -20px 0 0 -20px;
        background-color: #3742fa;
        border-radius: 50%;
        animation: scaleout 0.6s infinite ease-in-out forwards;
        text-indent: -99999px;
        z-index: 999991;
    }

    @keyframes scaleout {
        0% {
            transform: scale(0);
            opacity: 0;
        }

        40% {
            opacity: 1;
        }

        100% {
            transform: scale(1);
            opacity: 0;
        }
    }
    #cnblogs_post_body.blogpost-body-html code, #mainContent .cnblogs-markdown code{
        background-color: transparent;
        margin-top: 12px !important;
    }
    div[id^="ad"] a{
        color: #fff;
        display: none;
    }
    .toolbar-item i{
        color: #7ba5cd;
    }
    #div_digg .diggit::before,#div_digg .buryit::before{
        color: #fff;
    }
    div#sidebar_postcategory ul {
      display: flex;
      flex-wrap: wrap;
    }

    div#sidebar_postcategory ul li {
      margin: 3px 0;
    }

    div#sidebar_postcategory ul li a {
      padding: 3px 5px;
      border: 1px solid #000;
      border-radius: 4px;
    }
```

header HTML
```html
<div id="loading"><div class="loader-inner"></div></div>
```


footer HTML
```html
<script src="https://guangzan.gitee.io/awescnb/index.js"></script>
<script>
  const opts = {
    theme: {
      name: 'geek',
      color: '#7ba5cd',
      avatar: 'https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2036381/o_210925093935f030b8e5edcb8a4c77c47c9f64d4b096.jpg',
      title: '~LemonWater',
      favicon: '🔯',
      headerBackground: 'https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180850197.jpg',
      log: '',
    },
    emoji: {
      enable: true,
      buttonIcon: "🥳",
      emojiList: [
        {
          value: 'https://images.cnblogs.com/cnblogs_com/gshang/1626876/o_2001050555139.png',
          label: '',
        },
        {
            value: '🤣',
            label: '笑哭',
        },
        {
            value: '😃',
            label: '大笑',
        },
        {
            value: '😅',
            label: '苦笑',
        },
        {
            value: '😆',
            label: '斜眼笑',
        },
        {
            value: '😏',
            label: '得意',
        },
        {
            value: '😊',
            label: '微笑',
        },
        {
            value: '😎',
            label: '酷！',
        },
        {
            value: '😍',
            label: '花痴',
        },
        {
            value: '🙂',
            label: '呵呵',
        },
        {
            value: '🤩',
            label: '好崇拜哦',
        },
        {
            value: '🤔',
            label: '思考',
        },
        {
            value: '🙄',
            label: '白眼',
        },
        {
            value: '😜',
            label: '略略略',
        },
        {
            value: '😲',
            label: '呆住',
        },
        {
            value: '😭',
            label: '大哭',
        },
        {
            value: '🤯',
            label: '头炸了',
        },
        {
            value: '😰',
            label: '冷汗',
        },
        {
            value: '😱',
            label: '吓死了',
        },
        {
            value: '🤪',
            label: '略略略',
        },
        {
            value: '😵',
            label: '晕',
        },
        {
            value: '😡',
            label: '愤怒',
        },
        {
            value: '🥳',
            label: '祝贺',
        },
        {
            value: '🤡',
            label: '小丑竟是我',
        },
        {
            value: '🤫',
            label: '嘘~',
        },
        {
            value: '🐒',
            label: '猴',
        },
        {
            value: '🤭',
            label: '笑笑不说话',
        },
        {
            value: '🐂',
            label: '牛',
        },
        {
            value: '🍺',
            label: '啤酒',
        },
        {
            value: '(=・ω・=)',
            label: '',
        },
        {
            value: '(｀・ω・´)',
            label: '',
        },
        {
            value: '(°∀°)ﾉ',
            label: '',
        },
        {
            value: '←_←',
            label: '',
        },
        {
            value: '→_→',
            label: '',
        },
        {
            value: 'Σ(ﾟдﾟ;)',
            label: '',
        },
        {
            value: '(｡･ω･｡)',
            label: '',
        },
         {
             value: '(-_-#)',
             label: '',
         },
      ]
    },
    github: {
      enable: true,
      color: '#ffb3cc',
      url: 'https://github.com/s-mitsuha',
    },
    signature: {
      enable: true,
      contents: [
      "就像拓荒者一样, <b style='color:#7ba5cd'>你是第一批被选中涉足这里的人,</b>.",
      "<b>等待着前仆后继,人山人海的那一天。</b>",
      ],
    },
    imagebox: {
      enable: true,
    },
    darkMode: {
      enable: true,
      autoDark: false,
      autoLight: false
    },
    notice:{
      enable:true,
      text:['🔯欢迎访问','😜一起学习'],
    },
    lock: {
      enable: true,
      background: 'https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180458532.jpg',
      strings: [
        '<i>~LemonWater</i>',
        '&amp; Theme in awescnb',
        '就像拓荒者一样,你是第一批被选中涉足这里的人,等待着前仆后继,人山人海的那一天。',
      ],
    },
    click: {
      enable: true,
      auto: false,
      colors: ['#FF1461', '#18FF92', '#5A87FF', '#FBF38C'],
      size: 20,
      maxCount: 30,
    },
    gitee: {
      enable: true,
      color: '#C71D23',
      url: 'https://gitee.com/s-mitsuha/',
    },
    highLight: {
      dark: 'atomOneDark',
      light: 'atomOneLight',
    },
    lineNumbers: {
      enable: true,
    },
    links: [
      {
        name: 'Github',
        link: 'https://github.com/s-mitsuha',
      },
      {
        name: 'CSDN',
        link: 'https://blog.csdn.net/s_mitsuha',
      },
    ],
    postTopimage: {
      enable: true,
      fixed: true,
      imgs: [
        'https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180458532.jpg',
        'https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180500155.jpg',
        'https://images.cnblogs.com/cnblogs_com/blogs/700930/galleries/2033117/o_2109180459041.jpg'
      ],
    },
  }
  $.awesCnb(opts)
</script>
<script type="text/javascript" charset="utf-8" async=""
        src="https://cdn.jsdelivr.net/npm/live2d-widget@3.0.4/lib/L2Dwidget.min.js"></script>
<!-- 右下角live2d效果 -->
<!-- <script type="text/javascript">
        setTimeout(()=>{
        L2Dwidget.init({
                "model": {
                        "scale": 0.5  //#模型与canvas的缩放
                        // hHeadPos: 0.5	#模型头部横坐标
                        // vHeadPos: 0.618	#模型头部纵坐标
                },
                "display": {
                        // "superSample": 2	//超采样等级
                        "width": 70,   //画布的宽度，显示模型画布的长度
                        "height": 120,  //画布高度显示模型画布的高度
                        "position": "left",	//显示位置：左或右
                        "hOffset": 0,    //水平偏移
                        "vOffset": -10   //垂直偏移
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
</script> -->
<script>
  const htmlStyle = document.body.style;
  window.onload = function(){
    htmlStyle.setProperty('--md-singlelinecode-bg', 'transparent');
    htmlStyle.setProperty('--ad-bg', '#7ba5cd');
    htmlStyle.setProperty('--pagerBtn-bg', '#7ba5cd');
    htmlStyle.setProperty('--color-basic-900', '#fff');
    htmlStyle.setProperty('--sidebarItem-hover-color', '#7ba5cd');
    


    console.log('%c # # # # # # # # # # # # # # # # # # # # # # # #','color:#7ba5cd');
    console.log('%c # 🌏Github https://github.com/s-mitsuha','color: #FFC0CB;font-weight: bold;');
    console.log('%c # ⚡博客园 https://www.cnblogs.com/-LemonWater-','color: #9370DB;font-weight: bold;');
    console.log('%c # 📌CSDN https://blog.csdn.net/s_mitsuha','color: #1E90FF;font-weight: bold;');
    console.log('%c # # # # # # # # # # # # # # # # # # # # # # # #','color:#7ba5cd');
    function randomColor() {
      return "rgb(" + (~~(Math.random() * 255)) + "," + (~~(Math.random() * 255)) + "," + (~~(Math.random() * 255)) + ")";
    }
    let cats = document.querySelectorAll('div#sidebar_postcategory ul li a');
    for(let i = 0 ; i < cats.length ; i++){
      let catColor = randomColor()
      cats[i].style.color = catColor;
      cats[i].style.borderColor = catColor;
    }
  }
</script>
<script src="https://cdn.staticfile.org/jquery/1.10.2/jquery.min.js"></script>
<!-- 明日方舟小人 -->
<script src="https://blog-static.cnblogs.com/files/blogs/700930/o0olele.js"></script>
<canvas id="canvas" style="height:220px;width:220px;position:fixed;bottom:40px;left:0;" width="220" height="220"></canvas>
<script>
  var animationTurn = 0;
  document.getElementById("canvas").onclick = function (e) {
    var state = skeletons[activeSkeleton].state;
    var skeleton = skeletons[activeSkeleton].skeleton;
    var animationName = skeleton.data.animations[animationTurn].name;
    skeleton.setToSetupPose();
    state.setAnimation(0, animationName, true);
    animationTurn = animationTurn == skeleton.data.animations.length - 1 ? 0 : animationTurn + 1;
  };

  (function () {init();})();
</script>

```
