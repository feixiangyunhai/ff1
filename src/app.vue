<template>
  <div id="app">
        <div class="box">
        <div class="box_i">
          <img src="./img/img/one-2.png" alt="">
          <span class="sp_i">蛋糕贝式严选</span>
          <div class="jiantou"></div>
          <div class="hov aa"></div>
        </div>
        <div class="box_i">
          <img src="https://res.bestcake.com/images/new-index/one-3.png?v=1" alt="">
          <span class="sp_i">糖果西点</span>
          <div class="jiantou"></div>
          <div class="hov bb"></div>
        </div>
        <div class="box_i">
          <img src="./img/img/one-4.png" alt="">
          <span class="sp_i">乳品系列</span>
          <div class="jiantou"></div>
          <div class="hov cc"></div>
        </div>
        <div class="box_i">
          <img src="./img/img/one-5.png" alt="">
          <span class="sp_i">其他</span>
          <div class="jiantou"></div>
          <div class="hov dd"></div>
        </div>
        <div class="box_i">
          <img src="./img/img/one-1.png" alt="">
          <span class="sp_i">蛋糕匠心原创</span>
          <div class="jiantou"></div>
          <div class="hov ee"></div>
        </div>

        <div class="box_i">
          --------------------------------
        </div>

        <div class="box_i">
          <img src="./img/img/one-8.png" alt="">
          <span class="sp_i">aaa</span>
          <div class="jiantou"></div>
        </div>
        <div class="box_i">
          <img src="./img/img/one-9.png" alt="">
          <span class="sp_i">aaa</span>
          <div class="jiantou"></div>
        </div>
        <div class="box_i">
          <img src="./img/img/one-10.png" alt="">
          <span class="sp_i">aaa</span>
          <div class="jiantou"></div>
        </div>
      </div>


        <div class="lb">
        <div class="block">
          <el-carousel height="442px">
            <el-carousel-item v-for="item in im" :key="item">
              <img :src="item" alt="" class="imggg">
            </el-carousel-item>
          </el-carousel>
        </div>
        </div>
        <div class="main-er">
      <div class="mains">
        <img class="img1" src="https://res.bestcake.com/images/new-index/r0.png?v=2">
      </div>
      <div class="mainz">
        <img class="img2" src="https://res.bestcake.com/images/new-index/xz.jpg?v=2">
      </div>
      <div class="mainz">
        <img class="img3" src="https://res.bestcake.com/images/new-index/r2.png?v=2">
      </div>
      <div class="mainz">
        <img class="img4" src="https://res.bestcake.com/images/new-index/tz1.png">
      </div>
    </div>
    <div class="main-san">
      <img src="https://res.bestcake.com/images/new-index/index-three-title.png" class="img6">
      <div class="mainq">限时抢购</div>
    </div>
    <div class="mainw">
      <div class="main-q">
        <img src="https://res.bestcake.com/images/new-index/sale/茶色生香.png?v=1" class="shishi">
      </div>
      <div class="main-t">茶色生香1.2磅</div>
      <div class="main-y">
        <span class="main-u">￥</span>
        <span class="main-i">198.00</span>
      </div>
    </div>
    <div class="maine">
      <div class="main-w">
        <img src="https://res.bestcake.com/images/new-index/sale/冻烤燃情芝士.png?v=1">
      </div>
      <div class="main-t">冻烤燃情芝士1.2磅</div>
      <div class="main-y">
        <span class="main-u">￥</span>
        <span class="main-i">198.00</span>
      </div>
    </div>
    <div class="mainr">
      <div class="main-e">
        <img src="https://res.bestcake.com/images-2/index-3/sale/朗姆香栗.png">
      </div>
      <div class="main-t">朗姆香栗1.2磅</div>
      <div class="main-y">
        <span class="main-u">￥</span>
        <span class="main-i">198.00</span>
      </div>
    </div>
    <div class="maint">
      <div class="main-r">
        <img src="https://res.bestcake.com/images-2/index-3/sale/沃尔夫斯堡之春.png">
      </div>
      <div class="main-t">沃尔夫斯堡之春1.2磅</div>
      <div class="main-y">
        <span class="main-u">￥</span>
        <span class="main-i">198.00</span>
      </div>
    </div>
      <img src="https://res.bestcake.com/images/new-index/pc1.png?v=1" class="img7">
    <!-- 原创精选 -->
    <div class="main index-five">
      <div class="index-five-title">
        <div class="index-five-title-l">匠心·原创</div>
        <div class="index-five-title-r">查看更多</div>
      </div>
      <div class="index-five-list">
        <div class="index-five-list-l">
          <img class="index-five-img" src="https://res.bestcake.com/images/new-index/index-five-1.png?v=2" alt="">
        </div>
