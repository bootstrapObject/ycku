### 飘城企训网

使用技能
* [html](http://www.w3school.com.cn/html/)
* [css](http://www.w3school.com.cn/css/index.asp)
* [jQuery](https://jquery.com/)
* [bootstrap](http://getbootstrap.com/2.3.2/)
* [wow](http://www.dowebok.com/131.html)

兼容：IE9+ Chrome Firefox Opera Safari

适配 phone pad PC等各种尺寸屏幕

![](images/img1.gif)

![](images/img2.gif)

![](images/img3.gif)


index code:
```
<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1"/>
    <meta http-equiv="X-UA-Compitable" content="IE=edge">
    <title>飘城企训网</title>
    <!--[if lt IE 9]>
    <script src="js/html5shiv.min.js"></script>
    <script src="js/respond.min.js"></script>
    <![endif]-->
    <link rel="stylesheet" href="css/bootstrap.css"/>
    <link rel="stylesheet" href="css/index.css">
    <link rel="stylesheet" href="css/animate.min.css">
</head>
<body>
<nav class="navbar-default">
    <div class="container">
        <!-- Brand and toggle get grouped for better mobile display -->
        <div class="navbar-header wow rollIn animated">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
            <a href=""><img src="images/img/logo.png"/></a>
        </div>
        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
            <ul class="nav navbar-nav navbar-right ">
                <li class="active wow rollIn animated" data-wow-delay="0.5s"style="visibility: visible; animation-delay: 0.5s; animation-name: rollIn;"><a href="" data-toggle="tab"><span class="glyphicon glyphicon-home"></span> 首页</a></li>
                <li class="wow rollIn animated" data-wow-delay="1.5s"style="visibility: visible; animation-delay: 1.5s; animation-name: rollIn;"><a href="" data-toggle="tab"><span class="glyphicon glyphicon-list"></span> 资讯</a></li>
                <li class="wow rollIn animated" data-wow-delay="2.5s"style="visibility: visible; animation-delay: 2.5s; animation-name: rollIn;"><a href=""  data-toggle="tab"><span class="glyphicon glyphicon-fire"></span> 案例</a></li>
                <li class="wow bounceInRight animated" data-wow-delay="3.5s"style="visibility: visible; animation-delay: 3.5s; animation-name: bounceInRight;"><a href="" data-toggle="tab"><span class="glyphicon glyphicon-question-sign"></span> 关于</a></li>
            </ul>
        </div><!-- /.navbar-collapse -->
    </div><!-- /.container-fluid -->
</nav>
<div class="tab-content">
    <div class="tab-pane active" id="home">
        <!--轮播-->
        <div id="carousel-example-generic" class="carousel slide wow bounceInDown animated" data-ride="carousel">
            <!-- Indicators -->
            <ol class="carousel-indicators">
                <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
                <li data-target="#carousel-example-generic" data-slide-to="1"></li>
                <li data-target="#carousel-example-generic" data-slide-to="2"></li>
            </ol>
            <!-- Wrapper for slides -->
            <div class="carousel-inner" role="listbox">
                <div class="item active banner1">
                    <img src="images/img/slide1.png" alt="...">
                </div>
                <div class="item banner2">
                    <img src="images/img/slide2.png" alt="...">
                </div>
                <div class="item banner3">
                    <img src="images/img/slide3.png" alt="...">
                </div>
            </div>
            <!-- Controls -->
            <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
        <!--轮播-->
        <div class="container">
            <div class="row">
                <div class="col-md-12 text-center">
                    <h1 class="text-primary">「为什么选择瓢城企业培训」</h1>
                    <p>强大的师资力量，完美的实战型管理课程，让您的企业实现质的腾飞！</p>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <div class="media">
                        <div class="media-left wow rollIn animated">
                            <a href="#">
                                <img class="media-object" src="images/img/tab1-1.png" alt="...">
                            </a>
                        </div>
                        <div class="media-body">
                            <h4 class="media-heading">课程内空</h4>
                            <del>其他：高校不知名的讲师编写，没有任何实战价值的教材！</del>
                            <p>我们：知名企业家、管理学大师联合编写的具有实现性教材！</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="media">
                        <div class="media-left wow lightSpeedIn animated">
                            <a href="#">
                                <img class="media-object" src="images/img/tab1-2.png" alt="...">
                            </a>
                        </div>
                        <div class="media-body">
                            <h4 class="media-heading">师资力量</h4>
                            <del>其他：非欧美正牌大学毕业的、业界没有知名度的讲师！</del>
                            <p>我们：美国哈佛、耶鲁等世界一流高校、享有声誉的名牌专家！</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <div class="media">
                        <div class="media-left wow rollIn animated">
                            <a href="#">
                                <img class="media-object" src="images/img/tab1-3.png" alt="...">
                            </a>
                        </div>
                        <div class="media-body">
                            <h4 class="media-heading">课时安排</h4>
                            <del>其他：无法保证上课效率、没有时间表、任务无法完成！</del>
                            <p>我们：保证按时间表的上课、效率高、当天的任务当天完成！</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="media">
                        <div class="media-left wow bounceInRight animated">
                            <a href="#">
                                <img class="media-object" src="images/img/tab1-4.png" alt="...">
                            </a>
                        </div>
                        <div class="media-body">
                            <h4 class="media-heading">服务团队</h4>
                            <del>其他：社会招聘的、服务水平参差不齐的普通员工！</del>
                            <p>我们：内部培养、经受过良好高端服务培训的高标准员工！</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="slide" style="padding:50px 0;">
            <div class="container">
                <div class="row">
                    <div class="col-sm-6 tu wow bounceInRight animated">
                        <img class="center-block" src="images/img/tab2.png" alt="">
                    </div>
                    <div class="col-sm-6 text-center zi wow bounceInLeft animated">
                        <h2>强大的学习体系</h2>
                        <p>经过管理学大师层层把关、让您的企业突飞猛进。</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="container" style="padding:50px 0;">
            <div class="row">
                <div class="col-md-6 wow bounceInRight animated">
                    <img class="center-block" src="images/img/tab3.png" alt="" style="width:80%;">
                </div>
                <div class="col-md-6 text-center wow bounceInLeft animated">
                    <h2>完美的管理方式</h2>
                    <p>最新的管理培训方案，让您的企业赶超同行。</p>
                </div>
            </div>
        </div>
    </div>
    <div class="tab-pane" id="profile">
        <div class="bg">
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <h2>资讯</h2>
                        <p>企业内训的最新动态、资源等..........</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="slide">
            <div class="container">
                <div class="row">
                    <div class="col-md-8">
                        <div class="container-fluid">
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info1.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>广电总局发布TVOS2.0 华为阿里参与研发</h4>
                                    <p class="hidden-xs">TVOS2.0是在TVOS1.0与华为MediaOS及阿里巴巴YunOS融合的基础上，打造的新一代智能电视操作系统。华为主要承担开发工作，内置的电视购物商城由阿里方面负责。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info2.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>苹果四寸手机为何要配置强大的A9处理器？</h4>
                                    <p class="hidden-xs">苹果明年初有可能对外发布一款经过升级的四英寸手机，相当于iPhone 5s。该手机将会配置苹果在2015年旗舰手机中采用的A9处理器。配置性能如此强大的应用处理器？</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info3.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>六家互联网公司发声明 抵制流量劫持等违法.......</h4>
                                    <p class="hidden-xs">六家互联网公司（今日头条、美团大众点评网、360、腾讯、微博、小米科技）发布联合声明，呼吁有关运营商打击流量劫持，重视互联网公司被流量劫持，可能导致的严重后果。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info1.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>广电总局发布TVOS2.0 华为阿里参与研发</h4>
                                    <p class="hidden-xs">TVOS2.0是在TVOS1.0与华为MediaOS及阿里巴巴YunOS融合的基础上，打造的新一代智能电视操作系统。华为主要承担开发工作，内置的电视购物商城由阿里方面负责。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info2.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>苹果四寸手机为何要配置强大的A9处理器？</h4>
                                    <p class="hidden-xs">苹果明年初有可能对外发布一款经过升级的四英寸手机，相当于iPhone 5s。该手机将会配置苹果在2015年旗舰手机中采用的A9处理器。配置性能如此强大的应用处理器？</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info3.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>六家互联网公司发声明 抵制流量劫持等违法.......</h4>
                                    <p class="hidden-xs">六家互联网公司（今日头条、美团大众点评网、360、腾讯、微博、小米科技）发布联合声明，呼吁有关运营商打击流量劫持，重视互联网公司被流量劫持，可能导致的严重后果。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info1.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>广电总局发布TVOS2.0 华为阿里参与研发</h4>
                                    <p class="hidden-xs">TVOS2.0是在TVOS1.0与华为MediaOS及阿里巴巴YunOS融合的基础上，打造的新一代智能电视操作系统。华为主要承担开发工作，内置的电视购物商城由阿里方面负责。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info2.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>苹果四寸手机为何要配置强大的A9处理器？</h4>
                                    <p class="hidden-xs">苹果明年初有可能对外发布一款经过升级的四英寸手机，相当于iPhone 5s。该手机将会配置苹果在2015年旗舰手机中采用的A9处理器。配置性能如此强大的应用处理器？</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info3.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>六家互联网公司发声明 抵制流量劫持等违法.......</h4>
                                    <p class="hidden-xs">六家互联网公司（今日头条、美团大众点评网、360、腾讯、微博、小米科技）发布联合声明，呼吁有关运营商打击流量劫持，重视互联网公司被流量劫持，可能导致的严重后果。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info1.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>广电总局发布TVOS2.0 华为阿里参与研发</h4>
                                    <p class="hidden-xs">TVOS2.0是在TVOS1.0与华为MediaOS及阿里巴巴YunOS融合的基础上，打造的新一代智能电视操作系统。华为主要承担开发工作，内置的电视购物商城由阿里方面负责。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info2.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>苹果四寸手机为何要配置强大的A9处理器？</h4>
                                    <p class="hidden-xs">苹果明年初有可能对外发布一款经过升级的四英寸手机，相当于iPhone 5s。该手机将会配置苹果在2015年旗舰手机中采用的A9处理器。配置性能如此强大的应用处理器？</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-5">
                                    <img class="img-responsive" src="images/img/info3.jpg" alt="...">
                                </div>
                                <div class="col-xs-7">
                                    <h4>六家互联网公司发声明 抵制流量劫持等违法.......</h4>
                                    <p class="hidden-xs">六家互联网公司（今日头条、美团大众点评网、360、腾讯、微博、小米科技）发布联合声明，呼吁有关运营商打击流量劫持，重视互联网公司被流量劫持，可能导致的严重后果。</p>
                                    <span>admin 15 / 10 / 11</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="hidden-xs hidden-sm col-md-4">
                        <div class="row">
                            <div class="col-md-12">
                                <h2>｜热门资讯</h2>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info2.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>苹果四寸手机为何要配置强大的A9处理器？</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info1.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>广电总局发布TVOS2.0 华为阿里参与研发</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info3.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>六家互联网公司发声明 抵制流量劫持等违法行</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info2.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>苹果四寸手机为何要配置强大的A9处理器？</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info1.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>广电总局发布TVOS2.0 华为阿里参与研发</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info3.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>六家互联网公司发声明 抵制流量劫持等违法行</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info2.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>苹果四寸手机为何要配置强大的A9处理器？</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive" src="images/img/info1.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>广电总局发布TVOS2.0 华为阿里参与研发</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-md-5">
                                <img class="img-responsive img-last" src="images/img/info3.jpg" alt="...">
                            </div>
                            <div class="col-md-7">
                                <h4>六家互联网公司发声明 抵制流量劫持等违法行</h4>
                                <span>admin 15 / 10 / 11</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="tab-pane" id="messages">
        <div class="bg">
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <h2>案例</h2>
                        <p>和各大明星企业有着紧密合作..........</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="slide">
            <div class="container">
                <div class="row">
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case1.jpg" alt="...">
                            <div class="caption">
                                <h3>中国移动通信</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case2.jpg" alt="...">
                            <div class="caption">
                                <h3>中国石化</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case3.jpg" alt="...">
                            <div class="caption">
                                <h3>中国联通</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case4.jpg" alt="...">
                            <div class="caption">
                                <h3>中国电信</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case4.jpg" alt="...">
                            <div class="caption">
                                <h3>中国电信</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case3.jpg" alt="...">
                            <div class="caption">
                                <h3>中国联通</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case1.jpg" alt="...">
                            <div class="caption">
                                <h3>中国移动通信</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case2.jpg" alt="...">
                            <div class="caption">
                                <h3>中国石化</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case4.jpg" alt="...">
                            <div class="caption">
                                <h3>中国电信</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case3.jpg" alt="...">
                            <div class="caption">
                                <h3>中国联通</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case4.jpg" alt="...">
                            <div class="caption">
                                <h3>中国电信</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="thumbnail text-center">
                            <img src="images/img/case2.jpg" alt="...">
                            <div class="caption">
                                <h3>中国石化</h3>
                                <p>参与了本机构的总裁管理培训课程，学员反馈意见良好。</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="tab-pane" id="settings">
        <div class="bg">
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <h2>关于</h2>
                        <p>本机构的成长介绍..........</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="slide">
            <div class="container">
                <div class="row">
                    <div class="col-md-3 hidden-sm hidden-xs">
                        <div class="border-e">
                            <div class="row">
                                <div class="col-md-12">
                                    <div class="thumbnail">
                                        <a name="jigou2" href="#jigou">1.机构简介</a>
                                    </div>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-md-12">
                                    <div class="thumbnail">
                                        <a href="#join" name="join2">2.加入我们</a>
                                    </div>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-md-12">
                                    <div class="thumbnail">
                                        <a href="#concat" name="concat2">2.联系方式</a>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                    <div class="col-md-9">
                        <div class="thumbnail">
                            <a href="#jigou2" name="jigou">机构简介</a>
                            <hr>
                            <p>瓢城企业培训有限公司是一家专业以智能化弱电工程为主的高科技民营企业，公司自创立以来一直专业致力于智能化弱电工程；始终坚持发扬"诚信、创新、沟通"为企业宗旨，以"技术、服务"为立业之本的团体精神，并形成一套完整的设计、安装、调试、培训、维护一站式服务体系。</p>
                            <a href="#join2" name="join">加入我们</a>
                            <hr>
                            <p>网络已深刻改变着人们的生活，本地化生活服务市场前景巨大，生活半径团队坚信本地化生活服务与互联网的结合将会成就一家梦幻的公司，我们脚踏实地的相信梦想，我们相信你的加入会让生活半径更可能成为那家梦幻公司！生活半径人有梦想，有魄力，强执行力，但是要实现这个伟大的梦想，需要更多的有创业精神的你一路前行。公司将提供有竞争力的薪酬、完善的福利（五险一金）、期权、广阔的上升空间。只要你有能力、有激情、有梦想，愿意付出，愿意与公司共同成长，请加入我们！</p>
                            <p>请发送您的简历到：hr@xxx.com，我们会在第一时间联系您！</p>
                            <a href="#concat2" name="concat">联系方式</a>
                            <hr>
                            <p>地址：江苏省盐城市亭湖区大庆中路1234号</p>
                            <p>邮编：1234567</p>
                            <p>电话：010-88888888</p>
                            <p>传真：010-88666666</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<nav class="navbar navbar-color text-center text-white">
    <ul style="margin-top:1%;">
        <li><p>企业培训 ｜ 合作事宜 ｜版权投诉</p></li>
    </ul>
    <span>苏ICP备 12345678 .&copy; 2009-2016 瓢城企训网 .Powered by Bootstrap.</span>
</nav>
<script src="js/jquery-1.11.3.js"></script>
<script src="js/bootstrap.js"></script>
<script src="js/wow.min.js"></script>
<script>
$(function(){
    /* css布局实现任何设备均显示垂直居中样式*/
    $(window).load(function(){
        $("#home>.slide>.container>.row>.text-center").css("margin-top",($("#home>.slide>.container>.row>.col-sm-6>.center-block").height()-$("#home>.slide>.container>.row>.text-center").height())/2+"px");
    });
    $(window).resize(function(){
        $("#home>.slide>.container>.row>.text-center").css("margin-top",($("#home>.slide>.container>.row>.col-sm-6>.center-block").height()-$("#home>.slide>.container>.row>.text-center").height())/2+"px");
    });
    $(window).load(function(){
        $("#home>.container>.row>.text-center").css("margin-top",($("#home>.container>.row>.col-md-6>.center-block").height()-$("#home>.container>.row>.text-center").height())/2+"px");
    });
    $(window).resize(function(){
        $("#home>.container>.row>.text-center").css("margin-top",($("#home>.container>.row>.col-md-6>.center-block").height()-$("#home>.container>.row>.text-center").height())/2+"px");
    });
    /*实现页面淡入淡出效果*/
    $("#bs-example-navbar-collapse-1>.nav>li:first-child").click(function(){
        $(".tab-content>#settings").fadeOut(1000);
        $(".tab-content>#messages").fadeOut(1000);
        $(".tab-content>#profile").fadeOut(1000);
        $(".tab-content>#home").fadeIn(1000);
//        alert(1);
    })
    $("#bs-example-navbar-collapse-1>.nav>li").eq(1).click(function(){
        $(".tab-content>#home").fadeOut(1000);
        $(".tab-content>#settings").fadeOut(1000);
        $(".tab-content>#messages").fadeOut(1000);
        $(".tab-content>#profile").fadeIn(1000);
//        alert(2);
    })
    $("#bs-example-navbar-collapse-1>.nav>li").eq(2).click(function(){
        $(".tab-content>#home").fadeOut(1000);
        $(".tab-content>#profile").fadeOut(1000);
        $(".tab-content>#settings").fadeOut(1000);
        $(".tab-content>#messages").fadeIn(1000);
//        alert(3);
    })
    $("#bs-example-navbar-collapse-1>.nav>li").eq(3).click(function(){
        $(".tab-content>#home").fadeOut(1000);
        $(".tab-content>#profile").fadeOut(1000);
        $(".tab-content>#messages").fadeOut(1000);
        $(".tab-content>#settings").fadeIn(1000);
//        alert(4);
    })
})
</script>
</body>
</html>
```
