# ruanjian1
*{
    margin: 0;
    padding: 0;
}

.header{
    width: 100%;
    height: 58px;
    background-color: #191D3A;
}

.inner{
    width: 1000px;
    height: 58px;
    margin: 0;
    padding-left: 25%;
    clear: both;
}

.inner .logo{
    float: left;
    width: 225px;
    height: 58px;
    margin: 0 0;
}

.header .navs{
    float: left;
    height: 58px;
}

.header .inner .navs a{
    float: left;
    width: 85px;
    height: 58px;
    border-left: 1px solid #252947;
    border-left: 1px solid #252947;
    color: #818496;
    text-decoration: none;
    text-align: center;
    line-height: 58px;
    font-size: 14px;
}
.header .inner .navs .joinus{
    margin: 12px 0 0 10px;
    height: 32px;
    width: 98px;
    border: 1px solid #3aca7a;
    border-radius: 3px;
    background-color: #38b774;
    color: white;
    text-align: center;
    line-height: 32px;
}
.header .inner .joinus:hover{
    background-color: green;
}
.header .inner .nav:hover{
    color: #e2e4ed;
}

.header .inner .changelang a{
    display: block;
    margin-right: 10px;
    float: left;
    color: #818496;
    text-decoration: none;
    text-align: center;
    font-size: 14px;
}
.header .inner .changelang .cn{
    color: #1F9574;
}
.header .inner .changelang a:hover{
    color: #1F9574;
}
.header .inner .changelang{
    float: right;
    line-height: 58px;
}

.banner img{
    width: 100%;
}

.content{
    width: 1200px;
    margin: 10px auto;
}
.content ul li{
    list-style: none;
    float: left;
    width: 218px;
    margin-right: 40px;
}
.content ul li img{
    width: 210px;
    height: 130px;
}
.content ul li h4{
    text-align: center;
    line-height: 38px;
    font-size: 14px;
}
.content ul li p{
    text-align: center;
    height: 20px;
}
.content ul li a{
    color: black;
    font-size: 14px;
    text-decoration: none;
    padding-right: 12px;
}
.content ul li a:hover{
    color: green;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>博雅互动——Practice</title>
    <link rel="stylesheet" type="text/css" href="css/style.css" />
</head>
<body>
<div class="header">
    <div class="inner">
        <div class="logo">
            <a href="http://www.boyaa.com/index.html"><img src="imgs/1.png" alt="图片" /></a>
        </div>
        <div class="navs">
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670" class="nav">首页</a>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670" class="nav">博雅游戏</a>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670" class="nav">博雅新闻</a>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670" class="nav">关于我们</a>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670" class="nav">客服中心</a>
            <a href="" class="nav">投资者关系</a>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670" class="joinus">加入我们</a>
        </div>
        <div class="changelang">
            <a href="" class="cn">中文</a>
            <a href="">EN</a>
        </div>
    </div>

</div>
<div class="banner">
    <img src="imgs/2.png" alt="图片" />
</div>
<!--宣传栏-->
<div class="content">
    <ul>
        <li>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670">
                <img src="imgs/3.png" alt="图片">
                <h4>博雅棋牌</h4>
                <p>
                    <span>BOYAA CHESS</span>
                </p>
            </a>

        </li>

        <li>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670">
                <img src="imgs/4.png" alt="图片">
                <h4>四川麻将</h4>
                <p>
                    <span>sichuan mahjong</span>
                </p>
            </a>
        </li>

        <li>
            <a href="https://blog.csdn.net/qq_43717065/article/details/107322670">
                <img src="imgs/5.png" alt="图片">
                <h4>四川棋牌</h4>
                <p>
                    <span>boyaa szechwan game</span>
                </p>
            </a>
        </li>

        <li>
            <a href="">
                <img src="imgs/6.png" alt="图片">
                <h4>云南高校赛回顾</h4>
                <p>
                    <span>点击播放</span>
                </p>
            </a>
        </li>
    </ul>
</div>
</body>
</html>