<div class="index-five-list-r">
  <div class="index-five-tab">
     <div class="index-five-tab-cake">
     <img class="index-three-cake" src="https://res.bestcake.com/images/new-index/p/极地牛乳.png">
     </div>
     <div class="index-five-tab-name">
        <span style="color: #000; font-size: 16px;">极地牛乳</span>
        </div>
        <div class="index-five-tab-price">
        <span style="color: #ff3300; font-size: 17px;">￥</span>
        <span style="color: #ff3300; font-size: 22px;">198.00</span>
        </div>
        <div class="index-five-tab-volume">
        <span style="color: #a8a8a8; font-size: 15px;">销量 <abbr>547564</abbr></span>
          </div>
          <div class="index-five-tab-car">
            <img class="index-three-title-car" src="https://res.bestcake.com/images/new-index/index-five-tab-car.png?v=1" width="22" height="22">
            </div>
          <div class="index-five-tab-tc" style="width: 300px; display: none;">
          <div class="index-five-tab-tc1">
          <span style="color: #313131; font-size: 16px; margin-left:28px;">￥</span>
          <span style="color: #313131; font-size: 16px;">198.00</span>
          <span style="color: #313131; font-size: 16px;">/</span>
          <span style="color: #878787; font-size: 16px;">1.2磅</span>
          </div>
          <div class="index-five-tab-tc3">
          <div class="shop-car-list">
      <div class="shop_car_num borde">
      <num>1.2磅</num>
      <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ">
      </div>
      <div class="shop_car_num">
      <num>2.2磅</num>
      <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
      </div>
      <div class="shop_car_num">
      <num>3.2磅</num>
      <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
      </div>
      <div class="shop_car_num">
      <num>7.0磅</num>
      <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
      </div>
      </div>
      </div>
      <div class="index-five-tab-tc3">
      <div class="index-five-l">加入购物车</div>
      <div class="index-five-r">立即购买</div>
  </div>
 </div>
</div>
<div class="index-five-tab">
  <div class="index-five-tab-cake">
    <img class="index-three-cake" src="https://res.bestcake.com/images/new-index/p/情定爱情海.png">
</div>
  <div class="index-five-tab-name">
   <span style="color: #000; font-size: 16px;">情定爱情海</span>
</div>
<div class="index-five-tab-price">
  <span style="color: #ff3300; font-size: 17px;">￥</span>
    <span style="color: #ff3300; font-size: 22px;">198.00</span>
</div>
  <div class="index-five-tab-volume">
  <span style="color: #a8a8a8; font-size: 15px;">销量 <abbr>413412</abbr></span>
</div>
  <div class="index-five-tab-car">
  <img class="index-three-title-car" src="https://res.bestcake.com/images/new-index/index-five-tab-car.png?v=1" width="22" height="22">
  </div>
  <div class="index-five-tab-tc" style="width: 300px; display: none;">
  <div class="index-five-tab-tc1">
  <span style="color: #313131; font-size: 16px; margin-left:28px;">￥</span>
  <span style="color: #313131; font-size: 16px;">198.00</span>
  <span style="color: #313131; font-size: 16px;">/</span>
    <span style="color: #878787; font-size: 16px;">1.2磅</span>
 </div>
   <div class="index-five-tab-tc3">
     <div class="shop-car-list">
      <div class="shop_car_num borde">
         <num>1.2磅</num>
   <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ">
</div>
 <div class="shop_car_num">
  <num>2.2磅</num>
  <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
</div>
  <div class="shop_car_num">
  <num>3.2磅</num>
   <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
</div>
  <div class="shop_car_num">
    <num>7.0磅</num>
  <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
