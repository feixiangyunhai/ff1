<template>
  <div id="HelloWorld">
    <marquee behavior="scroll" scrollamount="10" onmouseover=this.stop() onmouseout=this.start()>
      贝思客官方申明：我司近期发现有客户通过非正常渠道售卖的代金卡无法正常使用，目前我司正通过法律途径解决此问题。我司在此郑重申明，从未授权过任何渠道售卖我司代金卡，请客户通过正常渠道（如：官网、公司销售）进行购买消费。   公告日期：2017年10月09日
    </marquee>
    <div class="topBox">
      <p>股票代码 835491</p>
      <!-- 图标 -->
      <img src="../img/img/logo.png" alt="" class="logo">

      <!-- 列表 -->
      <ul class="ul_a">
        <li id="tu" @click="zhe">
        <span class="q">北京</span>
        <div class="zhezhao" v-show="bol">
        <div class="zhezhaobai">
          <div>上海</div>
          <div>台州</div>
          <div>苏州</div>
          <div>宁波</div>
          <div>乌鲁木齐</div>
          <div>霜月村</div>
          <div>东海</div>
          <div>橘子镇</div>
          <div>军舰岛</div>
          <div>玛丽乔亚</div>
          <div>红土大陆</div>
          <div>爱琴海</div>
          <div>太阳</div>
        </div>
        <span class="yin" @click="yinc">×</span>
        </div>
        </li>
        <li>
          <router-link class="lian" to="/Vue">
          首页
          </router-link>
        </li>
        <li class="tab1">
        <router-link class="lian" to="/Vue">
          下午茶
          </router-link>
        <div class="cha a"></div>
        </li>
        <li class="tab1">
        <router-link class="lian" to="/Vue">
          送亲子
          </router-link>
        <div class="cha b"></div>
        </li>
        <li class="tab1">
        <router-link class="lian" to="/Vue">
          送长辈
          </router-link>
        <div class="cha c"></div>
        </li>
        <li class="tab1">
        <router-link class="lian" to="/Vue">
          送闺蜜
          </router-link>
        <div class="cha d"></div>
        </li>
        <li class="tab1">
        <router-link class="lian" to="/Vue">
          送恋人
          </router-link>
        <div class="cha e"></div>
        </li>
        <li id="zui">
          <div class="iisBox">
            <img src="https://res.bestcake.com/images/new-index/search.png?v=1" alt="" class="sou">
            <input type="text" class="kuang" placeholder="请输入要查找的内容">
            <span class="an">搜索</span>
          </div>
        </li>
      </ul>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
    data(){
      return{
        bol:false,
        ar:['上海,台州,苏州,宁波,乌鲁木齐,霜月村,东海,橘子镇,军舰岛,玛丽乔亚,红土大陆,爱琴海,太阳']
      }
    },

    methods:{

      
      yinc(e){
        this.bol=false
        console.log(e)
      },
      zhe(e){
        this.bol=true
        console.log(this.bol)
      }
  }
}

</script>

<style>
#HelloWorld {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
*{
  margin:0;
  padding: 0;
}
html,body{
  height:100%;
  width:100%;
}
marquee{
  width:80%;
  height:40px;
  /*background:green;*/
  font-size: 14px;
  position:absolute;
  top:2px;
  left:10%;
}
.topBox{
  width:80%;
  height:77px;
  margin-top:60px;
  margin-left:10%; 
  /*margin-top: -600px;*/
  position: absolute;
  top:-10px;
}
p{
  width:100%;
  height:22px;
  font-size:14px;
  color:#878787;
}
.logo{
  width:10%;
  height:55px;
}
/*列表*/
.ul_a{
  width:90%;
  height:55px;
  /*background: red;*/
  display:block;
  float:right;
  line-height: 55px;
}
.ul_a li{
  width:9%;
  height:55px;
  display:inline-block;
  /*background: green;*/
  margin-top:-20px;
  padding-top:0; 
  text-align: center;
}
.tab1:hover .lian{
  color: #26cad3;
  cursor:pointer;
}
#tu{
  width:96px;
  height:55px;
  background-image: url(../img/img/earth.png);
  background-repeat:no-repeat;
  background-position:center center ;
  /*margin-top:-20px;*/
}
.q{
  padding-left:40%;
  color:#fff;
}
.lian{
  padding-left:40%;
  color:#000;
  text-decoration: none;
}
/*搜索三联*/

#zui{
  display: inline-block;
  width:317px;
  height:100%;
  /*background:orange;*/
}
.sou{
  width:22px;
  height:22px;
  display: inline-block;
  position: absolute;
  left:55px;
  top: 18px;
}
.kuang{
  display: inline-block;
  width: 240px;
  font-size: 14px;
  height: 29px;
  padding: 0 30px;
  border: 1px solid #ddd;
}
.an{
  width:80px;
  height:30px;
  display: inline-block;
  font-size: 16px;
  background: #26cad3;
  color: #fff;
  line-height: 30px;
  margin: -83px;
  padding: 0;


}
.iisBox{
  width:317px;
  height:70%;
  /*background:blue;*/
  display: inline-block;
  position: relative;
}
.cha{
  width:1120px;
  height:216px;
  background: red;
  display: none;
  z-index:999;
}
.tab1:hover .cha{
  display:block;
  position:absolute;
  /*background-image:url(./img/1.png);*/
  left:0%;
}
.a{background-image:url(../img/1.png);}
.b{background-image:url(../img/2.png);}
.c{background-image:url(../img/3.png);}
.d{background-image:url(../img/4.png);}
.e{background-image:url(../img/5.png);}



.zhezhao{
  width:1349px;
  height:660px;
  background:rgba(0,0,0,0.6);
  position: fixed;
  left:0;
  top:0;
  z-index: 999;
  /*display: none;*/
}
.zhezhaobai{
  width:40%;
  height:40%;
  background: #fff;
  vertical-align:middle;
  line-height:10px;
  margin:100px auto;
}
.zhezhaobai div{
  width:71px;
  height:27px;
  color:#000;
  margin-left:25px;
  line-height:40px;
  z-index: 1000;
  display:inline-block;
  margin:40px auto;
  border-radius:20%;
  /*background:red;*/
}
.zhezhaobai div:hover{
  color:#fff;
  background:blue;
}
.yin{
  width:40px;
  height:40px;
  border-radius:50%;
  display:inline-block;
  border:2px #fff solid;
  font-size:65px;
  line-height: 40px;
  color:#fff;
  padding: 0;
  cursor:pointer;
}
</style>
