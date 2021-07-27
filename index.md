
<html lang="zh-CN">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,Chrome=1" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no" />
  <meta name="format-detection" content="telephone=no" />
  <title>方黎明-计算机科学与技术学院/人工智能学院</title>
  <meta name="keywords" content="" />
  <meta name="description" content="" />
<style type="text/css">
p{line-height:300%;}
 .justify
        {
            text-align: justify;
            width: 890px;
            margin-bottom:10px;
        }
        .justify > span
        {
            display: inline-block /* Opera */;
            padding-left: 100%;
        }
@charset"utf-8";
/* CSS Reset*/
input::-moz-placeholder, textarea::-moz-placeholder { color: #d6f0ff; }
input:-ms-input-placeholder, textarea:-ms-input-placeholder { color: #d6f0ff; }
input::-webkit-input-placeholder, textarea::-webkit-input-placeholder { color: #d6f0ff; }
.box-content{-webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;}
.fr { float: right; } .fl { float: left; }
.t-l{text-align: left;}.t-c{text-align: center;}.t-r{text-align: right;}
.an { transition: all 0.3s ease-out 0s;-moz-transition: all 0.3s ease-out 0s;-webkit-transition: all 0.3s ease-out 0s;-o-transition: all 0.3s ease-out 0s;}
.img-width { max-width: 100%; height: auto!important; }
.clearfix:before, .clearfix:after {content:""; display:table;}   
.clearfix:after {clear:both;}   
.clearfix { *zoom:1;}
.radius{border-radius:50%;-webkit-border-radius:50%;-moz-border-radius:50%;}
.over-txt {display:block;white-space:nowrap; overflow:hidden; text-overflow:ellipsis}
.txt-a-A {text-transform: capitalize;text-transform:uppercase;text-transform:lowercase;}
.po-re {position: relative;}
.p30{padding-left: 10px;padding-right: 10px;}
.bg {background-image:url(../images/);background-color:rgba(0,0,0,0.5);background-repeat:no-repeat;background-position: center;background-size:cover;}
.borderStyle {border-bottom:1px dashed #707070;border-top:1px dotted #707070;}
.box-shadow {-webkit-box-shadow:0 0 10px #ccc; -moz-box-shadow:0 0 10px #ccc;  box-shadow:0 0 10px #ccc;}
/*public*/
.top-se {background: #666;display: none;}
.t_se {width: 400px;max-width: 90%; position: relative;padding-right: 100px;height: 30px;margin:15px auto;background: #fff;}
.se_txt {width: 100%;float: left; border: none;margin:0;padding-left:10px; background:transparent;height: 30px;line-height: 30px;font-size: 12px;color: #333;font-family:"SimSun";}
.se_sub {position: absolute;right: 30px;top: 0;width: 60px;height: 30px;color: #fff;font-size: 12px;border: none;margin:0;padding:0;cursor: pointer; background: #0d4ea8;} 
.se_close {display: block;position:absolute;right: 0;top:0;background: #333 url(../images/close.png) no-repeat center;width: 30px;height: 30px;}

.top {width: 100%;background: #017abf url(../images/top-bg.jpg) no-repeat center top;position: relative;z-index: 50;}
.container {position: relative;}
.logo {padding:0 5px;text-align: center;}
.logo_table {display: table;width: 100%;height: 70px;}
.logo_cell {display: table-cell;vertical-align: middle;}
.logo_cell img {max-width: 500px;width: 100%;height: auto;}
.top_r {}
.top_r_a {text-align: right;}
.top_r_a a {display: inline-block;*display: inline;height: 30px;line-height: 30px;font-size: 12px;color: #b9e5fc;vertical-align: middle;margin-left: 3px;}
.top_r_a a.a1 {background-image:url(../images/home.png);background-repeat:no-repeat;background-position:6px center;background-color:#2b89e1;padding: 0 7px 0 23px;}
.top_r_a a.a2 {background-color:#0d4ea8;padding: 0 8px;}
.top_r_a a.a3 {width: 30px;background-image:url(../images/se.png);background-repeat:no-repeat;background-position:center;background-color:#006199;}
.top_r_a a:hover {background-color:#333;}

.top_nav {height: 60px;margin-top: 3px;}
.pc_menuCon {}
.pc_menuCon li {float: left;position: relative;line-height: 60px;height: 60px;}
.pc_menuCon li a {display:block; color: #fff;line-height: 60px;font-size: 14px;text-align: center;padding:0 15px;}
.pc_menuCon > li:hover > a {background-color:#2e83f1;color: #fff} 
.pc_menuCon > li.active > a {background-color:#2e83f1;color: #fff} 
.pc_menuCon > li.parent > a {background-color:#2e83f1;color: #fff} 
.pc_menuCon > li.selected > a {background-color:#2e83f1;color: #fff} 

.pc_menuCon ul { display: none;position: absolute;left: 50%;top: 60px; margin-left:-72px;width: 144px; padding:0;background: #2e83f1;list-style: none;}
.pc_menuCon ul li { width: 100%; float: left;background:transparent;height: 32px;line-height: 32px;border-top:1px solid #e9ecf0;}
.pc_menuCon ul li a {display:block;color:#fff;height: 32px;line-height: 32px;font-size: 12px;padding:0;text-align: center;border:none;font-weight: normal;}
.pc_menuCon ul li:hover {background: #017cc0;}
.pc_menuCon ul li:hover a {color: #fff;}
/*-----pc nav-----*/
.mean-container {background:#2e83f1;}
.mean-container a.meanmenu-reveal {color: #fff;}
.mean-container a.meanmenu-reveal span{background:#fff;}
.mean-container .meanmenu-title {color: #fff;}
.mean-container .mean-nav{background:rgba(46,131,241,0.9);}
.lighted-fixed {position: fixed;left: 0;width: 100%;top: 0;background: #2e83f1;z-index: 999;-webkit-box-shadow:0 0 10px #ccc; -moz-box-shadow:0 0 10px #ccc;  box-shadow:0 0 10px #ccc;}
.lighted-fixed .mean-nav > ul {height:calc(100vh - 50px);overflow-y:auto;}
/*-----phone nav-----*/
.banner {position: relative;width: 100%;}
.banner {}
.banner .bx-wrapper .bx-pager.bx-default-pager a {background:url(../images/ardius_q.png) no-repeat center;text-indent: -9999px;display: block;width: 12px;height: 12px;margin: 0 5px;outline: 0;-moz-border-radius: 0px;-webkit-border-radius: 0px;border-radius: 0px;}
.banner .bx-wrapper .bx-pager.bx-default-pager a:hover,
.banner .bx-wrapper .bx-pager.bx-default-pager a.active {background:url(../images/ardius_d.png) no-repeat center;}
.banner .bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-pager {bottom:10px;}

.type {background-color: #e9ecf0;}
.type .row {margin-left: 0;margin-right: 0;}
.type .row .col {padding-left: 0;padding-right: 0;}
.type-p {display:table;width: 100%;height:72px;text-align: center;background: url(../images/nav-l.jpg) no-repeat left center;position:relative;}
.type-p a {/*display: block;*/width: 100%;height: 100%;font-size: 16px;color: #333;z-index: 10;position:relative;text-align: center;color: #333;/*padding-top: 20px;*/}
.type-p a p {display:table-cell;vertical-align: middle;height: 72px;font-size: 24px;/*line-height: 105px;*/line-height: 28px;}
.type-p a p i {font-style: normal;font-size: 16px;}
.type-p span {position:absolute;display: block;left: 0;bottom: 0;background: #0e8ed5;width: 100%;height: 0;z-index: 5;}
.type-p:hover a{color: #fff;}
.type-p:hover span {height: 100%;}
.type .row .col {background:url(../images/nav-b.jpg) no-repeat center bottom;}
.type .row .col-d,.type .row .col-e,.type .row .col-f {background: none;}
.type-c,.type-e {background:url(../images/nav-l.jpg) no-repeat left center;}
.type-a,.type-d {background: none;}

.section {padding-bottom: 25px;}
.section2 {background: #f3f3f3;padding-bottom: 25px;}
.section .row {margin-left: -15px;margin-right: -15px;}
.section .row .col {padding-left: 15px;padding-right: 15px;}
.in_title {width: 100%;position: relative;height: 60px;margin-top: 12px;background: url(../images/title.png) no-repeat 2px center; padding-left: 72px;padding-right: 50px;border-bottom: 2px solid #017cc0;}
.in_title span {font-size: 16px;color: #017cc0;display: inline-block;*display: inline;line-height: 58px;height: 58px;}
.in_title a {display: block;width: 45px;height: 20px;line-height: 20px;position: absolute;right: 0;bottom: 13px;text-align: center;font-size: 12px;font-family:"SimSun";color: #a8a8a8;}
.in_title a:hover {color: #017cc0;}
.in_title_b {border-bottom: none;}
.in_title_b a {bottom: 15px;}
.in_title_c span {color: #8e8e8e;margin-right: 15px;cursor: pointer;}
.in_title_c span.active {color: #017cc0;background: url(../images/title02.png) no-repeat center bottom;}

.section-l-con {background: url(../images/bg01.jpg) no-repeat center top;}
.section-l-con .row {margin-left: -7px;margin-right: -7px;}
.section-l-con .row .col {padding-left: 7px;padding-right: 7px;}
.list-img {}
.bxslider03-pic li {height: 274px; }
.bxslider03-pic li div {height: 230px;background-size: cover;position: relative;background-repeat:no-repeat;background-position: center;}
.bxslider03-pic li p {width: 100%;height: 44px;padding:0 15px;color: #fff;text-align: center;}
.bxslider03-pic li a {display: block;width: 100%;line-height: 44px;font-size: 14px;color: #fff;white-space:nowrap; overflow:hidden; text-overflow:ellipsis;}
.list-img .bx-wrapper .bx-pager.bx-default-pager a {background:#fff;text-indent: 9999px;display: block;width: 10px;height: 10px;margin: 0 1px;outline: 0;-moz-border-radius: 0px;-webkit-border-radius: 0px;border-radius: 0px;}
.list-img .bx-wrapper .bx-pager.bx-default-pager a:hover,
.list-img .bx-wrapper .bx-pager.bx-default-pager a.active {background:#ff6600;}
.list-img .bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-pager {bottom:10px;left: auto;right: 10px; height: 10px;text-align: right;width: 48px;}
.list-ul {margin-top: 10px;}
.list-ul-li li{height: 36px;position:relative;background: url(../images/li01.png) no-repeat left center;padding: 0 68px 0 25px;}
.list-ul-li li a {display: block;font-size: 14px;color: #efefef;line-height: 36px;height: 36px; white-space:nowrap; overflow:hidden; text-overflow:ellipsis;position: relative;}
.list-ul-li li i {font-style: normal;width: 58px;height: 36px;line-height: 36px;position: absolute;right: 0;bottom: 0;font-size: 14px;color: #efefef;}
.list-ul-li li:hover a {color: #5ba8d2;}
.list-ul-b {margin-top: 5px;height: 192px;}
.list-ul-li-b li {padding: 0 50px 0 25px;height: 32px;}
.list-ul-li-b li a {color: #4b4c4c;line-height: 32px;height: 32px;}
.list-ul-li-b li i {color: #5ba8d2;width: 40px;line-height: 32px;height: 32px;}
.zt {position: relative;height: 74px;padding-left: 43px;margin-top: 3px;text-align: center;}
.zt-title {position:absolute;left: 0;top: 0;background: #0088e9;width: 43px;height: 74px;font-size: 16px;color: #fff;line-height: 32px;padding-top: 5px;}
.zt-con {height: 74px;}
.zt-con img {width: 100%;height: 100%;}

.in-news {background: #f3f3f4;}
.news_title_item {font-size: 16px;color: #8e8e8e;line-height: 58px;height: 58px;cursor: pointer;}
.news_title_item.active {color: #017cc0;background: url(../images/title02.png) no-repeat center bottom;}
.in-news-con {padding:20px 0;position:relative;height: 400px;}
.in-news-con .row {display: none;height: 360px;}
/*.in-news-li {}
.in-news-li {height: 40px;position:relative;padding: 0 72px 0 15px;}
.in-news-li a {display: block;font-size: 14px;color: #4b4c4c;line-height: 40px;height: 40px; white-space:nowrap; overflow:hidden; text-overflow:ellipsis;position: relative;}
.in-news-li i {font-style: normal;width: 15px;height: 40px;line-height: 40px;position: absolute;left: 0;bottom: 0;font-size: 14px;color: #0e8ed5;font-family:"SimSun";}
.in-news-li span {display: block;width: 75px;height: 40px;line-height: 40px;position: absolute;right: 0;bottom: 0;text-align: center;font-size: 14px;color: #5ba8d2;}
.in-news-li:hover a {color: #5ba8d2;}
.in-news-more {display: block;width: 45px;height: 20px;line-height: 20px;position: absolute;right: 0;top:-35px;text-align: center;font-size: 12px;font-family:"SimSun";color: #a8a8a8;}
.in-news-more:hover {color: #017cc0;}*/


.main-c-item {margin-top: 30px;}
.main-c-t {position: relative;height: 40px;/*background: #c0e9ff;*/}
.main-c-t span {display: inline-block;font-size: 18px;color: #1968ad;font-weight: bold;padding-left: 22px;line-height: 40px; background:url(../images/t01.jpg) no-repeat 10px center;}
.main-c-t a {display: block;width: 40px;height: 40px;line-height: 40px; font-size: 12px;color: #93c3ed;position: absolute;right: 7px;bottom: 0;text-align: center;}
.main-c-t a:hover{text-decoration: underline;color: #1a5ace}
.main-c-list {/*background: #e8f5ff;*/padding:4px 6px 18px;}
.main-c-list ul li {padding:0 50px 0 0;position: relative;height: 40px;border-bottom:1px dotted #808080;}
.main-c-list ul li a {line-height: 39px;font-size: 14px;color: #333; display: block;white-space:nowrap; overflow:hidden; text-overflow:ellipsis;padding-left: 15px;}
.main-c-list ul li i {font-style: normal;width: 15px;height: 40px;line-height: 40px;position: absolute;left: 0;bottom: 0;font-size: 14px;color: #0e8ed5;font-family:"SimSun";}
.main-c-list ul li span {display: block;width: 45px;height: 39px;line-height: 39px;text-align: right;position: absolute;right: 3px;top: 0;font-size: 14px;color: #333;}
.main-c-list ul li:hover a {color: #1a5ace;}



.in-info-con {padding-top: 25px;position: relative;}
.in-info-con .row {display: none;}
/*.info_item {padding-left: 85px;padding-right: 10px; position: relative;height: 74px;margin-bottom: 25px;}
.info_item .date {position: absolute;left: 0;top: 0;height: 74px;width: 65px;text-align: center;}
.info_item .date h3 {font-size: 20px;color: #fff;background: #2f83f1;height: 37px;line-height: 37px;text-transform:capitalize; }
.info_item .date p {font-size: 22px;color: #282828;height: 37px;line-height: 36px;background: #fff;border: 1px solid #f7f7f7;border-top: none;}
.info_item .title p {display: block;font-size: 14px;color: #165785;line-height: 28px;height: 28px;white-space:nowrap; overflow:hidden; text-overflow:ellipsis;font-weight: bold;}
.info_item .des {font-size: 14px;color: #838383;line-height: 23px;overflow: hidden;height: 46px;}
.info_item:hover {background: #0e8ed5;}
.info_item:hover .title p {color: #fff;}
.info_item:hover .des {color: #fff;}*/


.info-item {padding-left: 84px; position: relative;height: 135px;margin-bottom: 23px;}
.info-item .date {position: absolute;left: 0;top: 0;height: 66px;width: 64px;text-align: center;font-family: "Georgia";border:1px solid #2f83f1;}
.info-item .date h3 {font-size: 20px;color: #fff;background: #2f83f1;height: 32px;line-height: 32px;text-transform:capitalize; }
.info-item .date p {font-size: 20px;color: #6e0f6d;height: 32px;line-height: 32px;background: #fff;}
.info-item .title {}
.info-item .title a {font-weight: bold; display: block;font-size: 14px;color: #333;line-height: 24px;height: 24px;white-space:nowrap; overflow:hidden; text-overflow:ellipsis;}
.info-item .title p {font-family: "SimSun";font-size: 12px;color: #333;line-height: 22px;overflow: hidden;height: 22px;word-break:break-all;}
.info-item .title p.p1 {height: 44px;overflow: hidden;}
.info-item .title p.p2,.info-item .title p.p3,.info-item .title p.p4 {white-space:nowrap; overflow:hidden; text-overflow:ellipsis;}
.info-item:hover .title a {color: #0e8ed5;}



.lnk {background: #f3f3f4;padding: 25px 0;}
.lnk .container {padding:0 6px;}
.lnk-l .row,.lnk-r .row {margin-left: -3px;margin-right: -3px;}
.lnk-l .row .col,.lnk-r .row .col {padding-left: 3px;padding-right: 3px;}
.lnk-l-item a{display: block;padding:3px 0;}
.lnk-l-item span {display: block;width: 40px;height: 40px;margin:0 auto;}
.lnk-l-item span img {width: 100%;height: auto;}
.lnk-l-item p {font-size: 14px;color: #333;text-align: center;margin-top: 10px;}
.lnk-l-item:hover p {color: #2f83f1;}
.lnk-r-item {padding:3px 0;}
.lnk-r-item img {width: 100%;height: auto;}

.foot{background: #4d89bb url(../images/fo.jpg) no-repeat center top;padding:30px 0;font-family:"SimSun";}
.fo-l {font-size: 12px;color: #b1ddf5;line-height: 24px;text-align: center;margin-bottom: 20px;}
.fo-l a {font-size: 12px;color: #b1ddf5;line-height: 24px;}
.fo-r {width: 278px;margin:0 auto;}
.fo-r h3 {font-size: 14px;color: #aef1ff;font-weight: bold;}
.select {height: 25px;position: relative;width: 180px;margin: 6px 0;}
.select p {padding: 0 20px;cursor: pointer; line-height: 25px;border-radius: 10px;-webkit-border-radius: 10px;-ms-border-radius:10px;background: #fff;font-size: 12px;color: #9e9c9c;position: relative;}
.select p i {display: block;position: absolute;right: 15px;top: 50%;margin-top: -2px; height: 0;width: 0;border-bottom: 4px solid #585757;border-left: 4px solid transparent;border-right: 4px solid transparent;}
.select ul {position: absolute;left: 0;bottom: 25px;width:100%;display: none;}
.select ul li {background: #aad4fe;line-height: 17px;border-radius: 10px;-webkit-border-radius: 10px;-ms-border-radius:10px;font-size: 12px;color: #9e9c9c;margin-bottom: 2px;padding:4px 15px;width:100%; }
.select ul li a {color:#666;display: block;}
.select ul li a:hover {color:#0072fe;}
.fo-lnk a {display: block;float: left;background-color: #00517e;background-repeat:no-repeat;background-position:center; width: 37px;height: 37px;border-radius: 50%;-webkit-border-radius:50%;margin-left: 12px;}
.fo-lnk a.wx {background-image: url(../images/c1.png);position:relative;}
.fo-lnk a.wb {background-image: url(../images/c2.png);}
.ewm {width: 120px;height: 131px;position: absolute;left: 50%;margin-left: -60px;bottom: 37px;text-align: center;padding-top: 5px;background: url(../images/ewm_bg.png) no-repeat center;display: none;}
.ewm img {width: 110px;height: 110px;}
/*----index----*/

.p-banner {height: 255px;width: 100%;background-repeat:no-repeat;background-position: left center;}
.p-banner-pc-a {background-image:url(../images/p_banner01.jpg);}
.p-banner-pc-b {background-image:url(../images/p_banner02.jpg);}
.page-main {}
.in-main-con {background: #fff;padding-bottom: 30px;}
.pageCon > div{padding-left: 0;padding-right: 0;}
.pageCon {position: relative;}
.pageCon-left { position: absolute;left: 0;top: 0;height: 100%;background: #f7f7f7;}
.pageNav{margin-top: -60px;}
.pageNav-h {width: 100%;height: 60px;line-height: 60px;color: #fff;font-size: 18px;font-weight: normal;}
.pageNav-h a {display: block;background: #017cc0;color: #fff;font-size: 18px;padding:0 10px;}
.pageNav-ul ul {padding:0;}
.nav-one { display: block;border:1px solid #e6e6e6;border-top: none;border-left: none; line-height: 50px;background:#fefefe;position: relative;}
.nav-one a {display: block;position: relative;line-height: 20px;font-size: 14px;color: #017cc0;padding:15px 20px;}
.nav-one em {display: block; width: 4px;height: 100%;position: absolute;left: -4px;background: #f84d50;}
.nav-one.selected em {background:#ff8e43;}
.nav-one a span {margin-right: 5px;}
.nav-one a:hover {background: #1a96db;color: #fff;}
.nav-two {display: block;border:none;border-top: 1px solid #e6e6e6; line-height: 40px;background:#fbfbfb;}
.nav-two a {display: block;position: relative;line-height: 16px;font-size: 13px;color: #017cc0;padding:12px 20px 12px 30px;border:none;}
.nav-one.parent .nav-two a {background: #fff;color:#017cc0;}
.nav-one.parent .nav-two a:hover {background: #1a96db;color: #fff;}
.nav-one.parent .nav-two.selected a {background: #1a96db;color: #fff;}

.pageR {padding:5px 10px 30px;background: #fff;}
.pageR_t {width: 100%;height: 40px;overflow: hidden;position: relative;z-index: 9;}
.pageR_t p {display: block;float: left;font-size: 18px; color: #017cc0;height: 40px;line-height: 40px;position: relative;padding:0 10px;z-index: 999;}
.pageR_t_a {float: left;height: 40px;line-height: 40px;color: #999;font-size: 12px;padding:0 5px;}
.pageR_t_a a {color: #999;font-size: 12px;}
.pageR_t_a a:hover {color: #017cc0;}
.pageR .line {width: 100%;height: 2px;background: #017cc0;}

#news_list {margin:10px 0 40px 0;}
#news_list ul.news_ul li {padding: 10px 90px 10px 24px;line-height: 30px;height: 50px;position: relative;border-bottom: 1px solid #dedede;background: url(../images/li_i.png) 10px center no-repeat;}
#news_list ul.news_ul li a {display: block;width: 100%;height: 30px;line-height: 30px;font-size: 14px;color: #333;white-space:nowrap; overflow:hidden; text-overflow:ellipsis;}
#news_list ul.news_ul li span {width: 80px;position: absolute;display: block;right: 0;top: 10px;height: 30px;line-height: 30px;font-size: 12px; color: #919191;text-align: center;}
#news_list ul.news_ul li:hover a {color: #017cc0;}

.pageR_img_list .row {margin-left: -5px;margin-right: -5px;}
.pageR_img_list .row .col {padding-left: 5px;padding-right: 5px;}
.pageR_img_item {margin-top: 10px;}
.pageR_img_item .img {width: 100%;overflow: hidden;}
.pageR_img_item .txt {height: 30px;line-height: 30px;padding:0 10px;border:1px solid #ccc;font-size: 14px;color: #343b69;text-align: center;white-space:nowrap; overflow:hidden; text-overflow:ellipsis;}
.pageR_img_item:hover {box-shadow:0 0 10px 3px #ccc;-webkit-box-shadow:0 0 10px 3px #ccc;-moz-box-shadow:0 0 10px 3px #ccc;}

.pageR_article {padding:20px 0 30px;}
.pageR_article .title { line-height:26px; font-family:"Microsoft Yahei"; padding:5px; text-align:center; font-size:22px; color: #017cc0;}
.pageR_article .title_y { line-height:26px; font-family:"Microsoft Yahei"; padding:5px; text-align:left; font-size:18px; color:#787878; font-weight:normal;}
.pageR_article .title_f { line-height:26px; font-family:"Microsoft Yahei"; padding:5px; text-align:center; font-size:18px; color:#787878; font-weight:normal;}
.pageR_article .infoA {font-size: 12px;color: #787878;padding:10px;text-align: center; font-family:"Microsoft Yahei";}
.pageR_article .infoA span {display: inline-block;margin:0 5px; font-family:"Microsoft Yahei";}
.pageR_article .con,.pageR_article .con p { line-height:1.6; font-size:16px; color:#222; font-family:"Microsoft Yahei";}
.pageR_article .con p { margin-bottom:6px;/*text-indent: 2em;*/}
.pageR_article .con img {max-width: 100%!important;height: auto!important;}

.wp_entry,.wp_entry p { line-height:1.6; font-size:16px; color:#222; font-family:"Microsoft Yahei";}
.wp_entry p { margin-bottom:6px;/*text-indent: 2em;*/}
.wp_entry img { max-width:940px; _width:expression(this.width > 940 ? "940px" : this.width); display: inline-block;margin: 0 auto;}

/* 超小屏幕（手机，小于 768px） */
/* 小屏幕（平板，大于等于 768px） */
@media screen and (min-width:768px) {
.container {padding-left: 0;padding-right: 0;position: relative;}
.logo {padding:10px 0 13px;}
.in_title span {font-size: 20px;}
.news_title_item {font-size: 20px;}
.in-news-con {height: 160px;}
.in-news-con .row {height: 120px;}
.lnk .container {padding-left: 0;padding-right: 0;}
.fo-l {text-align: left;margin-bottom: 0;}
.fo-r {float: right;}

.pageR_article .con img {max-width: 100%!important;height: auto!important;}

.p-banner {background-position: center;}
.pageNav-h {text-align: center;}
.pageNav-ul {padding-left: 12px;}
.pageCon-left {border-left: 12px solid #017cc0;}/* page bg color */
.pageR_t_a {float: right;}
.listR_tL {width: auto;}
.listR_tR {float:right;width: auto;}

.pageNav ul li {float:left;width: 100%;}
.pageR {padding:30px 0 0 30px;}
.pageR-con {border-top:1px solid #ccc;border-left:1px solid #ccc;padding:10px 15px 40px;}
.pageR_news_list {margin:10px 0 40px;} 

.pageR_img_list .row {margin-left: -10px;margin-right: -10px;}
.pageR_img_list .row .col {padding-left: 10px;padding-right: 10px;}
.pageR_img_item {margin-top: 20px;}
}

/* 中等屏幕（桌面显示器，大于等于 992px） */
@media screen and (min-width:992px) {
.logo {text-align: left;}
.top_nav {float: right;}
.pc_menuCon li a {font-size: 14px;padding:0 4px;}
.type .row .col{background: none;}
.type-d {background:url(../images/nav-l.jpg) no-repeat left center;}
.in-info-con {height: 223px;}
.type-p { height:105px;}
.type-p a p { height:105px;}
}
/* 大屏幕（大桌面显示器，大于等于 1200px） */
@media screen and (min-width:1200px) {
.container {width: 1200px;}
.top_nav {padding-right:30px;}
.pc_menuCon li a {font-size: 15px;padding:0 6px;}
.in-info-con .row {margin-left: -25px;margin-right: -25px;}
.in-info-con .row .col {padding-left: 25px;padding-right: 25px;}

}
@charset"utf-8";
html {font-family:"Times New Roman","Arial","Microsoft YaHei","SimSun",sans-serif;-ms-text-size-adjust: 100%; -webkit-text-size-adjust: 100%; font-size: 14px;overflow:hidden;overflow-y:auto;}
body {font-family:"Times New Roman","Arial","Microsoft YaHei","SimSun",sans-serif; margin: 0; color: #000; line-height: 1.5; background-color: #fff; height: 100%;overflow:hidden;overflow-y:auto;}
article, aside, details, figcaption, figure, footer, header, hgroup, main, nav, section, summary { display: block; }
a { background: transparent; text-decoration: none; color: #000;transition: all 0.3s ease-out 0s;-moz-transition: all 0.3s ease-out 0s;-webkit-transition: all 0.3s ease-out 0s;-o-transition: all 0.3s ease-out 0s;}
a:active { outline: 0; }
a {-webkit-tap-highlight-color:rgba(0,0,0,0);}
b, strong { font-weight: bold; }
dfn { font-style:normal;}
img { border: 0; vertical-align: middle; }
* {
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
    -webkit-tap-highlight-color: rgba(0,0,0,0);
    -webkit-tap-highlight-color: transparent; /* For some Androids */
    outline: none;      
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}
input,textarea,button { border: 0; margin: 0; padding: 0;}
textarea { resize: none;}
table { border-collapse: collapse; border-spacing: 0; }
td, th { padding: 0; }
h1, h2, h3, h4, h5, h6, p, figure, form, blockquote { margin: 0; }
h1, h2, h3, h4, h5, h6 {font-weight: normal;}
ul, ol, li, dl, dd { margin: 0; padding: 0; }
ul, ol { list-style: none; }
input:-webkit-autofill,textarea:-webkit-autofill,select:-webkit-autofill { -webkit-box-shadow: 0 0 0 1000px white inset; }
a:focus, a:hover { text-decoration:none; outline: none;}
input { outline:none;box-sizing:border-box;vertical-align:middle;}
input::-moz-placeholder, textarea::-moz-placeholder { color: #666; }
input:-ms-input-placeholder, textarea:-ms-input-placeholder { color: #666; }
input::-webkit-input-placeholder, textarea::-webkit-input-placeholder { color: #666; }
/* Grid
----------------------------------------------------------------------------- */
.container{position: relative; margin-right: auto;margin-left: auto;}
.container-pd {padding-left:15px;padding-right:15px;}
/* Row */
.row:before,.container:before,.row:after,.container:after{content:""; display:table;}   
.row:after,.container:after {clear:both;}   
.row,.container { *zoom:1;}
.row {
    margin-right: -15px;
    margin-left: -15px;
}
/* Column */
.form-control {
    display: block;
    width: 100%;
    height: 34px;
    padding: 6px 12px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555;
    background-color: #fff;
    background-image: none;
    border: 1px solid #ccc;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    -webkit-transition: border-color ease-in-out .15s, -webkit-box-shadow ease-in-out .15s;
    -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.btn {
    display: inline-block;
    padding: 6px 12px;
    margin-bottom: 0;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.42857143;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    -ms-touch-action: manipulation;
    touch-action: manipulation;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px;
}
.btn-block {
    display: block;
    width: 100%;
}
.input-lg {
    height: 46px;
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px;
}
.col {
	display: block;
	width: 100%;
	float: left;
    position: relative;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;	
}
.xs-0 {display: none;}
.xs-1, .xs-2, .xs-3, .xs-4, .xs-5, .xs-6, .xs-7, .xs-8, .xs-9, .xs-10, .xs-11, .xs-12 {display: block;}
.xs-1  {width: 8.3333%;}
.xs-2  {width: 16.6667%;}
.xs-3  {width: 25%;}
.xs-4  {width: 33.3333%;}
.xs-5  {width: 41.6667%;}
.xs-6  {width: 50%;}
.xs-7  {width: 58.3333%;}
.xs-8  {width: 66.6667%;}
.xs-9  {width: 75%;}
.xs-10 {width: 83.3333%;}
.xs-11 {width: 91.6667%;}
.xs-12 {width: 100%;}
.xs-offset-12{margin-left: 100%;}
.xs-offset-11{margin-left: 91.66666667%;}
.xs-offset-10{margin-left: 83.33333333%;}
.xs-offset-9{margin-left: 75%;}
.xs-offset-8{margin-left: 66.66666667%;}
.xs-offset-7{margin-left: 58.33333333%;}
.xs-offset-6{margin-left: 50%;}
.xs-offset-5{margin-left: 41.66666667%;}
.xs-offset-4{margin-left: 33.33333333%;}
.xs-offset-3{margin-left: 25%;}
.xs-offset-2{margin-left: 16.66666667%;}
.xs-offset-1{margin-left: 8.33333333%;}
.xs-offset-0{margin-left: 0%;}	
.hidden-xs {display: none!important;}
.visible-xs {display: block!important;}
.hidden-sm {display: block!important;}
.visible-sm {display: none!important;}
.hidden-md {display: block!important;}
.visible-md {display: none!important;}
.hidden-lg {display: block!important;}
.visible-lg {display: none!important;}
.hidden-xs-sm {display: none!important;}
.visible-xs-sm {display: block!important;}
.hidden-xs-sm-md {display: none!important;}
.visible-xs-sm-md {display: block!important;}
.hidden-xs-md {display: none!important;}
.visible-xs-md {display: block!important;}
/*------meanMenu.css----- begin*/

a.meanmenu-reveal{display:none}
.mean-container {min-height: 50px;}
.mean-container .mean-bar{float:left;width:100%;position:relative;min-height:50px;z-index:999;font-size: 14px;}
.mean-container a.meanmenu-reveal{width:30px;height:22px;padding:11px 13px 17px;position:absolute;top:0;right:0;cursor:pointer;color:#fff;text-decoration:none;font-size:16px;text-indent:-9999em;line-height:30px;font-size:1px;display:block;font-family:Arial, Helvetica, sans-serif;font-weight:700}
.mean-container a.meanmenu-reveal span{display:block;background:#fff;height:3px;margin-top:5px}
.mean-container .mean-nav{float:left;width:100%;background:rgba(182,1,21,0.9);/*bg-color*/margin-top:50px;position: absolute;left: 0;top: 0;}
.mean-container .mean-nav ul{padding:0;margin:0;width:100%;list-style-type:none}
.mean-container .mean-nav ul li{position:relative;float:left;width:100%}
.mean-container .mean-nav ul li a{display:block;float:left;width:90%;line-height: 20px;padding:7px 5%;margin:0;text-align:left;color:#fff;border-bottom:1px solid #383838;border-bottom:1px solid rgba(255, 255, 255, .5);text-decoration:none;text-transform:uppercase}
.mean-container .mean-nav ul li li a{width:80%;padding:7px 10%;border-bottom:1px solid #f1f1f1;border-bottom:1px solid rgba(255, 255, 255, .25);opacity:.75;filter:alpha(opacity=75);text-shadow:none!important;visibility:visible}
.mean-container .mean-nav ul li.mean-last a{border-bottom:0;margin-bottom:0}
.mean-container .mean-nav ul li li li a{width:70%;padding:7px 15%}
.mean-container .mean-nav ul li li li li a{width:60%;padding:1em 20%}
.mean-container .mean-nav ul li li li li li a{width:50%;padding:1em 25%}
.mean-container .mean-nav ul li a:hover{background:#252525;background:rgba(255, 255, 255, .1)}
.mean-container .mean-nav ul li a.mean-expand{margin-top:0px;width:20px;height:10px;line-height: 10px;padding:12px!important;text-align:center;position:absolute;right:0;top:0;z-index:2;font-weight:700;background:rgba(255, 255, 255, .1);border:0!important;border-left:1px solid rgba(255, 255, 255, .4)!important;border-bottom:1px solid rgba(255, 255, 255, .2)!important}
.mean-container .mean-push{float:left;width:100%;padding:0;margin:0;clear:both}
.mean-nav .wrapper{width:100%;padding:0;margin:0}
.mean-container .mean-bar, .mean-container .mean-bar *{-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box}
.mean-remove{display:none!important}
.mean-container .meanmenu-title{position: absolute;width: 100px;height: 50px;left: 0;top: 0;display: block;font-size: 16px;color: #fff;display: inline-block;padding:0 15px;line-height: 50px;}
/*------meanMenu.css----- end*/
/*------jquery.bxslider.css begin-----*/
.bx-wrapper{position: relative;margin: 0 auto;padding: 0;*zoom: 1;}
.bx-wrapper img{width: 100%;display: block;}
.bx-wrapper .bx-viewport{-webkit-transform: translatez(0);-moz-transform: translatez(0);-ms-transform: translatez(0);-o-transform: translatez(0);transform: translatez(0);}
.bx-wrapper .bx-pager,.bx-wrapper .bx-controls-auto{position: absolute;bottom: -30px;width: 100%;}
.bx-wrapper .bx-controls-auto{display: none;}
.bx-wrapper .bx-loading{min-height: 50px;background: url(../images/bx_loader.gif) center center no-repeat #fff;height: 100%;width: 100%;position: absolute;top: 0;left: 0;z-index: 60;}
.bx-wrapper .bx-pager{text-align: center;font-size: .85em;font-family: Arial;font-weight: bold;color: #666;}
.bx-wrapper .bx-pager .bx-pager-item,
.bx-wrapper .bx-controls-auto .bx-controls-auto-item{display: inline-block;*zoom: 1;*display: inline;}
.bx-wrapper .bx-pager.bx-default-pager a{background: #666;text-indent: -9999px;display: block;width: 10px;height: 10px;margin: 0 5px;outline: 0;-moz-border-radius: 5px;-webkit-border-radius: 5px;border-radius: 5px;}
.bx-wrapper .bx-pager.bx-default-pager a:hover,
.bx-wrapper .bx-pager.bx-default-pager a.active{background: #000;}
.bx-wrapper .bx-prev{left: 10px;background: url(../images/controls.png) no-repeat 0 -32px;}
.bx-wrapper .bx-next{right: 10px;background: url(../images/controls.png) no-repeat -43px -32px;}
.bx-wrapper .bx-prev:hover{background-position: 0 0;}
.bx-wrapper .bx-next:hover{background-position: -43px 0;}
.bx-wrapper .bx-controls-direction a{position: absolute;top: 50%;margin-top: -16px;outline: 0;width: 32px;height: 32px;text-indent: -9999px;z-index: 130;}
.bx-wrapper .bx-controls-direction a.disabled{display: none;}
.bx-wrapper .bx-controls-auto{text-align: center;}
.bx-wrapper .bx-controls-auto .bx-start{display: block;text-indent: -9999px;width: 10px;height: 11px;outline: 0;background: url(../images/controls.png) -86px -11px no-repeat;margin: 0 3px;}
.bx-wrapper .bx-controls-auto .bx-start:hover,
.bx-wrapper .bx-controls-auto .bx-start.active{background-position: -86px 0;}
.bx-wrapper .bx-controls-auto .bx-stop{display: block;text-indent: -9999px;width: 9px;height: 11px;outline: 0;background: url(../images/controls.png) -86px -44px no-repeat;margin: 0 3px;}
.bx-wrapper .bx-controls-auto .bx-stop:hover,
.bx-wrapper .bx-controls-auto .bx-stop.active{background-position: -86px -33px;}
.bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-pager{text-align: center;width: 100%;position: absolute;left: 0;bottom: 20px;z-index: 130;}
.bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-controls-auto{right: 0;width: 35px;}
.bx-wrapper .bx-caption{position: absolute;bottom: 0;left: 0;background: #666\9;background: rgba(80, 80, 80, 0.75);width: 100%;}
.bx-wrapper .bx-caption span{color: #fff;font-family: Arial;display: block;font-size: .85em;padding: 10px;}
/*------jquery.bxslider.css end-----*/

@media (min-width: 768px) {
	.container-pd {padding-left:0;padding-right:0;}
	.container{width: 750px;}
	.sm-0 {display: none;}
	.sm-1, .sm-2, .sm-3, .sm-4, .sm-5, .sm-6, .sm-7, .sm-8, .sm-9, .sm-10, .sm-11, .sm-12 {display: block;}
	.sm-1  {width: 8.3333%;}
	.sm-2  {width: 16.6667%;}
	.sm-3  {width: 25%;}
	.sm-4  {width: 33.3333%;}
	.sm-5  {width: 41.6667%;}
	.sm-6  {width: 50%;}
	.sm-7  {width: 58.3333%;}
	.sm-8  {width: 66.6667%;}
	.sm-9  {width: 75%;}
	.sm-10 {width: 83.3333%;}
	.sm-11 {width: 91.6667%;}
	.sm-12 {width: 100%;}
    .sm-offset-12{margin-left: 100%;}
	.sm-offset-11{margin-left: 91.66666667%;}
	.sm-offset-10{margin-left: 83.33333333%;}
	.sm-offset-9{margin-left: 75%;}
	.sm-offset-8{margin-left: 66.66666667%;}
	.sm-offset-7{margin-left: 58.33333333%;}
	.sm-offset-6{margin-left: 50%;}
	.sm-offset-5{margin-left: 41.66666667%;}
	.sm-offset-4{margin-left: 33.33333333%;}
	.sm-offset-3{margin-left: 25%;}
	.sm-offset-2{margin-left: 16.66666667%;}
	.sm-offset-1{margin-left: 8.33333333%;}
	.sm-offset-0{margin-left: 0%;}
	.hidden-xs {display: block!important;}
    .visible-xs {display: none!important;}		
	.hidden-sm {display: none!important;}
	.visible-sm {display: block!important;}
	.hidden-md {display: block!important;}
	.visible-md {display: none!important;}
    .hidden-lg {display: block!important;}
	.visible-lg {display: none!important;}
	.hidden-xs-sm {display: none!important;}
	.visible-xs-sm {display: block!important;}
	.hidden-xs-sm-md {display: none!important;}
	.visible-xs-sm-md {display: block!important;}	
	.hidden-xs-md {display: block!important;}
	.visible-xs-md {display: none!important;}			
}

@media (min-width: 992px) {
	.container{width: 970px;}
	.md-0 {display: none;}
	.md-1, .md-2, .md-3, .md-4, .md-5, .md-6, .md-7, .md-8, .md-9, .md-10, .md-11, .md-12 {display: block;}
	.md-1  {width: 8.3333%;}
	.md-2  {width: 16.6667%;}
	.md-3  {width: 25%;}
	.md-4  {width: 33.3333%;}
	.md-5  {width: 41.6667%;}
	.md-6  {width: 50%;}
	.md-7  {width: 58.3333%;}
	.md-8  {width: 66.6667%;}
	.md-9  {width: 75%;}
	.md-10 {width: 83.3333%;}
	.md-11 {width: 91.6667%;}
	.md-12 {width: 100%;}
    .md-offset-12{margin-left: 100%;}
	.md-offset-11{margin-left: 91.66666667%;}
	.md-offset-10{margin-left: 83.33333333%;}
	.md-offset-9{margin-left: 75%;}
	.md-offset-8{margin-left: 66.66666667%;}
	.md-offset-7{margin-left: 58.33333333%;}
	.md-offset-6{margin-left: 50%;}
	.md-offset-5{margin-left: 41.66666667%;}
	.md-offset-4{margin-left: 33.33333333%;}
	.md-offset-3{margin-left: 25%;}
	.md-offset-2{margin-left: 16.66666667%;}
	.md-offset-1{margin-left: 8.33333333%;}
	.md-offset-0{margin-left: 0%;}	
	.hidden-xs {display: block!important;}
    .visible-xs {display: none!important;}
    .hidden-sm {display: block!important;}
    .visible-sm {display: none!important;}
	.hidden-md {display: none!important;}
	.visible-md {display: block!important;}
    .hidden-lg {display: block!important;}
	.visible-lg {display: none!important;}
	.hidden-xs-sm {display: block!important;}
	.visible-xs-sm {display: none!important;}
	.hidden-xs-sm-md {display: none!important;}
	.visible-xs-sm-md {display: block!important;}
	.hidden-xs-md {display: none!important;}
	.visible-xs-md {display: block!important;}				
}



@media (min-width: 1200px) {
	.container{width: 1200px;}
	.lg-0 {display: none;}
	.lg-1, .lg-2, .lg-3, .lg-4, .lg-5, .lg-6, .lg-7, .lg-8, .lg-9, .lg-10, .lg-11, .lg-12 {display: block;}
	.lg-1  {width: 8.3333%;}
	.lg-2  {width: 16.6667%;}
	.lg-3  {width: 25%;}
	.lg-4  {width: 33.3333%;}
	.lg-5  {width: 41.6667%;}
	.lg-6  {width: 50%;}
	.lg-7  {width: 58.3333%;}
	.lg-8  {width: 66.6667%;}
	.lg-9  {width: 75%;}
	.lg-10 {width: 83.3333%;}
	.lg-11 {width: 91.6667%;}
	.lg-12 {width: 100%;}
    .lg-offset-12{margin-left: 100%;}
	.lg-offset-11{margin-left: 91.66666667%;}
	.lg-offset-10{margin-left: 83.33333333%;}
	.lg-offset-9{margin-left: 75%;}
	.lg-offset-8{margin-left: 66.66666667%;}
	.lg-offset-7{margin-left: 58.33333333%;}
	.lg-offset-6{margin-left: 50%;}
	.lg-offset-5{margin-left: 41.66666667%;}
	.lg-offset-4{margin-left: 33.33333333%;}
	.lg-offset-3{margin-left: 25%;}
	.lg-offset-2{margin-left: 16.66666667%;}
	.lg-offset-1{margin-left: 8.33333333%;}
	.lg-offset-0{margin-left: 0%;}
	.hidden-xs {display: block!important;}
    .visible-xs {display: none!important;}
    .hidden-sm {display: block!important;}
    .visible-sm {display: none!important;}
	.hidden-md {display: block!important;}
	.visible-md {display: none!important;}    		
	.hidden-lg {display: none!important;}
	.visible-lg {display: block!important;}
	.hidden-xs-sm {display: block!important;}
	.visible-xs-sm {display: none!important;}
	.hidden-xs-sm-md {display: block!important;}
	.visible-xs-sm-md {display: none!important;}
	.hidden-xs-md {display: block!important;}
	.visible-xs-md {display: none!important;}			
}
.bbit-dp
{
    position:absolute;
    width:175px;    
    border:#718bb7 1px solid;
    overflow:hidden;
    zoom:1;
    padding:0;
    font-size:11px;
    font-family:tahoma,verdana,sans-serif;
    visibility:hidden;
    background:#fff;
    left:0px;
    top:0px;
}
.bbit-dp em
{
 font-style:normal;
 font-weight:normal;    
}
.bbit-dp table
{
    width:100%;   
    table-layout: fixed;
    border-collapse: separate;
}
.bbit-dp td th
{
    margin:0px;
}
.bbit-dp-top-center
{
    font:normal 11px tahoma,verdana,helvetica;
    cursor:pointer;
    white-space:nowrap;
    color:#fff;   
    text-align:center;
}

.bbit-dp-top-center button
{
     font-size:13px;
    border:0 none;
    padding-right:10px;    
    background:transparent url(images/dp/btn-arrow-light.gif) no-repeat top right;
    font:normal 11px tahoma,verdana,helvetica;
    padding-left:3px; 
    color:#fff;
    cursor:pointer;
    margin:0;
    overflow:visible;
    width:auto;
    -moz-outline:0 none;
    outline:0 none;
   
}
.ie .bbit-dp-top-center button
{
    
}
.bbit-dp-top-right
{
    height:21px;
}

.bbit-dp .bbit-dp-top
{
   background:url("images/dp/hd-sprite.gif") repeat-x 0px -83px; 
}
.bbit-dp-top-right,.bbit-dp-top-left{width:18px;}
.bbit-dp-top-right{text-align:right;}

.bbit-dp-top-right a,.bbit-dp-top-left a
{
    display:block;
    width:16px;
    height:16px;
    background-position:center;
    background-repeat:no-repeat;
    cursor:pointer;
    -moz-opacity:0.6;
    opacity:0.6;
    filter:alpha(opacity=60);
}
.bbit-dp-top-right a:hover,.bbit-dp-top-left a:hover
{
    -moz-opacity:1;
    opacity:1;
    filter:alpha(opacity=100);
}

.bbit-dp-top-left a
{
    background:url(images/dp/left-btn.gif); MARGIN-LEFT: 2px
}
.bbit-dp-top-right a
{
    background:url(images/dp/right-btn.gif); MARGIN-LEFT: 2px
}
.bbit-dp-inner th,.bbit-dp-inner td{
border-collapse:separate;
}

.bbit-dp-inner th
{
   width:25px;
   background:#dfecfb url(images/dp/glass-bg.gif) repeat-x left top;
   text-align:right!important;
   border-bottom:1px solid #a3bad9;  
   color:#233d6d;
   cursor:default;
   padding:0;
   border-collapse:separate;
}
.bbit-dp-inner th span
{
    display:block;
    padding:2px;
    padding-right:7px;
    font:normal 10px arial,helvetica,tahoma,sans-serif;
}
.bbit-dp-inner td
{
    border:1px solid #fff;text-align:right;padding:0;
    border-collapse:separate;
    color:Black;
}
.bbit-dp a
{   
    text-decoration:none;
    color:black; 
    zoom:1; 
}
.bbit-dp-inner td a
{
    font:normal 11px arial,helvetica,tahoma,sans-serif;
    padding:2px 5px;
    display:block;  
    text-align:right;   
}

.bbit-dp-inner .bbit-dp-active{cursor:pointer;color:black;}
.bbit-dp-inner .bbit-dp-selected a{background:#dfecfb url(../images/default/shared/glass-bg.gif) repeat-x left top;border:1px solid #8db2e3;padding:1px 4px;}
.bbit-dp-inner .bbit-dp-today a{border:1px solid darkred;padding:1px 4px;}
.bbit-dp-inner .bbit-dp-selected span{font-weight:bold;}
.bbit-dp-inner .bbit-dp-prevday a,.bbit-dp-inner .bbit-dp-nextday a{color:#aaa;text-decoration:none!important;}
.bbit-dp-inner a:hover,.bbit-dp-inner bbit-dp-disabled a:hover{text-decoration:none!important;color:black;background:#ddecfe;}
.bbit-dp-inner .bbit-dp-disabled a{cursor:default;background:#eee;color:#bbb;}

.bbit-dp-bottom{padding:2px;border-top:1px solid #a3bad9;background:#dfecfb url(images/dp/glass-bg.gif) repeat-x left top;}
/*.bbit-dp-bottom button {text-decoration:none;text-align:center;text-decoration:none!important;background:#083772;color:white;border:1px solid;border-color:#36c #005 #005 #36c;padding:1px 3px 1px;font:normal 11px arial,helvetica,tahoma,sans-serif;cursor:pointer;}*/
.bbit-dp-mp{position:absolute;left:0;top:0;background:white;display:none;}
            
.bbit-dp-mp td{padding:2px;font:normal 11px arial,helvetica,tahoma,sans-serif;}
td.bbit-dp-mp-month,td.bbit-dp-mp-year,td.bbit-dp-mp-ybtn{border:0 none;text-align:center;vertical-align:middle;width:25%;}
.bbit-dp-mp-ok{margin-right:3px;}
.bbit-dp-mp-btns button{text-decoration:none;text-align:center;text-decoration:none!important;background:#083772;color:white;border:1px solid;border-color:#36c #005 #005 #36c;padding:1px 3px 1px;font:normal 11px arial,helvetica,tahoma,sans-serif;cursor:pointer;}
.bbit-dp-mp-btns{background:#dfecfb url(images/dp/glass-bg.gif) repeat-x left top;}
.bbit-dp-mp-btns td{border-top:1px solid #c5d2df;text-align:center;}
td.bbit-dp-mp-month a,td.bbit-dp-mp-year a{display:block;padding:2px 4px;text-decoration:none;text-align:center;color:#15428b;}
td.bbit-dp-mp-month a:hover,td.bbit-dp-mp-year a:hover{color:#15428b;text-decoration:none;cursor:pointer;background:#ddecfe;}
td.bbit-dp-mp-sel a{padding:1px 3px;background:#dfecfb url(images/dp/glass-bg.gif) repeat-x left top;border:1px solid #8db2e3;}
.bbit-dp-mp-ybtn a{overflow:hidden;width:15px;height:15px;cursor:pointer;background:transparent url(images/dp/tool-sprites.gif) no-repeat;display:block;margin:0 auto;}
.bbit-dp-mp-ybtn a.bbit-dp-mp-next{background-position:0 -120px;}
.bbit-dp-mp-ybtn a.bbit-dp-mp-next:hover{background-position:-15px -120px;}
.bbit-dp-mp-ybtn a.bbit-dp-mp-prev{background-position:0 -105px;}
.bbit-dp-mp-ybtn a.bbit-dp-mp-prev:hover{background-position:-15px -105px;}
.bbit-dp-mp-ybtn{text-align:center;}
td.bbit-dp-mp-sep{border-right:1px solid #c5d2df;}


.bbit-dp-input
{
    width:100px;
    height:18px;
    padding-left:4px;
}
.owl-carousel .animated{-webkit-animation-duration:1000ms;animation-duration:1000ms;-webkit-animation-fill-mode:both;animation-fill-mode:both}.owl-carousel .owl-animated-in{z-index:0}.owl-carousel .owl-animated-out{z-index:1}.owl-carousel .fadeOut{-webkit-animation-name:fadeOut;animation-name:fadeOut}@-webkit-keyframes fadeOut{0%{opacity:1}100%{opacity:0}}@keyframes fadeOut{0%{opacity:1}100%{opacity:0}}.owl-height{-webkit-transition:height 500ms ease-in-out;-moz-transition:height 500ms ease-in-out;-ms-transition:height 500ms ease-in-out;-o-transition:height 500ms ease-in-out;transition:height 500ms ease-in-out}.owl-carousel{display:none;width:100%;-webkit-tap-highlight-color:transparent;position:relative;z-index:1}.owl-carousel .owl-stage{position:relative;-ms-touch-action:pan-Y}.owl-carousel .owl-stage:after{content:".";display:block;clear:both;visibility:hidden;line-height:0;height:0}.owl-carousel .owl-stage-outer{position:relative;overflow:hidden;-webkit-transform:translate3d(0px,0,0)}.owl-carousel .owl-controls .owl-dot,.owl-carousel .owl-controls .owl-nav .owl-next,.owl-carousel .owl-controls .owl-nav .owl-prev{cursor:pointer;cursor:hand;-webkit-user-select:none;-khtml-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel.owl-loaded{display:block}.owl-carousel.owl-loading{opacity:0;display:block}.owl-carousel.owl-hidden{opacity:0}.owl-carousel .owl-refresh .owl-item{display:none}.owl-carousel .owl-item{position:relative;min-height:1px;float:left;-webkit-backface-visibility:hidden;-webkit-tap-highlight-color:transparent;-webkit-touch-callout:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel .owl-item img{-webkit-transform-style:preserve-3d}.owl-carousel.owl-text-select-on .owl-item{-webkit-user-select:auto;-moz-user-select:auto;-ms-user-select:auto;user-select:auto}.owl-carousel .owl-grab{cursor:move;cursor:-webkit-grab;cursor:-o-grab;cursor:-ms-grab;cursor:grab}.owl-carousel.owl-rtl{direction:rtl}.owl-carousel.owl-rtl .owl-item{float:right}.no-js .owl-carousel{display:block}.owl-carousel .owl-item .owl-lazy{opacity:0;-webkit-transition:opacity 400ms ease;-moz-transition:opacity 400ms ease;-ms-transition:opacity 400ms ease;-o-transition:opacity 400ms ease;transition:opacity 400ms ease}.owl-carousel .owl-item img{transform-style:preserve-3d}.owl-carousel .owl-video-wrapper{position:relative;height:100%;background:#000}.owl-carousel .owl-video-play-icon{position:absolute;height:80px;width:80px;left:50%;top:50%;margin-left:-40px;margin-top:-40px;background:url(owl.video.play.png) no-repeat;cursor:pointer;z-index:1;-webkit-backface-visibility:hidden;-webkit-transition:scale 100ms ease;-moz-transition:scale 100ms ease;-ms-transition:scale 100ms ease;-o-transition:scale 100ms ease;transition:scale 100ms ease}.owl-carousel .owl-video-play-icon:hover{-webkit-transition:scale(1.3,1.3);-moz-transition:scale(1.3,1.3);-ms-transition:scale(1.3,1.3);-o-transition:scale(1.3,1.3);transition:scale(1.3,1.3)}.owl-carousel .owl-video-playing .owl-video-play-icon,.owl-carousel .owl-video-playing .owl-video-tn{display:none}.owl-carousel .owl-video-tn{opacity:0;height:100%;background-position:center center;background-repeat:no-repeat;-webkit-background-size:contain;-moz-background-size:contain;-o-background-size:contain;background-size:contain;-webkit-transition:opacity 400ms ease;-moz-transition:opacity 400ms ease;-ms-transition:opacity 400ms ease;-o-transition:opacity 400ms ease;transition:opacity 400ms ease}.owl-carousel .owl-video-frame{position:relative;z-index:1}
/* 
 * 	Default theme - Owl Carousel CSS File
 */
.owl-theme .owl-controls {
  margin-top: 25px;
}
.owl-theme .owl-nav {
  text-align: center;
  -webkit-tap-highlight-color: transparent;
}
.owl-theme .owl-nav [class*='owl-'] {
  color: white;
  display: inline-block;
  cursor: pointer;
}
.owl-theme .owl-nav .disabled {
  opacity: 0.5;
  cursor: default;
}
.owl-theme .owl-nav.disabled + .owl-dots {
  margin-top: 10px;
}
.owl-theme .owl-dots {
  text-align: center;
  -webkit-tap-highlight-color: transparent;
}
.owl-theme .owl-dots .owl-dot {
  display: inline-block;
  zoom: 1;
  *display: inline;
}
.owl-theme .owl-dots .owl-dot span {
  width: 12px;
  height: 12px;
  margin: 1px 5px;
  background: #9f9b9b;
  display: block;
  -webkit-backface-visibility: visible;
  -webkit-transition: opacity 200ms ease;
  -moz-transition: opacity 200ms ease;
  -ms-transition: opacity 200ms ease;
  -o-transition: opacity 200ms ease;
  transition: opacity 200ms ease;
  -webkit-border-radius: 30px;
  -moz-border-radius: 30px;
  border-radius: 30px;
}
.owl-theme .owl-dots .owl-dot.active span, .owl-theme .owl-dots .owl-dot:hover span {
  background: #1e2b63;
}

@import "system_editor.css";
.wp_nav { display:block; margin: 0; padding: 0;display: block; *zoom:1;}
.wp_nav * {margin: 0; padding: 0}
.wp_nav:after {clear: both;content: ".";display: block;height: 0;visibility: hidden;}
.wp_nav .nav-item { display:inline-block; float:left; position:relative; vertical-align:bottom;}
.wp_nav .on { z-index:10;}
.wp_nav .nav-item .mark {display:block; width:100%; height:100%; position:absolute; left:0;top:0; z-index:99; }
.wp_nav .nav-item a{ font-family:"Microsoft Yahei"; display:block;text-align:center;position:relative; z-index:100;}
.wp_nav .nav-item a.parent:hover{}
.wp_nav .nav-item a.parent {color:#000;}
.wp_nav .nav-item a span.item-name { display:inline-block; padding:5px 10px; line-height:22px;cursor:pointer;}
.wp_nav .sub-nav {display:block; width:100%; position:absolute; z-index:200; visibility:hidden; border:1px solid #ccc;border-top:none;}
.wp_nav .sub-nav .nav-item { white-space:nowrap; }
.wp_nav .sub-nav .nav-item .mark { background:#fff;}
.wp_nav .sub-nav .nav-item a {font-family:"Microsoft Yahei"; font-size:13px;font-weight:normal; color:#000;text-align:left;border-top:1px solid #D8E1CC;min-width: 80px;}
.wp_nav .sub-nav .nav-item a.parent:hover{ background:#eee;color:#000;}
.wp_nav .sub-nav .nav-item a.parent { background:#eee;color:#000;}
.wp_nav .sub-nav .nav-item a span.item-name { padding:5px 10px; line-height:22px;}
.wp_nav .nav-item a.parent:hover span.item-name{}
.wp_nav .nav-item a.parent span.item-name{}
.wp_nav .sub-nav .nav-item a.parent:hover span.item-name{}
.wp_nav .sub-nav .nav-item a.parent span.item-name{}
/* 
    Document   : simplenews
    Created on : 2013-9-18, 15:30:07
    Author     : cpzheng
    Description:
        Purpose of the stylesheet follows.
*/
.possplit{background-image: url(posSplit.gif);background-repeat: no-repeat;background-position: left center;text-indent: 22px;background-position: center;width: 10px;display: inline-block; border: 0px solid red;}

/**更多：more**/
.more {text-align:right; margin-top:3px;}
.more a.more-link { color:#525252;}
.more a.more-link:hover { color:#000;}
.more-link .moretext { display:inline;}
.more-link .moretext img { vertical-align:bottom;}
/**文章列表:Table**/
.wp_article_list_table .list_item { line-height:23px; color:#454545;}
.wp_article_list_table .list_item .count {width:20px; overflow:hidden;}
.wp_article_list_table .list_item .count .item_num {width:15px; height:23px; background:url(wp_article_li_1.png) no-repeat 8px 10px; text-indent:-99em; overflow:hidden;}
.wp_article_list_table .list_item .field { white-space:nowrap;}
/**文章列表:UL**/
.wp_article_list{ display:block; width:100%;}
.wp_article_list .list_item { width:100%; height:24px; line-height:24px; border-bottom:1px dashed #ccc; vertical-align:top; }
.wp_article_list .list_item span { display:inline-block; vertical-align:top; float:left; margin-left:5px;}
.wp_article_list .list_item .pr_fields { display:inline; float:left;}
.wp_article_list .list_item .Article_Index { display:inline-block; width:10px; height:16px; margin-top:3px; color:#fff; font-size:11px;float:left; margin-right:5px; overflow:hidden; text-indent:-99em; background:url(wp_article_li_1.png) no-repeat 50%;}
.wp_article_list .list_item .Article_Title { float: left;}
.wp_article_list .list_item .ex_fields { display:inline; float:right;}
.wp_article_list .list_item .Article_PublishDate { color:#666;}
.wp_article_list .list_item .Article_VisitCount { color:#999;}
/**子栏目文章列表**/
.wp_subcolumn_list { display:block; width:100%;}
.wp_subcolumn_list .wp_sublist { margin-bottom:20px;}
.wp_subcolumn_list .wp_sublist .sublist_title { display:block; height:32px; line-height:32px; border-bottom:2px solid #C00; margin-bottom:10px;}
.wp_subcolumn_list .wp_sublist .sublist_title a { display:inline-block; color:#393939; font-size:14px; font-weight:bold;}
.wp_subcolumn_list .wp_sublist .sublist_title a:hover { color:#999;}
.wp_subcolumn_list .wp_sublist .sublist_title a .subcolumn-name { cursor:pointer;}
/**子栏目文章列表更多：more**/
.wp_subcolumn_list .wp_sublist .sublist_title a.morelink { color:#525252;float:right;}
.wp_subcolumn_list .wp_sublist .sublist_title a.morelink:hover { color:#000;}
.wp_subcolumn_list .wp_sublist .sublist_title .morelink .moretext { display:inline-block;}
.wp_subcolumn_list .wp_sublist .sublist_title .morelink .moretext img { vertical-align:bottom;}
.wp_subcolumn_list .wp_sublist .sublist_title a.morelink { margin-top:11px;}


/***文章内容初始样式（包括之后文章页内容）***/
.wp_entry { width:100%; line-height:1.7em; font-size:13px; color:#333; overflow:hidden;}
.wp_entry p { text-indent:0em; margin-bottom:5px;}
.wp_entry a { color:#5A5A5A;}
.wp_entry a:hover { text-decoration:underline; color:#E10000;}
.wp_entry img { max-width:640px; _width::expression(this.width>640?"640px":this.width+"px");}

/***文章内容分页***/
.wp_single .single_paging { text-align:center;}
.wp_single .single_paging a.paging-nav { display:inline-block; height:20px; line-height:20px; font-weight:bold; padding:0 7px; font-size:13px; cursor:pointer; background:#eee; border:1px solid #ccc; border-radius:3px; overflow:hidden; vertical-align: bottom; margin:0 2px; text-decoration: none;}
.wp_single .single_paging a.paging-nav:hover { color:#fff; background:#999; border-color:#666; }
.wp_single .single_paging a.current { background:#999; border-color:#666; color:#fff;}

/* 列表页－栏目列表 */
.wp_listcolumn { display:block; width:100%; border-top:1px solid #ddd; border-bottom:1px solid #fff;}
.wp_listcolumn .wp_column {display:block; width:100%; vertical-align: bottom;}
.wp_listcolumn .wp_column a { display:block; width:100%; color:#666; font-size:15px; font-weight:bold; word-wrap:break-word; background:#f5f5f5 url(wp_column_menu_li_1.gif) no-repeat 6px 12px; border-bottom:1px solid #ddd; border-top:1px solid #fff; text-align: left;}
.wp_listcolumn .wp_column a:hover { color:#C00; background-color:#f9f9f9; background-image: url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_column a.selected { color:#000; background-color:#e8e8e8; background-image: url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_column a .column-name { display:inline-block; line-height:22px; padding:5px 10px 5px 20px; cursor:pointer;}
/**二级栏目**/
.wp_listcolumn .wp_subcolumn { border-top:1px solid #fff;}
.wp_listcolumn .wp_subcolumn .wp_column a { color:#555; font-size:14px; border-bottom:1px solid #aaa; border-top:none; background:#f1f1f1 url(wp_column_menu_li_1.gif) no-repeat 16px 10px;}
.wp_listcolumn .wp_subcolumn .wp_column a:hover { color:#C30; background-color:#f7f7f7; background-image:url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_column a.selected { color:#000; background-color:#e8e8e8; background-image: url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_column a .column-name { line-height:20px; padding-left:30px;}
/**三级栏目**/
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_column a { color:#444; font-size:13px; background:#e9e9e9 url(wp_column_menu_li_1.gif) no-repeat 26px 9px; font-weight:normal;}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_column a:hover { color:#C30; background-color:#f4f4f4; background-image:url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_column a.selected { color:#000; background-color:#e8e8e8; background-image: url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_column a .column-name { line-height:18px; padding-left:40px;}
/**四级栏目**/
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a { color:#333; font-size:12px; background:#d9d9d9 url(wp_column_menu_li_1.gif) no-repeat 36px 9px;}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a:hover { color:#C30; background-color:#f4f4f4; background-image:url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a.selected { color:#000; background-color:#e8e8e8; background-image: url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a .column-name { line-height:16px; padding-left:50px;}
/**五级栏目及其子栏目**/
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a { color:#222; font-size:12px; background:#c9c9c9 url(wp_column_menu_li_1.gif) no-repeat 46px 8px;}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a:hover { color:#C30; background-color:#f1f1f1; background-image:url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a.selected { color:#000; background-color:#e8e8e8; background-image: url(wp_column_menu_li_2.gif);}
.wp_listcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_subcolumn .wp_column a .column-name { line-height:16px; padding-left:60px;}

/**子栏目列表：横向**/
.wp_listcolumn_x { display:block; width:100%;}
.wp_listcolumn_x:after { content:"."; display:block; width:100%; height:0; overflow:hidden;}
.wp_listcolumn_x .wp_column {display:inline-block; float:left; vertical-align: bottom;}
.wp_listcolumn_x .wp_column a { display:inline-block; color:#555; font-size:15px; font-weight:bold; background:#ddd;}
.wp_listcolumn_x .wp_column a:hover { color:#C00; background-color:#e8e8e8;}
.wp_listcolumn_x .wp_column a.selected { color:#000; background-color:#f8f8f8; }
.wp_listcolumn_x .wp_column a .column-name { display:inline-block; line-height:30px; padding:0 10px; cursor:pointer;}

/** 分页栏 **/
.wp_paging { display:block; margin:0; padding:0; list-style:none; font-size:13px;font-family:'Microsoft Yahei', Verdana, Geneva, sans-serif; color:#494949; float:right;}
.wp_paging input {font-size:12px;*font-size:100%;}
.wp_paging li { display:inline-block; height:25px; line-height:25px; float:left; margin-top:5px;}
.wp_paging li span,.wp_paging li a { display:inline-block; float:left; margin-left:10px; }
.wp_paging li em { font-style:normal;}
.wp_paging li a { cursor:pointer; color:#666; line-height: 25px; height: 25px;}
.wp_paging li a:hover { color:#000; }
.wp_paging li a span{ margin:0;}
.wp_paging li input { font-size:12px;*font-size:100%; width:24px; height:15px; line-height:15px; border:1px solid #d5d5d5; background:#fff; margin-top:4px; text-align:center;}
.wp_paging li input:focus{ outline:none;}

#wp_pager ul.pages{display:inline-block;margin: 10px 0 10px;padding: 0;font-size: 13px;text-transform:capitalize;border: none;}
#wp_pager ul.pages li{float: left;margin: 0 3px 0 0;line-height:32px;list-style: none;color: #333;border: 1px solid #dddddd; text-decoration: none; cursor:pointer;}
#wp_pager ul.pages li:hover{background: #f2f8ff;border: 1px solid #999;}
#wp_pager ul.pages li a{display:inline-block;line-height:32px;padding:0px 11px; color: #333;}
#wp_pager ul.pages li.pgNext{}
#wp_pager ul.pages li.pgEmpty{display: none;}
#wp_pager ul.pages li a.pgCurrent{color: #222;font-weight: 700;border: none;}

/** 栏目图片列表 **/
.wp_listalbumn { width:100%;}
.wp_listalbumn .albumn_info { width:100%; height:auto; text-align:center;}
.wp_listalbumn .albumn_info a { display:inline-block; position:relative; margin:0 auto; color:#333; text-decoration:none; font-size:13px; font-family:'Microsoft YaHei', Tahoma, Geneva, sans-serif;}
.wp_listalbumn .albumn_info a:hover { color:#C30;}
.wp_listalbumn .albumn_info .Article_MicroImage { display:block;}
.wp_listalbumn .albumn_info .Article_Title { display:block; padding:5px 0; margin:0 auto; text-align:center; line-height:1.7em;}
.wp_listalbumn .albumn_info .albumn_mark { display:block; width:100%; height:0; position:absolute; left:0; bottom:0; filter:alpha(opacity=70); opacity:0.7; background-color:#000000; z-index:0; overflow:hidden;}

/** 内容折叠 **/
.wp_contentfold { width:100%;}
.wp_contentfold .title {background-position: 0% 0%; CURSOR: pointer; HEIGHT: 53px; WIDTH: 754px; PADDING-LEFT: 0px; LINE-HEIGHT: 25px; background-image:url('titlegb.jpg'); padding-top:18px; background-repeat:no-repeat}
.wp_contentfold .title p {line-height: 100%; margin-left: 20px; margin-top: 0; margin-bottom: 0}
.wp_contentfold .title p font {color: rgb(255, 255, 255);}
.wp_contentfold .content {HEIGHT: 100%; WIDTH: 749px;}
.wp_contentfold .content div {padding-bottom: 20px;}
.wp_contentfold .content div table {background-color: #F7F7F7;}

/** 搜索 **/
.wp_search{}
.wp_search .search{ background:url(../images/btn_search.gif); width:58px; height:22px; border:0px; cursor: pointer;}
.wp_search .search_en{ background:url(../images/btn_search_en.gif); width:72px; height:22px; border:0px; cursor: pointer; }
.wp_search .advanceSearch{ background:url(../images/btn_advanceSearch.gif); width:80px; height:22px; border:0px; cursor: pointer;}
.wp_search .advanceSearch_en{ background:url(../images/btn_advanceSearch_en.gif); width:127px; height:22px; border:0px; cursor: pointer; }
.wp_search .datepicker {cursor: pointer; background:url(../images/cal.gif) no-repeat; width:16px; height:14px; display: inline-block; border:0px; margin-left: 1px;}

/** 统计排行 **/
.wp_ranking_list{ display:block; width:100%;}
.wp_ranking_list .list_item { width:100%; height:24px; line-height:24px; border-bottom:1px dashed #ccc; vertical-align:top;}
.wp_ranking_list .list_item .pr_fields { display:inline; float:left;}
.wp_ranking_list .list_item .count { display:inline-block; width:16px; height:16px; line-height:16px; text-align:center; margin-top:3px; background:#ddd; border:1px solid #bbb; border-radius:4px; color:#fff; font-size:11px;float:left; margin-right:5px;}
.wp_ranking_list .i1 .count,.wp_ranking_list .i2 .count,.wp_ranking_list .i3 .count{ background:#9C3; border:1px solid #060;}
.wp_ranking_list .list_item .title {float:left; }
.wp_ranking_list .list_item .ex_fields { display:inline; float:right;}
.wp_ranking_list .list_item .date { color:#666;}
.wp_ranking_list .list_item .views { color:#999;}

/** before_login: 横向登录前 **/
.wp_login_x { width:100%;}
.wp_login_x .login_input { display:inline-block; float:left; margin-right:4px; height:26px; line-height:26px;}
.wp_login_x .login_input label { float:left; display:inline-block; height:26px; line-height:24px; cursor:pointer;}
.wp_login_x .login_input .input {float:left; display:block; width:90px; border:1px solid #ccc; background-color:#fff;}
.wp_login_x .login_code .input { width:54px;}
.wp_login_x .login_code .verifycodeImg { display:inline-block; width:60px; height:20px; margin-top:3px; margin-left:5px;}
.wp_login_x .login_input .input input { display:block; width:96%; height:14px; line-height:14px; padding:5px 2%; border:0;}
.wp_login_x .login_btn .button {display:block; float:left;  width:54px; height:24px; background-color:#eee; border:1px solid #ccc;}
.wp_login_x .login_btn .button input { display:inline-block; width:54px; height:24px; border:none; background:none; color:#444; text-align:center; cursor:pointer;}
.wp_login_x .login_btn .button input:hover { background-color:#e8e8e8; border-color:#d5d5d5; color:#333;}
/** after_login: 横向登录后 **/
.wp_login_x .login_info { display:inline-block; float:left; line-height:24px; margin-right:4px;}
.wp_login_x .login_tool a {display:inline-block; padding:0 7px; height:22px; line-height:22px; background-color:#eee; border:1px solid #ccc; text-align:center; margin-left:5px;}
.wp_login_x .login_tool a:hover {background-color:#e8e8e8; border-color:#d5d5d5; color:#333;}

/** before_login: 纵向登录前 **/
.wp_login { width:100%;}
.wp_login .login_input { width:100%; height:26px; line-height:26px; margin-bottom:8px;}
.wp_login .login_input label { float:left; display:block; width:60px; height:26px; line-height:24px; text-align:right; cursor:pointer;}
.wp_login .login_input .input { float:left; display:block; width:120px; border:1px solid #ccc; background-color:#fff;}
.wp_login .login_code .input { width:54px;}
.wp_login .login_code .verifycodeImg { display:inline-block; width:60px; height:20px; float:left; margin-top:3px; margin-left:5px;}
.wp_login .login_input .input input { display:block; width:96%; height:14px; line-height:14px; padding:5px 2%; border:0;}
.wp_login .login_btn { width:auto; padding-left:60px;}
.wp_login .login_btn .button { display:block; float:left; width:54px; height:24px; background-color:#eee; border:1px solid #ccc;}
.wp_login .login_btn .button input { display:inline; width:100%; height:24px; border:none; background:none; color:#444; text-align:center; cursor:pointer;}
.wp_login .login_btn .button input:hover { background-color:#e8e8e8; border-color:#d5d5d5; color:#333;}
/** after_login: 纵向登录后 **/
.wp_login .login_info { line-height:24px;}
.wp_login .login_info .info_item { display:inline-block; width:60px; text-align:right;}
.wp_login .login_tool a {display:inline-block; padding:0 7px; height:22px; line-height:22px; background-color:#eee; border:1px solid #ccc; text-align:center; margin-left:5px;}
.wp_login .login_tool a:hover {background-color:#e8e8e8; border-color:#d5d5d5; color:#333;}

/**投票扩展样式**/ 
/** 图文调查列表 **/
.wp_listmiltivote { width:100%;text-align:center;padding-top: 5px}
.wp_listmiltivote .miltivote_info { width:100%; height:auto; text-align:center;}
.wp_listmiltivote .miltivote_info a { display:inline-block; position:relative; margin:0 auto; color:#333; text-decoration:none; font-size:13px; font-family:'Microsoft YaHei', Tahoma, Geneva, sans-serif;}
.wp_listmiltivote .miltivote_info a:hover { color:#C30;}
.wp_listmiltivote .miltivote_info .Article_MicroImage { display:block;}
.wp_listmiltivote .miltivote_info .Article_Title { display:block; padding:5px 0; margin:0 auto; text-align:center; line-height:1.7em;}
.wp_listmiltivote .miltivote_info .albumn_mark { display:block; width:100%; height:0; position:absolute; left:0; bottom:0; filter:alpha(opacity=70); opacity:0.7; background-color:#000000; z-index:0; overflow:hidden;}
.wp_listmiltivote .miltivote_ctl .wp_miltivote { height: auto; _display:inline-block; text-align: left; line-height: 13px; vertical-align: central;}
.wp_listmiltivote .miltivote_ctl .wp_miltivote span {line-height: 1}
.wp_listmiltivote .miltivote_ctl .wp_miltivote .vote_button {cursor: pointer;}
.wp_listmiltivote .miltivote_ctl .wp_miltivote .vote_button_disabled {cursor: auto; color:#ccc;}
.wp_listmiltivote .miltivote_ctl .wp_miltivote .vote_count { font-size: 12px; color: #999;}
.wp_listmiltivote .miltivote_ctl .wp_miltivote .vote_rate { font-size: 12px; color: #999;} 
.wp_miltivote_submit { text-align: center; padding: 5px;}
.wp_miltivote_submit .vote_submit { cursor: pointer;}
.wp_miltivote_submit .vote_submit_disabled { cursor: auto; color:#ccc;}

/**阅读状态**/
.wp_artReadStatus_unread {display: inline-block;
                          width: 10px;
                          height: 16px;
                          margin-top: 3px;
                          color: #fff;
                          font-size: 11px;
                          float: left;
                          margin-right: 5px;
                          overflow: hidden;
                          text-indent: -99em;
                          background: url(wp_article_li_1.png) no-repeat 50%;}


.wp_listcolumn_searchbartree{padding: 2px 0px;}
.wp_listcolumn_searchbartree .wp_listcolumn_treeKeyword{
    width: 130px;height: 22px;
    line-height: 225px;
    vertical-align:middle;
    padding-left: 3px;
}
.wp_listcolumn_searchbttree{
    line-height:23px;
    display: inline-block;
    padding:0px 9px;
    background-color: #ecefec;
    border:none;
    vertical-align:middle;
    cursor:pointer;
}
</style>
</head>

<body>
  <div class="top-se">
    <div class="container">
      <div class="t_se clearfix" frag="窗口0" portletmode="search">            <form method="post" action="http://cs.nuaa.edu.cn/_web/search/doSearch.do?locale=zh_CN&request_locale=zh_CN&_p=YXM9NjgmdD0xMDI2JmQ9NDE1OSZwPTImZj0xOTUyJm09U04mfGJubkNvbHVtblZpcnR1YWxOYW1lPTE5NTIm" target="_blank">
                <input name="keyword" type="text" class="se_txt">
                <input name="submit" type="submit" class="se_sub" value="搜 索">
                <a class="se_close" href="javascript:;"></a>
            </form>
        </div>
    </div>
  </div>
  <div class="top">
    <div class="container">
      <div class="row">
        <div class="col xs-12 sm-12 md-5 lg-5">
          <div class="logo">
            <div class="logo_table">
              <div class="logo_cell"> <a href="http://cs.nuaa.edu.cn/main.htm"><img src="http://cs.nuaa.edu.cn/_upload/tpl/04/02/1026/template1026/images/logo.png"></a> </div>
            </div>
          </div>
        </div>
        <div class="col xs-12 sm-12 md-7 lg-7">
          <div class="top_r">
            <div class="top_r_a"><a class="a1" href="http://www.nuaa.edu.cn/" target="_blank">南航主页</a><a class="a2" href="javascript:void(0)">ENGLISH</a><a class="a3" href="javascript:;"></a></div>
            <div class="top_nav hidden-xs" frag="窗口1" portletmode="simpleSudyNavi" configs="{'c1':'1','c7':'2','c4':'_self','c3':'30','c6':'0','c8':'2','c9':'0','c2':'1','c5':'2'}" contents="{'c2':'0', 'c1':'/学院概况,/师资队伍,/科学研究,/教学工作,/学生工作,/党群工作,/招生就业,/常用下载'}">
              
              <ul class="clearfix pc_menuCon">
                <li><a href="/main.htm">首页</a></li>
                
                <li class=""><a href="/1954/list.htm" target="_self">学院概况</a>
                  
                  <ul>
                    
                    <li><a href="/1965/list.htm" target="_self">Introduction of the College</a></li>
                    
                    <li><a href="/1966/list.htm" target="_self">领导班子</a></li>
                    
                    <li><a href="/1967/list.htm" target="_self">学院概况</a></li>
                    
                    <li><a href="/1968/list.htm" target="_self">历史沿革</a></li>
                    
                  </ul>
                  
                </li>
                
                <li class=""><a href="/1956/list.htm" target="_self">师资队伍</a>
                  
                  <ul>
                    
                    <li><a href="/7381/list.htm" target="_self">师资概况</a></li>
                    
                    <li><a href="/7382/list.htm" target="_self">学科团队</a></li>
                    
                    <li><a href="/7383/list.htm" target="_self">博士生导师</a></li>
                    
                    <li><a href="/7384/list.htm" target="_self">硕士生导师</a></li>
                    
                  </ul>
                  
                </li>
                
                <li class=""><a href="/1957/list.htm" target="_self">科学研究</a>
                  
                  <ul>
                    
                    <li><a href="/1975/list.htm" target="_self">科研动态</a></li>
                    
                    <li><a href="/1976/list.htm" target="_self">表格下载</a></li>
                    
                  </ul>
                  
                </li>
                
                <li class=""><a href="/1958/list.htm" target="_self">教学工作</a>
                  
                  <ul>
                    
                    <li><a href="/1977/list.htm" target="_self">教学动态</a></li>
                    
                    <li><a href="/jxzd/list.htm" target="_self">教学制度</a></li>
                    
                    <li><a href="/1978/list.htm" target="_self">本科生教学</a></li>
                    
                    <li><a href="/1979/list.htm" target="_self">研究生教学</a></li>
                    
                    <li><a href="/1980/list.htm" target="_self">教学改革与成果</a></li>
                    
                    <li><a href="/1981/list.htm" target="_self">资料下载</a></li>
                    
                  </ul>
                  
                </li>
                
                <li class=""><a href="/1959/list.htm" target="_self">学生工作</a>
                  
                  <ul>
                    
                    <li><a href="/1982/list.htm" target="_self">学生活动</a></li>
                    
                    <li><a href="/1983/list.htm" target="_self">研究生会</a></li>
                    
                    <li><a href="/1984/list.htm" target="_self">共青团</a></li>
                    
                    <li><a href="/1985/list.htm" target="_self">学生党建</a></li>
                    
                    <li><a href="/1986/list.htm" target="_self">获奖情况</a></li>
                    
                    <li><a href="/1987/list.htm" target="_self">通知公告</a></li>
                    
                  </ul>
                  
                </li>
                
                <li class=""><a href="/1960/list.htm" target="_self">党群工作</a>
                  
                  <ul>
                    
                    <li><a href="/1988/list.htm" target="_self">党员管理</a></li>
                    
                    <li><a href="/1989/list.htm" target="_self">主题活动</a></li>
                    
                    <li><a href="/1990/list.htm" target="_self">组织建设</a></li>
                    
                    <li><a href="/1991/list.htm" target="_self">党员发展</a></li>
                    
                    <li><a href="/1992/list.htm" target="_self">党校工作</a></li>
                    
                  </ul>
                  
                </li>
                
                <li class=""><a href="/1962/list.htm" target="_self">招生就业</a>
                  
                  <ul>
                    
                    <li><a href="/1993/list.htm" target="_self">招生信息</a></li>
                    
                    <li><a href="/1994/list.htm" target="_self">就业信息</a></li>
                    
                  </ul>
                  
                </li>
                
                <li class=""><a href="/cyxz/list.htm" target="_self">常用下载</a>
                  
                  <ul>
                    
                    <li><a href="/rsxz/list.htm" target="_self">人事工作</a></li>
                    
                    <li><a href="/bkjx/list.htm" target="_self">本科生培养</a></li>
                    
                    <li><a href="/yjspy/list.htm" target="_self">研究生培养</a></li>
                    
                    <li><a href="/kxyj/list.htm" target="_self">科学研究</a></li>
                    
                    <li><a href="/xsgz/list.htm" target="_self">学生工作</a></li>
                    
                    <li><a href="/djqt/list.htm" target="_self">党建群团</a></li>
                    
                    <li><a href="/xygz/list.htm" target="_self">校友工作</a></li>
                    
                    <li><a href="/xyLogo/list.htm" target="_self">学院Logo</a></li>
                    
                  </ul>
                  
                </li>
                
              </ul>
              
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="phone_menu_t visible-xs">
    <div class="phone_menu" style="display: none" frag="窗口01" portletmode="simpleSudyNavi" configs="{'c1':'1','c7':'2','c4':'_self','c3':'30','c6':'0','c8':'2','c9':'0','c2':'1','c5':'2'}" contents="{'c2':'0', 'c1':'/学院概况,/师资队伍,/科学研究,/教学工作,/学生工作,/党群工作,/招生就业'}">
      
      <ul>
        
        <li><a href="http://cs.nuaa.edu.cn/1954/list.htm" target="_self">学院概况</a>
          
          <ul>
            
            <li><a href="http://cs.nuaa.edu.cn/1965/list.htm" target="_self">Introduction of the College</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1966/list.htm" target="_self">领导班子</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1967/list.htm" target="_self">学院概况</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1968/list.htm" target="_self">历史沿革</a></li>
            
          </ul>
          
        </li>
        
        <li ><a href="http://cs.nuaa.edu.cn/1956/list.htm" target="_self">师资队伍</a>
          
          <ul>
            
            <li><a href="http://cs.nuaa.edu.cn/7381/list.htm" target="_self">师资概况</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/7382/list.htm" target="_self">学科团队</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/7383/list.htm" target="_self">博士生导师</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/7384/list.htm" target="_self">硕士生导师</a></li>
            
          </ul>
          
        </li>
        
        <li><a href="http://cs.nuaa.edu.cn/1957/list.htm" target="_self">科学研究</a>
          
          <ul>
            
            <li><a href="http://cs.nuaa.edu.cn/1975/list.htm" target="_self">科研动态</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1976/list.htm" target="_self">表格下载</a></li>
            
          </ul>
          
        </li>
        
        <li><a href="http://cs.nuaa.edu.cn/1958/list.htm" target="_self">教学工作</a>
          
          <ul>
            
            <li><a href="http://cs.nuaa.edu.cn/1977/list.htm" target="_self">教学动态</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/jxzd/list.htm" target="_self">教学制度</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1978/list.htm" target="_self">本科生教学</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1979/list.htm" target="_self">研究生教学</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1980/list.htm" target="_self">教学改革与成果</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1981/list.htm" target="_self">资料下载</a></li>
            
          </ul>
          
        </li>
        
        <li><a href="http://cs.nuaa.edu.cn/1959/list.htm" target="_self">学生工作</a>
          
          <ul>
            
            <li><a href="http://cs.nuaa.edu.cn/1982/list.htm" target="_self">学生活动</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1983/list.htm" target="_self">研究生会</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1984/list.htm" target="_self">共青团</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1985/list.htm" target="_self">学生党建</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1986/list.htm" target="_self">获奖情况</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1987/list.htm" target="_self">通知公告</a></li>
            
          </ul>
          
        </li>
        
        <li><a href="http://cs.nuaa.edu.cn/1960/list.htm" target="_self">党群工作</a>
          
          <ul>
            
            <li><a href="http://cs.nuaa.edu.cn/1988/list.htm" target="_self">党员管理</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1989/list.htm" target="_self">主题活动</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1990/list.htm" target="_self">组织建设</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1991/list.htm" target="_self">党员发展</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1992/list.htm" target="_self">党校工作</a></li>
            
          </ul>
          
        </li>
        
        <li><a href="http://cs.nuaa.edu.cn/1962/list.htm" target="_self">招生就业</a>
          
          <ul>
            
            <li><a href="http://cs.nuaa.edu.cn/1993/list.htm" target="_self">招生信息</a></li>
            
            <li><a href="http://cs.nuaa.edu.cn/1994/list.htm" target="_self">就业信息</a></li>
            
          </ul>
          
        </li>
        
      </ul>
      
    </div>
  </div>
  <script type="text/javascript">
  $(function() {
    $('.pc_menuCon li').hover(function() {
      $('ul', this).slideDown(200);
    }, function() {
      $('ul', this).slideUp(100);
    });
    $('.a3').click(function() {
      $('.top-se').stop().slideToggle();
    });
    $('.se_close').click(function() {
      $('.top-se').stop().slideUp(200);;
    });
  });
  jQuery('.phone_menu').meanmenu();
  $(window).scroll(function() {
    var scrollHeight = $(document).scrollTop();
    if (scrollHeight > 340) {
      $('.phone_menu_t').addClass('lighted-fixed');
    } else {
      $('.phone_menu_t').removeClass('lighted-fixed');
    }
  });
  </script>
  <div class="p-banner p-banner-pc-a"></div>
  <div class="page-main">
    <div class="container">
      <div class="in-main-con">
        <div class="pageCon clearfix">
          <div style="position:absolute;width:25%;height: 100%;background: #017abf;"></div>
          <div class="col xs-12 sm-4 md-3 lg-3">
            <div class="pageNav">
              <div frag="窗口3" portletmode="simpleColumnAnchor">
                <h3 class="pageNav-h"><a>师资队伍</a></h3>
              </div>
              <div frag="窗口4" portletmode="simpleColumnList">
                <ul class="clearfix hidden-xs pageNav-ul">
                  
                  <li class="nav-one selected"><em></em><a href="http://cs.nuaa.edu.cn/7381/list.htm" target="_self"><span>|-</span>师资概况</a>
                    
                  </li>
                  
                  <li class="nav-one "><em></em><a href="http://cs.nuaa.edu.cn/7382/list.htm" target="_self"><span>|-</span>学科团队</a>
                    
                  </li>
                  
                  <li class="nav-one "><em></em><a href="http://cs.nuaa.edu.cn/7383/list.htm" target="_self"><span>|-</span>博士生导师</a>
                    
                  </li>
                  
                  <li class="nav-one "><em></em><a href="http://cs.nuaa.edu.cn/7384/list.htm" target="_self"><span>|-</span>硕士生导师</a>
                    
                  </li>
                  
                </ul>
              </div>
            </div>
          </div>
<div class="content";>
        <div class="title"style="text-align:center;font-weight:bold;margin-top:20px;font-size:18px">方黎明</div>
        <div class="time" style="text-align:center">时间：2021-07-08&nbsp;&nbsp;&nbsp;&nbsp;</div>   
<div style="margin-left:340px;width:890px;">
           <div class="con">           
            <div><img src="http://github.com/flmwebsite/flm.github.io/raw/gh-pages/css/flm.png" width="200" style="float:right;margin:0 0 20px 20px;"></div>
<p style="font-size:17px"><strong>1.</strong><strong>基本信息</strong></p>
<p><strong>姓</strong><strong>名：</strong>方黎明&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>性</strong><strong>别：</strong>男</p>
<p><strong>联系电话</strong><strong>：</strong>18626858383&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>E-mail</strong><strong>：</strong>fangliming@nuaa.edu.cn</p>
<p><strong>职</strong><strong>务：</strong>南京航空航天大学智能与安全实验室副主任</p>
<p><strong>研究方向：</strong>密码学、区块链、人工智能安全</p>
<p><strong>招生信息：</strong>每年招收有志于从事信息安全相关国际前沿研究的博士和硕士研究生</p>
<p  style="font-size:17px"><strong>2.个人简介</strong></p>
<div style="text-align:justify;text-align-last:left;">  男，研究员，南京航空航天大学密码与应用安全实验室副主任、高安全系统的软件开发与验证技术工信部重点实验室学术带头人、香港城市大学博士后、CCF区块链专委会委员、江苏省计算机学会区块链专委会委员、江苏省人工智能学会智能与安全专委会秘书长，浙江省科技进步奖评审专家、湖北省科技项目评审专家。担任国际会议WASA 2021组织委员会主席，Inscrypt 2019组织委员会主席，担任CryptoIC 2019组织委员会主席，担任SpaCCS 2020国际会议秘书长，担任十多个国际会议程序委员会委员。在密码学、区块链、人工智能等领域具有长期的技术积累，承担了国家自然科学基金、国家重点研发计划、工信部工业互联网创新发展工程、江苏省重点研发计划等十余项，申请发明专利二十余项，在科学出版社出版专著一本。担任多个SCI期刊的客座编辑，在中国科学、Theoretical Computer Science、ICDE、IEEE Transactions on Dependable and Secure Computing、IEEE Transactions on Information Forensics and Security、IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems、IEEE Transactions on Parallel and Distributed Systems、IEEE Transactions on Industrial Informatics、IEEE Transactions on Fuzzy Systems、ACM Transactions on Data Science、ACM Transactions on Multimedia Computing, Communications and Applications、IEEE Internet of Things J.、Designs Codes and Cryptography等国际著名期刊和会议上发表论文80余篇。</div>
<p  style="font-size:17px"><strong>3.承担国家及省部级科研项目情况</strong></p>
<div class="justify">
1.支持多关键词复杂匹配的可搜索代理重加密研究，<strong>国家自然科学基金（面上项目），</strong>项目编号：61872181，2019.1-2021.12，<strong>主持，</strong>国家级项目;</div>
<div class="justify">2.人工智能安全理论及验证平台，国家重点研发计划，522万，2021.1-2023.12，课题共同负责人;</div>
<div class="justify">3.安全可控体系恶意代码分析设备，<strong>工信部工业互联网创新发展工程，</strong>招标编号：TC200H02X,120万,2020.10-2021.10,南航负责人，省部级项目;</div>
<div class="justify">4.工业互联网威胁诱捕技术及设备，<strong>工信部工业互联网创新发展工程，</strong>招标编号：TC190H46H,400万，2019.9-2021.5，南航负责人，省部级项目；</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">5.支持国密标准的自主可控区块链防伪追溯的文化艺术品展示与交易平台研发，<strong>江苏省重点研发计划（产业前瞻），</strong>项目编号：1015-PBA20002，2020.7-2023.6，负责人，省部级项目；</div>
<div class="justify">6.可搜索公钥加密关键安全性问题的研究，<strong>国家自然科学基金（青年基金），</strong>项目编号：61300236，2014.1-2016.12，<strong>主持，</strong>国家级项目；</div>
<div class="justify">7.轻量化密码算法技术合作项目，华为技术有限公司，160万，2020.07-2021.1，在研;</div>
<div class="justify">8.区块链发票系统中隐私保护加密算法研发，深圳市腾讯计算机系统有限公司，50万，2020.08--2021.01，在研;</div>
<div class="justify">9.带多关键字搜索的公钥加密的研究，<strong>江苏省基础研究（自然科学基金），</strong>项目编号：BK20130809，2013.9-2016.12，<strong>主持，</strong>省部级项目；</div>
<div class="justify">10.基于多关键字的条件代理重加密的研究，<strong>中国博士后面上基金一等资助，</strong>项目编号：2013M530254，主持，省部级项目；</div>
<div class="justify">11.支持多关键词匹配的可搜索公钥加密的研究，<strong>中国博士后科学基金特别资助,主持，</strong>省部级项目；</div>
<div class="justify">12.支持复杂匹配搜索的可搜索公钥加密的研究，<strong>江苏省博士后基金,</strong> 编号：1302137C，<strong>主持，</strong>省部级项目；</div>
<div class="justify">13.支持多条件复杂匹配的代理重加密研究，<strong>国家自然科学基金（青年基金），</strong>项目编号：61702236，2017.1-2019.12，<strong>参与，</strong>国家级项目;</div>
<div class="justify">14.XX项目，十三五总装预研基金项目，2016.1-2020.12, <strong>参与，</strong>国家级项目；</div>
<div class="justify">15.云计算演化环境中的隐私建模与检测方法研究,<strong>国家自然科学基金（面上项目）,</strong>项目编号：61272083,81万,2013.1-2016.12,<strong>参与，</strong>国家级项目；</div>
<div class="justify">16.面向机场感知的噪声监测及其环境评估，<strong>国家自然基金重点项目，</strong>项目编号：61139002，280万，2011-2014，<strong>参与，</strong>国家级项目；</div>
<div class="justify">17.基于服务架构的民航公众信息服务平台，科技部，<strong> 863重点项目，</strong>项目编号：2006AA12A106，260万，2007-2009，<strong>参与，</strong>国家级项目；</div>
<div class="justify">18.参与直升机/无人机战术信息网络安全技术的研究，<strong>航空科学基金，</strong> 2005-2007，<strong>参与，</strong>省部级项目；</div>
<div class="justify">19.项目：ARC Future Fellowship FT0991397；<strong>参与</strong>；</div>
<p  style="font-size:17px"><strong>4.部分学术论文</strong></p>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[1].<strong>Liming Fang</strong>, Hanyi Zhang, Minghui Li, Chunpeng Ge, Liang Liu, Zhe Liu: A Secure and Fine-grained Scheme for Data Security in Industrial IoT Platforms for Smart City, IEEE Internet of Things Journal, 2020, 7(9): 7982-7990. (中科院一区, IF: 9.515)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[2].Chunpeng Ge, Willy Susilo, Joonsang Baek, Zhe Liu, Jinyue Xia, <strong>Liming Fang</strong>, Revocable Attribute-Based Encryption with Data Integrity in Clouds, IEEE Transactions on Dependable and Secure Computing, 2021. (CCF A, IF: 6.211, 已录用)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[3].<strong>Liming Fang</strong>, Yang Li, Zhe liu, Changchun Yin, Minghui Li, Zehong Cao. A Practical Model Based on Anomaly Detection for Protecting Medical IoT Control Services Against External Attacks. IEEE Transactions on Industrial Informatics. 2021, 17(6): 4260-4269.(中科院一区期刊，IF=9.112)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[4].Chunpeng Ge, Zhe Liu, Jinyue Xia, <strong>Liming Fang</strong>. Revocable Identity-Based Broadcast Proxy Re-encryption for Data Sharing in Clouds. IEEE Transactions on Dependable and Secure Computing, 2021, 18(3), 1214-1226. DOI: 10.1109/TDSC.2019.2899300 (CCF A类, IF:6.404)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[5].Chunpeng Ge, Willy Susilo, Joonsang Baek, Zhe Liu, Jinyue Xia, <strong>Liming Fang</strong>, A Verifiable and Fair Attribute-based Proxy Re-encryption Scheme for Data Sharing in Clouds, IEEE Transactions on Dependable and Secure Computing, 2021. DOI: 10.1109/TDSC.2021.3076580. (CCF A, IF: 6.211, 已录用)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[6].<strong>Liming Fang</strong>, Changchun Yin, Juncen Zhu, Chunpeng Ge, M. Tanveer, Alireza Jolfaei, Zehong Cao*: Privacy Protection for Medical Data Sharing in Smart Healthcare, ACM Transactions on Multimedia Computing, Communications, and Applications, 2020, 16(3s): 1-18. (CCF B类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[7].<strong>Liming Fang</strong>, Bo Zhao, Yang Li, Zhe Liu, Chunpeng Ge, Weizhi Meng. Countermeasure Based on Smart Contracts and AI Against DoS/DDoS Attack in 5G Circumstances. IEEE Network. 2020, 34(6): 54-61. (中科院一区, IF: 7.503) <span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[8].Xinyu Wang, Yuefeng Du, Cong Wang, Qian Wang, <strong>Liming Fang</strong>；WebEnclave: Protect Web Secrets from browser extensions with Software Enclave, IEEE Transactions on Dependable and Secure Computing, 2021. (CCF A, IF: 6.211, 已录用)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[9].<strong>Liming Fang</strong>, Yang Li, Xinyu Yun, Zhenyu Wen, Shouling Ji, Weizhi Meng, Zehong Cao, Muhammad Tanveer. THP: A Novel authentication scheme to prevent multiple attacks in SDN-based IoT network[J]. IEEE Internet of Things Journal, 2019. DOI: 10.1109/JIOT.2019.2944301 (中科院一区, IF: 9.515)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[10].<strong>Liming Fang</strong>, Changchun Yin, Lu Zhou, Yang Li, Chunhua Su, Jinyue Xia. A physiological and behavioral feature authentication scheme for medical cloud based on fuzzy-rough core vector machine[J]. Information Sciences, 2020, 507: 143-160. DOI: 10.1016/j.ins.2019.08.020 (中科院一区, IF: 5.524)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[11].Chunpeng Ge, Zhe Liu, <strong>Liming Fang</strong>, Huangding Ling, Aiping Zhang, Changchun Yin. A Hybrid Fuzzy Convolutional Neural Network Based Mechanism for Photovoltaic Cell Defect Detection with Electroluminescence Images. IEEE Transactions on Parallel and Distributed Systems. 2020. DOI: 10.1109/TPDS.2020.3046018. (CCF A类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[12].Chunpeng Ge, Willy Susilo, Zhe Liu, Jinyue Xia, <strong>Liming Fang</strong>, Pawel Szalachowski: Secure Keyword Search and Data Sharing Mechanism for Cloud Computing, IEEE Transactions on Dependable and Secure Computing, 2020, DOI: 10.1109/TDSC.2020.2963978 (CCF A类, IF:6.404)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[13].<strong>Liming Fang</strong>, Willy Susilo, Chunpeng Ge, Jiandong Wang. Public Key Encryption with Keyword Search Secure Against Keyword Guessing Attacks without Random Oracle. Information Sciences. 2014, 238:221–241. DOI:  10.1016/j.ins.2013.03.008 (中科院一区, IF: 5.524)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[14].Sihao Hu, Xuhong Zhang, Junfeng Zhou, Shouling Ji, Jiaqi Yuan, Zhao Li, Zhipeng Wang, Qi Chen, Qinming He, <strong>Liming Fang</strong>, Turbo: Fraud Detection in Deposit-free Leasing Service via Real-Time Behavior Network Mining, IEEE International Conference on Data Engineering (ICDE’21), April 19-22, 2021, Chania, Crete, Greece. (CCF A)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[15].Binbin Zhao, Shouling Ji, Wei-Han Lee, Changting Lin, Haiqing Weng, Jingzheng Wu, Pan Zhou, <strong>Liming Fang</strong>, Reheem Beyah. A Large-scale Empirical Study on the Vulnerability of Deployed IoT Devices. IEEE Transactions on Dependable and Secure Computing, 2020. (CCF A类, IF: 6.211)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[16].<strong>Liming Fang</strong>, Hongwei Zhu, Boqing Lv, Zhe Liu, Weizhi Meng, Yu Yu, Shouling Ji, Zehong Cao. HandiText: Handwriting Recognition based on Dynamic Characteristics with Incremental LSTM. ACM Transactions on Data Science, 2020, 1(4): 1-18. DOI: 10.1145/3385189.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[17].Yushu Zhang, Ping Wang, <strong>Liming Fang</strong>, Xing He, Hao Han, Bing Chen. Secure Transmission of Compressed Sampling Data Using Edge Clouds. IEEE Transactions on Industrial Informatics, 2020. DOI: 10.1109/TII.2020.2966511 (中科院一区, IF: 7.737)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[18].Zhuo Su, Dongyan Wang, Yixiao Yang, Yu Jiang, Wanli Chang, <strong>Liming Fang</strong>, Wen Li, Jiaguang Sun. Code Synthesis for Dataflow Based Embedded Software Design, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems , 2021, DOI: 10.1109/TCAD.2021.3055487 (CCF A类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[19].<strong>Liming Fang</strong>, Xinyu Yun, Changchun Yin, Weiping Ding, Lu Zhou, Zhe Liu, Chunhua Su. ANCS: Automatic NXDomain Classification System based on Incremental Fuzzy Rough Sets Machine Learning, IEEE Transactions on Fuzzy Systems, 2020. DOI: 10.1109/TFUZZ.2020.2965872 (中科院一区, IF: 8.759).<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[20].Chunpeng Ge, Zhe Liu, <strong>Liming Fang</strong>. A blockchain based decentralized data security mechanism for the Internet of Things[J]. Journal of Parallel and Distributed Computing, 2020, 141: 1-9.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[21].Chunpeng Ge, Changchun Yin, Zhe Liu, <strong>Liming Fang</strong>, Juncen Zhu, Huading Lin. A privacy preserve big data analysis system for wearable wireless sensor network[J]. Computers & Security, 2020, 96: 101887. (CCF B类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[22].Qi Xie, Duncan S. Wong, Guilin Wang, Xiao Tan, Kefei Chen and <strong>Liming Fang</strong>. Provably Secure Dynamic ID-based Anonymous Two-factor Authenticated Key Exchange Protocol with Extended Security Model. IEEE Transactions on Information Forensics & Security, 2017, 12(6): 1382-1392. DOI: 10.1109/TIFS.2017.2659640 (CCF A类, IF: 6.211)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[23].<strong>Liming Fang</strong>, Willy Susilo, Chunpeng Ge, Jiandong Wang: Chosen-ciphertext secure anonymous conditional proxy re-encryption with keyword search. Theoretical Computer Science, 2012, 462(4): 39-58. DOI: 10.1016/j.tcs.2012.08.017 (IF: 0.718, CCF B类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[24].<strong>Liming Fang</strong>, Willy Susilo, Chunpeng Ge, Jiandong Wang. Hierarchical Conditional Proxy Re-encryption. Computer Standards and Interfaces, 2012, 34(4):380-389. DOI: 10.1016/j.csi.2012.01.002 (SCI, IF: 2.441)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[25].Yang Li, Xinyu Yun, <strong>Liming Fang</strong>, Chunpeng Ge. An Efficient Login Authentication System against Multiple Attacks in Mobile Devices. Symmetry, 2021, 13(1): 125 (2021). <span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[26].ChangChun Yin, Hao Wang, Lu Zhou, <strong>Liming Fang</strong>. 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom). IEEE, 2020: 277-284. (CCF C类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[27].Minghui Li, Yang Li, <strong>Liming Fang</strong>. IEEE 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom). IEEE, 2020: 475-482. (CCF C类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[28].<strong>Liming Fang</strong>, Jiandong Wang, Chunpeng Ge, Yongjun Ren. Fuzzy Conditional Proxy Re-encryption. SCIENCE CHINA Information Sciences. 2013, 56(5): 1-13. DOI: 10.1007/s11432-012-4623-6 (CCF B类, IF: 2.731)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[29].<strong>Liming Fang</strong>, Willy Susilo, Chunpeng Ge, Jiandong Wang. Interactive conditional proxy re-encryption with fine grain policy. Journal of Systems and Software, 2011, 84(12): 2293-2302. DOI: 10.1016/j.jss.2011.06.045 (IF: 2.559, CCF B类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[30].Chunpeng Ge, Changchun Yin, Zhe Liu, <strong>Liming Fang</strong>, Juncen Zhu, Huading Ling, A privacy preserve big data analysis system for wearable wireless sensor network, Computers & Security, 2020. DOI: 10.1016/j.cose.2020.101887 (CCF B类，IF: 3.062)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[31].<strong>Liming Fang</strong>, Liang Liu, Jinyue Xia, Maosheng Sun: A Secure Multimedia Data Sharing Scheme for Wireless Network. Security and Communication Networks, 2018. DOI: 10.1155/2018/5037892 (IF: 1.376, CCF C类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[32].<strong>Liming Fang</strong>, Chunpeng Ge, Zhiqiu Huang, Jiandong Wang. Privacy preserving cloud data sharing system with flexible control, Computers and Electrical Engineering. 2018. DOI: 10.1016/j.compeleceng.2018.02.048 (JCR: Q2, IF: 2.189)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[33].<strong>Liming Fang</strong>, Minghui Li, Lu Zhou, Hanyi Zhang, Chunpeng Ge. A Fine-Grained User-Divided Privacy- Preserving Access Control Protocol in Smart Watch. Sensors, 19(9): 2109 (2019). DOI: 10.3390/s19092109 (JCR: Q2, IF: 3.031)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[34].Chunpeng Ge, <strong>Liming Fang</strong>, and Jinyue Xia. "Key-Private Identity-Based Proxy Re-encryption." Computers, Materials & Continua, 2020, 63(2): 633-647. DOI: https://doi.org/10.32604/cmc.2020.06217 (SCI, IF: 3.024)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[35].Chunpeng, Ge, Zhe Liu, and <strong>Liming Fang</strong>. "A blockchain based decentralized data security mechanism for the Internet of Things." Journal of Parallel and Distributed Computing, 2020. DOI: 10.1016/j.jpdc.2020.03.005 (JCR: Q2, IF: 1.819)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[36].Bo Zhao, <strong>Liming Fang</strong>, Hanyi Zhang, Chunpeng Ge, Weizhi Meng, Liang Liu, Chunhua Su. Y-DWMS: A Digital Watermark Management System Based on Smart Contracts. Sensors, 2019. DOI: 10.3390/s19143091 (JCR: Q2, IF: 3.031)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[37].Liang Liu, Zhaoyang Han, <strong>Liming Fang</strong>, Zuchao Ma. Tell the Device Password: Smart Device Wi-Fi Connection Based on Audio Waves. Sensors, 19(3): 618 (2019). DOI: 10.3390/s19030618 (JCR: Q2, IF:3.031)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[38].Maosheng Sun, Chunpeng Ge, <strong>Liming Fang</strong>, Jiandong Wang. Conditional proxy broadcast re-encryption with fine grain policy for cloud data sharing. IJES 11(2): 115-124 (2019). DOI: 10.3390/s19030618<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[39].Chunpeng Ge, Willy Susilo, <strong>Liming Fang</strong>, Jiandong Wang, Yunqing Shi: A CCA-Secure Key-Policy Attribute-based Proxy Re-encryption in the Adaptive Corruption Model for Dropbox Data Sharing System. Designs, Codes & Crptography, 2018. DOI: 10.1007/s10623-018-0462-9 (IF: 1.224, CCF B类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[40].Chunpeng Ge, Willy Susilo, Jiandong Wang, <strong>Liming Fang</strong>. Identity-based conditional proxy re-encryption with fine grain policy, Computer Standard & Interface. 2017, 52: 1-9. DOI: 10.1016/j.csi.2016.12.005 (SCI, IF: 2.441)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[41].Maosheng Sun, Chunpeng Ge, <strong>Liming Fang</strong>, Jiandong Wang: A proxy broadcast re-encryption for cloud data sharing. Multimedia Tools Appl, 2018, 77(9): 10455-10469. DOI: 10.1007/s11042-017-4448-9 (SCI, IF: 2.101 )<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[42].Chunpeng Ge, Willy Susilo, Jiandong Wang, Zhiqiu Huang, <strong>Liming Fang</strong>, Yongjun Ren. A Key-Policy Attribute-based Proxy Re-encryption without Random Oracles, Computer Journal, 2016, 59(7): 970-982. DOI:  10.1093/comjnl/bxv100 (SCI, CCF B类)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[43].Kaitai Liang, <strong>Liming Fang</strong> Duncan S. Wong, Willy Susilo: A ciphertext policy attribute-based proxy re-encryption scheme for data sharing in public clouds. Concurrency and Computation: Practice and Experience. 2015, 27(8): 2004-2027. DOI: 10.1002/cpe.3397 (SCI, IF: 1.167)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[44].Kaitai Liang, <strong>Liming Fang</strong>, Willy Susilo, Duncan S. Wong: A Ciphertext-Policy Attribute-Based Proxy Re-encryption with Chosen-Ciphertext Security. INCoS 2013: 552-559. (EI/ISTP)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[45].<strong>Liming Fang</strong>, Willy Susilo, Chunpeng Ge, Jiandong Wang. A Secure Channel Free Public Key Encryption with Keyword Search Scheme without Random Oracle. Proc. of CANS 2009. LNCS 5888, Heidelberg: Springer, 2009: 248-258. (EI/ISTP)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[46].Yongjun Ren, Yaping Cheng, Jin Wang, <strong>Liming Fang</strong>: Data protection based on multifunction digital watermark in wireless sensor network. ICCST 2015: 37-41. (EI/ISTP)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[47].Yongjun Ren, Zhenqi Yang, Jin Wang, <strong>Liming Fang</strong>: Reliable access control for multi-authority in cloud storage. ICCST 2015: 113-116. (EI/ISTP)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[48].Yongjun Ren, Jian Shen, Jin Wang, <strong>Liming Fang</strong>: Outsourced data tagging via authority and delegable auditing for cloud storage. ICCST 2015: 131-134 . (EI/ISTP)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[49].Yongjun Ren, Jin Han, Jin Wang, <strong>Liming Fang</strong>: Privacy-preserving proof of storage in large group. ICCST 2015: 269-272. (EI/ISTP)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[50].Yongjun Ren, Yaping Chen, Jin Wang, <strong>Liming Fang</strong>: Leakage Resilient Provable Data Possession in Public Cloud Storage. IIH-MSP 2014: 706-709.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[51].Yongjun Ren, Zhenqi Yang, Jin Wang, <strong>Liming Fang</strong>: Attributed Based Provable Data Possession in Public Cloud Storage. IIH-MSP 2014: 710-713.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[52].Yongjun Ren, Jiang Xu, Jin Wang, <strong>Liming Fang</strong>: Oriented Group Provable Data Possession in Public Cloud. IIH-MSP 2014: 775-778.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[53].Yongjun Ren, Jian Shen, Jin Wang, <strong>Liming Fang</strong>: Analysis of Delegable and Proxy Provable Data Possession for Cloud Storage. IIH-MSP 2014: 779-782.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[54].Yongjun Ren, Jian Shen, Jin Wang, <strong>Liming Fang</strong>: Security Analysis of Delegable and Proxy Provable Data Possession in Public Cloud Storage. IIH-MSP 2014: 795-798<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[55].<strong>Liming Fang</strong>, Willy Susilo, Jiandong Wang. Anonymous Conditional Proxy Re-encryption without Random Oracle. Proc. of ProvSec 2009. LNCS 5848, pp. 47-60. Heidelberg: Springer, 2009: 47-60. (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[56].<strong>Liming Fang</strong>, Willy Susilo, Chunpeng Ge, Jiandong Wang. Chosen Public Key and Ciphertext Secure Proxy Re-encryption Schemes. International Journal of Digital Content Technology and its Applications. 2010, 4(9):151-160. (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[57].<strong>Liming Fang</strong>, Chunpeng Ge, Jiandong Wang, Yongjun Ren. Decryptable Public Key Encryption with Keyword Search Schemes. International Journal of Digital Content Technology and its Applications, 2010, 4(9):141-150. (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[58].<strong>Liming Fang</strong>, Jiandong Wang, Yongjun Ren, Jinyue Xia, Shizhu Bian. Chosen-Ciphertext Secure Fuzzy Identity-Based Encryption without ROM. Journal of Shanghai Jiaotong University, 2008, 13(6):646-650. (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[59].<strong>Liming Fang</strong>, Jiandong Wang, Yongjun Ren, Jinyue Xia, Shizhu Bian. Chosen-Ciphertext Secure Multi-authority Fuzzy Identity-Based Key Encapsulation without ROM. Proc. of 2008 International Conference on Computational Intelligence and Security, Vol. 1, 2008: 326-330. (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[60].<strong>Liming Fang</strong>, Jiandong Wang, Yongjun Ren, Jinyue Xia, Shizhu Bian: Chosen-Ciphertext Secure Fuzzy Identity-Based Key Encapsulation without ROM. IACR Cryptology ePrint Archive 2008: 139 (2008)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[61].<strong>Liming Fang</strong>, Jinyue Xia: Full Security: Fuzzy Identity Based Encryption. IACR Cryptology ePrint Archive 2008: 307 (2008)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[62].Guoan Zhao, <strong>Liming Fang</strong>, Jiandong Wang, Chunpeng Ge, Yongjun Ren: Improved unidirectional chosen-ciphertext secure proxy re-encryption. WCNIS 2010: 476-480(EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[63].Guoan Zhao, Canghai Tan, Yongjun Ren, <strong>Liming Fang</strong>: An efficient unlinkable secret handshake protocol without ROM.WCNIS 2010: 486-490(EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[64].Yuan Yuan, Bing Chen, Jiandong Wang, <strong>Liming Fang</strong>, Tao Xu: Weighted Margin Multi-Class Core Vector Machines. CIS (1) 2008: 235-239(EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[65].Yongjun Ren, Jiandong Wang, Youdong Zhang, <strong>Liming Fang</strong>. Identity-Based Key Issuing Protocol for Ad Hoc Networks. IEEE International Conference on Computational Intelligence and Security, 2007.12 (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[66].任勇军, 王建东, 庄毅, <strong>方黎明</strong>. 基于属性的认证密钥协商协议. 兰州大学学报, 2010, 46(2): 103-110.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[67].卞仕柱, 王建东, 任勇军, <strong>方黎明</strong>, 夏金月. 强安全高效的认证密钥交换协议. 计算机工程,  2010, 36(07): 136-139.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[68].夏金月, 王建东, <strong>方黎明</strong>, 任勇军, 卞仕柱. ECK2007模型与其他密钥协商协议模型安全强弱关系的形式化证明. 南京航空航天大学学报英文版, 2008, 4(7): 282-288. (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[69].Jinyue Xia, Jiandong Wang, <strong>Liming Fang</strong>, Yongjun Ren, Shizhu Bian: Formal Proof of Relative Strengths of Security between ECK2007 Model and other Proof Models for Key Agreement Protocols. IACR Cryptology ePrint Archive 2008: 479 (2008)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[70].任勇军, 王建东, 庄毅, <strong>方黎明</strong>. 基于双线性对的秘密重分配方案. 兰州大学学报, 2008, 44(1): 82-85.<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[71].任勇军, 王建东, 庄毅, <strong>方黎明</strong>. 一种动态的Ad Hoc网络密钥管理方案.南京航空航天大学学报, 2007, 39(9): 810-813. (EI)<span><span></div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">[72].任勇军, 王建东, 庄毅, <strong>方黎明</strong>. 基于身份的Ad Hoc网络密钥分发协议. 武汉大学学报, 2007, 40(5): 133-136.IEEE Transactions on Information Theory</em>, 2012, 58 (1): 445-452<strong>(CCF A</strong><strong>类期刊)</strong><span><span></div>
<p  style="font-size:17px"><strong>5.专利</strong></p>
<div class="justify">1.<strong>方黎明; </strong>李阳; 恽昕宇, 一种基于隐式登录指示符传递的图形认证方法, 发明专利, 专利申请日：2020.12.24, 中国, 申请号：202011545496.5</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">2.<strong>方黎明;</strong> 恽昕宇; 李阳, 一种可抵抗多重攻击的基于生物行为特征的登录认证方法, 发明专利, 专利申请日：2020.12.24, 中国, 申请号：202011548482.6</div>
<div class="justify">3.<strong>方黎明;</strong> 李明慧; 李阳, 一种基于地理位置的可认证的二维码支付方法, 发明专利, 专利申请日: 2020-12-18, 中国, 申请号: 202011456138.4</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">4.<strong>方黎明; </strong>刘哲; 刘亮; 葛春鹏; 沈立; 胡跃龙; 殷常春; 李阳, 一种细粒度策略的条件代理可重构加密方法, 发明专利, 专利申请日: 2019-11-18, 中国, 申请号: 201911127494.9</div>
<div class="justify">5.<strong>方黎明; </strong>李阳; 恽昕宇, 一种基于图形的登录认证方法, 发明专利, 专利申请日: 2019-11-15, 中国, 申请号: 201911117292.6</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">6.<strong>方黎明;</strong> 刘哲; 刘亮; 葛春鹏; 沈立; 胡跃龙; 张涵一; 李明慧, 一种模糊条件的代理广播可重构加密方法, 发明专利, 专利申请日: 2018-12-19, 中国, 申请号: 201811553447.6</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">7.<strong>方黎明; </strong>来容易; 黄志球; 王建东; 刘亮; 吴孙慈, 一种无须安全信道的带关键词搜索公钥加密方法, 发明专利, 专利申请日: 2018-05-11, 中国, 申请号: 201810227500.7</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">8.程桂花; 闫军; 代宗波; 钟显恒; <strong>方黎明, </strong> 一种基于BCSA优化支持向量机的电梯故障诊断方法,  发明专利, 专利申请日：2017-07-11, 中国, 申请号: CN201710559561.9</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">9.<strong>方黎明;</strong>葛春鹏;陈小杰, 一种基于可搜索密文的智能家居安全访问方法及其系统, 发明专利, 专利申请日：2012-10-19, 中国, 申请号: 201210399443.3</div>
<div class="justify">10.<strong>方黎明;</strong>葛春鹏, 一种基于运动检测的智能家居监控方法及其系统, 发明专利, 专利申请日：2012-08-28, 中国, 申请号: 201210309639.9</div>
<div class="justify">11.<strong>方黎明;</strong>陈小杰, 一种万能遥控器关联方法及其系统, 发明专利, 专利申请日：2012-08-29, 中国, 申请号: 201210311865.0></div>
<div class="justify">12.范渊; <strong>方黎明; </strong>张小孟; 莫金友等, 一种无线网络攻击定位方法, 发明专利, 专利申请日：2017-03-16, 中国, 申请号: CN201710157892.X </div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">13.范渊、<strong>方黎明;</strong> 张小孟; 莫金友等, 入侵检测系统中基于多属性哈希去重的网络日志存储方法, 发明专利, 专利申请日：2017-03-16, 中国, 申请号: CN201710167463.0</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">14.金晓东; 孙博; 黄步添; 王建东;<strong>方黎明, </strong>基于服刑人员行为特征集成学习模型的危险倾向预测方法, 发明专利, 专利申请日：20140822, 中国, 申请号: CN201410416208.</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">15.邹朋成; 金晓东; 黄步添; 王建东; 陈海燕; <strong>方黎明</strong>等, 一种监狱服刑人员危险性倾向的智能分析预警方法, 发明专利, 专利申请日：20140822, 中国, 申请号: CN201410245760.9</div>
<div class="justify">16.任勇军;顾彬;<strong>方黎明;</strong>王建东, 基于sniffer的无线传感网的入侵检测方法, 发明专利, 专利申请日：2010-07-28, 中国, 申请号: 201010238738.3></div>
<div class="justify">17.应华;<strong>方黎明,</strong>一种信息加密的无线灯联网系统及其加密通讯方法, 发明专利, 专利申请日：2011-06-23, 中国, 申请号: 201110171229.8</div>
<div class="justify">18.任勇军;<strong>方黎明;</strong>葛春鹏;王建东, 基于可搜索密文的WSN数据安全处理方法, 发明专利, 专利申请日：2010-07-28, 中国, 申请号:201010238740.0</div>
<div class="justify">19.<strong>方黎明;</strong> 葛春鹏, 一种基于多agent的智能家居学习系统及方法, 发明专利, 专利申请日：2013-02-01, 中国, 申请号：201310040235.9</div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">20.王建东; 孙婷; <strong>方黎明; </strong>朱新峰; 孙茂圣; 王丽娜,基于AES加密的机场噪声预测数据网络传输方法, 发明专利, 专利申请日：2013-06-8, 中国, 申请号: CN201310226583.5 </div>
<div style="text-align:justify;text-align-last:left;margin-bottom:10px;">21.赵国安;刘玉龙;薛琳强;<strong>方黎明;</strong>郁斌;田明, 无线传感器网络中执行非对称密码的方法, 发明专利, 专利申请日：2010-04-29, 中国, 申请号: 201010159400.9</div>
<div class="justify">22.<strong>方黎明, </strong>徐圣, 陈小杰, 一种智能家居网关, 实用新型, 中国, 申请号: 201220435047.7</div>
<div class="justify">23.<strong>方黎明,</strong>葛春鹏, 一种智能家居监控系统, 实用新型, 中国, 申请号: 201220430638.5</div>
<div class="justify">24.<strong>方黎明, </strong>应华, 徐圣,一种节能插座控制电路, 实用新型, 中国, 申请号: 201220643650.4</div>
   </div>
         </div> 
     </div> 
</div> 
</div>
                <div class="page_num"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <script>
  $('table').each(function() {
    $(this).wrap("<div class='tableCon' style='width:100%;overflow-x:auto'></div>");
    $(this).parent('.tableCon').before("<p class='all' style='display:none;color:#f89a20;padding:10px 0'>左右滑动查看表格全部<span><span></div>")
    if ($(this).parent('.tableCon').width() < $(this).width()) {
      $(".all").css("display", "block")
    }
  })
  </script>
  <div class="foot">
    <div class="container container-pd">
      <div class="fo-con clearfix">
        <div class="row">
          <div class="col xs-12 sm-7 md-8 lg-9">
            <div class="fo-l">
              <p>地址：江苏省南京市江宁区将军大道29号</p>
              <p>邮政编码: 211106 </p>
              <p>版权所有：南京航空航天大学计算机科学与技术学院/人工智能学院 ALL RIGHTS RESERVED 苏ICP备05070685号 <a href="http://site.nuaa.edu.cn/" target="_blank">后台管理</a> <a href="mailto:njliujr@nuaa.edu.cn" target="_blank"><img src="http://site.nuaa.edu.cn/_upload/tpl/04/02/1026/template1026/images/email.png"> 书记信箱</a> <a href="mailto:cb_china@nuaa.edu.cn" target="_blank"><img src="http://site.nuaa.edu.cn/_upload/tpl/04/02/1026/template1026/images/email.png"> 院长信箱</a></p>
            </div>
          </div>
          <div class="col xs-12 sm-5 md-4 lg-3">
            <div class="fo-r">
              <h3>友情链接</h3>
              <div class="fo-r-con clearfix">
                <div class="select fl" frag="窗口15" portletmode="simpleNews" configs="{'c8':'1','c42':'320','c25':'320','c30':'0','c29':'1','c22':'0','c23':'1','c34':'300','c20':'0','c31':'0','c16':'1','c3':'30','c2':'标题','c27':'480','c43':'0','c17':'0','c5':'_blank','c24':'240','c32':'','c26':'1','c37':'1','c28':'640','c40':'1','c15':'0','c14':'1','c44':'0','c33':'500','c10':'50','c18':'yyyy-MM-dd','c36':'0','c1':'1','c6':'-1','c19':'yyyy-MM-dd','c21':'0','c4':'1','c35':'-1:-1','c39':'300','c38':'100','c7':'1','c12':'0','c9':'0','c11':'1','c13':'200','c41':'240'}" contents="{'c2':'0', 'c1':'/友情链接'}">
                  <p>校外导航链接<i></i></p>
                  <ul>
                    
                    <li><a href='javascript:void(0)' target='_blank' title='友情链接'>友情链接</a></li>
                    
                  </ul>
                </div>
                <div class="fo-lnk clearfix fl"> <a class="wx" href="javascript:;">
                    <div class="ewm"><img src="http://site.nuaa.edu.cn/_upload/tpl/04/02/1026/template1026/images/ewm.png" /></div>
                  </a> <a class="wb" href="javascript:void(0)"></a> </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <script>
  $(function() {
    $(".select p").on("click", function(e) {
      var objDiv = $(this).next('ul');
      if (objDiv.css('display') == 'none') {
        objDiv.css('display', 'block');
        objDiv.parent().siblings().find('ul').css('display', 'none');
        event.stopPropagation();
      } else {
        objDiv.css('display', 'none');
      }
      $(document).one("click", function() {
        objDiv.hide();
      });
      e.stopPropagation();
    });
    $(".select p").next('ul').on("click", function(e) {
      e.stopPropagation();
    });
    $('.wx').on('click', function() {
      $('.ewm').toggle();
    });
  });
  </script>
</body>

</html>
 <img src="http://site.nuaa.edu.cn/_visitcount?siteId=68&type=2&columnId=1956" style="display:none" width="0" height="0"></image>