</div>
</div>
</div>
<div class="index-five-tab-tc3">
  <div class="index-five-l">加入购物车</div>
 <div class="index-five-r">立即购买</div>
</div>
</div>
</div>
            
  <div class="index-five-tab">
    <div class="index-five-tab-cake">
      <img class="index-three-cake" src="https://res.bestcake.com/images/new-index/p/白色红丝绒.png">
</div>
  <div class="index-five-tab-name">
    <span style="color: #000; font-size: 16px;">白色红丝绒</span>
</div>
  <div class="index-five-tab-price">
    <span style="color: #ff3300; font-size: 17px;">￥</span>
      <span style="color: #ff3300; font-size: 22px;">198.00</span>
</div>
  <div class="index-five-tab-volume">
  <span style="color: #a8a8a8; font-size: 15px;">销量 <abbr>163055</abbr></span>
</div>
  <div class="index-five-tab-car">
<img class="index-three-title-car" src="https://res.bestcake.com/images/new-index/index-five-tab-car.png?v=1" width="22" height="22">
</div>
<div class="index-five-tab-tc" style="width: 300px; display: none;">
  <div class="index-five-tab-tc1">
  <span style="color: #313131; font-size: 16px; margin-left:28px;">￥</span>
    <span style="color: #313131; font-size: 16px;">198.00</span>
 <span style="color: #313131; font-size: 16px;">/</span>
    <span style="color: #878787; font-size: 16px;">1.2磅</span>
  </div>
 <div class="index-five-tab-tc3">
<div class="shop-car-list">
  <div class="shop_car_num borde">
  <num>1.2磅</num>
    <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ">
    </div>
    <div class="shop_car_num">
  <num>2.2磅</num>
<img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
</div>
  <div class="shop_car_num">
    <num>3.2磅</num>
  <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
</div>
  <div class="shop_car_num">
    <num>7.0磅</num>
     <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
</div>
</div>
</div>
<div class="index-five-tab-tc3">
  <div class="index-five-l">加入购物车</div>
<div class="index-five-r">立即购买</div>
</div>
 </div>
</div>
 <div class="index-five-tab">
  <div class="index-five-tab-cake">
 <img class="index-three-cake" src="https://res.bestcake.com/images/new-index/p/奥利奥雪域牛乳芝士.png">
</div>
<div class="index-five-tab-name">
<span style="color: #000; font-size: 16px;">奥利奥雪域牛乳芝士</span>
</div>
<div class="index-five-tab-price">
  <span style="color: #ff3300; font-size: 17px;">￥</span>
    <span style="color: #ff3300; font-size: 22px;">198.00</span>
</div>
  <div class="index-five-tab-volume">
<span style="color: #a8a8a8; font-size: 15px;">销量 <abbr>327981</abbr></span>
</div>
<div class="index-five-tab-car">
  <img class="index-three-title-car" src="https://res.bestcake.com/images/new-index/index-five-tab-car.png?v=1" width="22" height="22">
 </div>
<div class="index-five-tab-tc" style="width: 300px; display: none;">
 <div class="index-five-tab-tc1">
  <span style="color: #313131; font-size: 16px; margin-left:28px;">￥</span>
    <span style="color: #313131; font-size: 16px;">198.00</span>
<span style="color: #313131; font-size: 16px;">/</span>
  <span style="color: #878787; font-size: 16px;">1.2磅</span>
 </div>
<div class="index-five-tab-tc3">
<div class="shop-car-list">
 <div class="shop_car_num borde">
 <num>1.2磅</num>
<img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ">
</div>
<div class="shop_car_num">
<num>2.2磅</num>
  <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" style="display: none;">
</div>
                        
<div class="shop_car_num" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">3.2磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data" style="display: none;">
                            </div>
                        
                            <div class="shop_car_num" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">7.0磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data" style="display: none;">
                            </div>
                        </div>
                    </div>
                    <div class="index-five-tab-tc3">
                        <div class="index-five-l" data-bind="click:function(){$root.buy($data,'cart')}">加入购物车</div>
                        <div class="index-five-r" data-bind="click:function(){$root.buy($data,'buy')}">立即购买</div>
                    </div>
                </div>
            </div>
            
            <div class="index-five-tab">
                <div class="index-five-tab-cake" data-bind="click:function(){$root.jumpHref($data.ProductHref)}">
                    <img class="index-three-cake" data-bind="attr:{src:'https://res.bestcake.com'+$data.ImgUrl}" src="https://res.bestcake.com/images/new-index/p/草莓拿破仑.png">
                </div>
                <div class="index-five-tab-name">
                    <span style="color: #000; font-size: 16px;" data-bind="text:$data.Name">草莓拿破仑</span>
                </div>
                <div class="index-five-tab-price">
                    <span style="color: #ff3300; font-size: 17px;">￥</span>
                    <span style="color: #ff3300; font-size: 22px;" data-bind="text:($data.CostPrice||$data.Price).toFixed(2)">198.00</span>
                </div>
                <div class="index-five-tab-volume">
                    <span style="color: #a8a8a8; font-size: 15px;">销量 <abbr data-bind="text:$data.SaleCount || 0">14768</abbr></span>
                </div>
                <div class="index-five-tab-car" data-bind="click:function(){$root.openCart($data)}">
                    <img class="index-three-title-car" src="https://res.bestcake.com/images/new-index/index-five-tab-car.png?v=1" width="22" height="22">
                </div>
                <div class="index-five-tab-tc" style="width: 300px; display: none;" data-bind="visible:$data.ShowSizeList">
                    <div class="index-five-tab-tc1">
                        <span style="color: #313131; font-size: 16px; margin-left:28px;">￥</span>
                        <span style="color: #313131; font-size: 16px;" data-bind="text:$data.ChoosePrice().toFixed(2)">198.00</span>
                        <span style="color: #313131; font-size: 16px;">/</span>
                        <span style="color: #878787; font-size: 16px;" data-bind="text:$data.ChooseSize">1.2磅</span>
                    </div>
                    <div class="index-five-tab-tc3">
                        <div class="shop-car-list" data-bind="foreach:$data.SizeList">
                            <div class="shop_car_num borde" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">1.2磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data">
                            </div>
                        
                            <div class="shop_car_num" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">2.2磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data" style="display: none;">
                            </div>
                        
                            <div class="shop_car_num" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">7.0磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data" style="display: none;">
                            </div>
                        </div>
                    </div>
                    <div class="index-five-tab-tc3">
                        <div class="index-five-l" data-bind="click:function(){$root.buy($data,'cart')}">加入购物车</div>
                        <div class="index-five-r" data-bind="click:function(){$root.buy($data,'buy')}">立即购买</div>
                    </div>
                </div>
            </div>
            
            <div class="index-five-tab">
                <div class="index-five-tab-cake" data-bind="click:function(){$root.jumpHref($data.ProductHref)}">
                    <img class="index-three-cake" data-bind="attr:{src:'https://res.bestcake.com'+$data.ImgUrl}" src="https://res.bestcake.com/images/new-index/p/莱茵河莓妖精.png">
                </div>
                <div class="index-five-tab-name">
                    <span style="color: #000; font-size: 16px;" data-bind="text:$data.Name">莱茵河莓妖精</span>
                </div>
                <div class="index-five-tab-price">
                    <span style="color: #ff3300; font-size: 17px;">￥</span>
                    <span style="color: #ff3300; font-size: 22px;" data-bind="text:($data.CostPrice||$data.Price).toFixed(2)">198.00</span>
                </div>
                <div class="index-five-tab-volume">
                    <span style="color: #a8a8a8; font-size: 15px;">销量 <abbr data-bind="text:$data.SaleCount || 0">285697</abbr></span>
                </div>
                <div class="index-five-tab-car" data-bind="click:function(){$root.openCart($data)}">
                    <img class="index-three-title-car" src="https://res.bestcake.com/images/new-index/index-five-tab-car.png?v=1" width="22" height="22">
                </div>
                <div class="index-five-tab-tc" style="width: 300px; display: none;" data-bind="visible:$data.ShowSizeList">
                    <div class="index-five-tab-tc1">
                        <span style="color: #313131; font-size: 16px; margin-left:28px;">￥</span>
                        <span style="color: #313131; font-size: 16px;" data-bind="text:$data.ChoosePrice().toFixed(2)">198.00</span>
                        <span style="color: #313131; font-size: 16px;">/</span>
                        <span style="color: #878787; font-size: 16px;" data-bind="text:$data.ChooseSize">1.2磅</span>
                    </div>
                    <div class="index-five-tab-tc3">
                        <div class="shop-car-list" data-bind="foreach:$data.SizeList">
                            <div class="shop_car_num borde" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">1.2磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data">
                            </div>
                        
                            <div class="shop_car_num" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">2.2磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data" style="display: none;">
                            </div>
                        
                            <div class="shop_car_num" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">3.2磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data" style="display: none;">
                            </div>
                        
                            <div class="shop_car_num" data-bind="click:function(){$root.ChooseSize($parent,$data)},css:$parent.ChooseSize() === $data?'borde':''">
                                <num data-bind="text:$data">7.0磅</num>
                                <img src="https://res.bestcake.com/images/new-index/seven_7.png?v=1" alt="选择" class="shop_car_num_yes displ" data-bind="visible:$parent.ChooseSize() === $data" style="display: none;">
                            </div>
                        </div>
                    </div>
                    <div class="index-five-tab-tc3">
                        <div class="index-five-l" data-bind="click:function(){$root.buy($data,'cart')}">加入购物车</div>
                        <div class="index-five-r" data-bind="click:function(){$root.buy($data,'buy')}">立即购买</div>
                    </div>
                </div>
            </div>
            <!--/ko-->
        </div>





















      </div>
    </div>


    <router-view/>
  </div>
</template>
<script>
export default {
  name: 'app',
  data(){
    return{
      im:[
        ['https://res.bestcake.com/images-2/banner/pc-banner-0yuan.jpg'],
        ['https://res.bestcake.com/images-2/banner/pc-banner-tips.jpg'],
        ['https://res.bestcake.com/m-images/banner_new/274987921840067700.jpg'],
        ['https://res.bestcake.com/m-images/banner_new/732636547069428100.jpg'],
        ['https://res.bestcake.com/m-images/banner_new/503204226149236400.jpg']
      ],
      tuu:[]
    }
  }
}

</script>

<style>
/*轮播*/
.lb{
  width:880px;
  height:440px;
  
  display:inline-block;
  position:absolute;
  top:180px;
  left:363px;
}
.imggg{
  width:100%;
  height:100%;
  z-index:10;
}






#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
}

/*轮播旁边的列表*/
.box{
  height:442px;
  width:228px;
  background: #26CAD3;
  display: inline-block;
  margin-top:180px; 
  margin-left:10%; 
.box_i{
  width:173px;
  height:20px;
  margin-bottom:2px;
  margin-top:10px;
  color: #fff;
  font-size: 16px;
  line-height: 21px;
  /*position: relative;*/
  padding: 8.5px 24px 8.5px 31px;
  cursor: pointer;

.jiantou{
  width:7px;
  height:12px;
  background-image:url(https://res.bestcake.com/images/new-index/jt.png);
  background-repeat:no-repeat;
  display: inline-block;
  float:right; 
}
.hov{
  width:900px;
  height:442px;
  /*display:block;*/
  background: red;
  position:absolute;
  left:363px;
  top:180px;
  background-repeat:no-repeat;
  background-size:cover;
  display: none;
  background-position:center center;
  z-index:888;
}
.aa{background-image: url(./img/a.png);}
.bb{background-image: url(./img/b.png);}
.cc{background-image: url(./img/c.png);}
.dd{background-image: url(./img/d.png);}
.ee{background-image: url(./img/e.png);}
}
.box_i img{
  width:22px;
  height:22px;
}
.box_i:hover .hov{
  display: block;
}
}


/*限时抢购*/

.main-er{
    width:1100px;
    height:167px;
    /* // background:red; */
    margin:0 auto;
    margin-top:14px;
}
    .mains{
      width:200px;
      height:150px;
      /* // background:green; */
      float:left;
      .img1{
        width:220px;
        height:150px;
        margin-left:10px;
      }
    }
    .mainz{
      width:280px;
      height:150px;
      // background:green;
      margin-left:10px;
      float:right;
      .img2{
        width:277px;
        height:150px;
      }
      .img3{
        width:277px;
        height:150px;
      }
      .img4{
        width:277px;
        height:150px;
      }
    }
  }
  .main-san{
    width:1100px;
    height:26px;
    // background:red;
    margin:0 auto;
    margin-top:40px;
    .img6{
      float:left;
    }
    .mainq{
      float: left;
      font-size: 25px;
      color: #1db0b8;
      line-height: 25px;
      margin-left: 8px;
      margin-right: 8px;
    } 
  }
  .mainw{
    width: 280px;
    height: 246px;
    float: left;
    margin-right: 10px;
    margin-top:20px;
    position: relative;
    background: #fafafa;
    margin-left:110px;
    .main-q{
      width:280px;
      height:173px;
    }
    .mainw:hover .shishi{
      background-color:#fff;
      
    }
    .main-t{
      font-size: 14px;
      color: #2a2a2a;
      text-align: center;
      height: 35px;
      line-height: 40px;
    }
    .main-y{
      text-align: center;
      font-size: 0;
      color:red;
      .main-u{
        color: #ff3300;
        font-size: 14px;
      }
      .main-i{
        color: #ff3300;
        font-size: 14px;
      }
    }
  }
  .maine{
    width: 280px;
    height: 246px;
    float: left;
    margin-right: 10px;
    margin-top:20px;
    position: relative;
    background: #fafafa;
    .main-w{
      width:280px;
      height:173px;
    }
    .main-t{
      font-size: 14px;
      color: #2a2a2a;
      text-align: center;
      height: 35px;
      line-height: 40px;
    }
    .main-y{
      text-align: center;
      font-size: 0;
      color:red;
      .main-u{
        color: #ff3300;
        font-size: 14px;
      }
      .main-i{
        color: #ff3300;
        font-size: 14px;
      }
    }
  }
  .mainr{
    width: 280px;
    height: 246px;
    float: left;
    margin-right: 10px;
    margin-top:20px;
    position: relative;
    background: #fafafa;
    .main-e{
      width:280px;
      height:173px;
    }
    .main-t{
      font-size: 14px;
      color: #2a2a2a;
      text-align: center;
      height: 35px;
      line-height: 40px;
    }
    .main-y{
      text-align: center;
      font-size: 0;
      color:red;
      .main-u{
        color: #ff3300;
        font-size: 14px;
      }
      .main-i{
        color: #ff3300;
        font-size: 14px;
      }
    }
  }
  .maint{
    width: 280px;
    height: 246px;
    float: left;
    margin-right: 10px;
    margin-top:20px;
    position: relative;
    background: #fafafa;
    .main-r{
      width:280px;
      height:173px;
    }
    .main-t{
      font-size: 14px;
      color: #2a2a2a;
      text-align: center;
      height: 35px;
      line-height: 40px;
    }
    .main-y{
      text-align: center;
      font-size: 0;
      .main-u{
        color: #ff3300;
        font-size: 14px;
      }
      .main-i{
        color: #ff3300;
        font-size: 14px;
      }
    }
  }
  .img7{
    width:1150px;
    height:130px;
    margin-top:20px;
    margin-left:110px;
  }

  
  /*原创精选*/
.index-five {
  margin-top: 30px;
}
.main {
    width: 1200px;
    margin: 0 auto;
.index-five-title-l {
    float: left;
    font-size: 24px;
    color: #26cad3;
    margin-bottom: 30px;
}
.index-five-title-r {
    float: right;
    position: relative;
    margin-right: 30px;
    cursor: pointer;
    margin-top: 10px;
    color: #878787;
}
.index-five-list {
    clear: both;
.index-five-list-l {
    width: 258px;
    height: 626px;
    float: left;
    margin-right: 11px;
.index-five-img {
    width: 259px;
    height: 609px;
    transition: all .2s linear;
    position: relative;
}
}
.index-five-list-r {
    position: relative;
    float: left;
.index-five-tab {
    width: 300px;
    height: 297px;
    float: left;
    margin-left: 10px;
    margin-top: 14px;
    background: #fff;
    -webkit-transition: all .2s linear;
    transition: all .2s linear;
    position: relative;
}
}
}
}
</style>
