<style>
.header {
  width: 100%;
  height: 99px;
  background-color: #216767;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo {
  width: 133px;
  height: 38px;
  margin-left: 80px;
  display: block;
}
.phone {
  padding-right: 30px;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.phone img {
  width: 43px;
  height: 41px;
  margin-right: 14px;
}
.phone_text {
  color: #f2d397;
  font-size: 14px;
}
.phone_text p {
  font-size: 12px;
}
.phone_text span {
  font-size: 24px;
  font-weight: 600;
}
/* 内容 */
.conter {
  width: 100%;
  height: 613px;
}
.conter img {
  width: 100%;
  height: 100%;
}

/* logo 介绍 */
.logo-duce {
  display: flex;
  flex-direction: row;
  padding: 20px 0;
  background: url("../assets/bg.png") no-repeat;
  background-size: 100% 100%;
}
.logo-box {
  display: flex;
  flex: 1;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.logo-box img {
  width: 72px;
  height: 72px;
}
.logo-text {
  color: #216b6c;
  text-align: center;
}
.logo-text h3 {
  font-size: 18px;
  line-height: 40px;
}
.logo-text p {
  line-height: 20px;
}
/* 产品介绍 */
.product {
  margin: 38px 83px;
}
.product-title {
  display: flex;
  flex-direction: column;
  position: relative;
  padding-left: 14px;
}

.product-title::after {
  content: "";
  position: absolute;
  width: 5px;
  height: 100%;
  top: 0px;
  left: 0;
  background-color: #206969;
}
.product-title::before {
  content: "";
  position: absolute;
  top: 0px;
  left: 6px;
  width: 1px;
  height: 100%;
  border-left: 1px dashed #206969;
}
.title {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.title h2 {
  font-size: 36px;
  line-height: 40px;
  color: #206969;
}
.title h3 {
  font-size: 26px;
  line-height: 40px;
  color: #efd095;
}
.product-title p {
  color: #000;
  margin-top: 15px;
  font-size: 16px;
  line-height: 30px;
}
/* 轮播图 */
.swiper {
}

/* 传统 */
.tradition {
  margin-top: 51px;
  background-color: #eee;
  padding-bottom: 53px;
}
.bg {
  width: 100%;
  height: 296px;
}
.bg1 {
  background: url("../assets/bg1.png") no-repeat;
  background-size: 100% 100%;
}
.img-trad {
  width: 100%;
  height: 92.7px;
  display: flex;
  justify-content: center;
  margin-top: -251px;
}
.img-trad img {
  width: 505px;
  height: 92.7px;
}

.trad-box {
  width: 505px;
  margin: auto;
  background-color: #fff;
  margin-top: 19px;
  display: flex;
  flex-direction: row;
  box-shadow: 5px 5px 5px #fff;
}
.trad-li {
  display: flex;
  flex: 1;
  justify-content: center;
  flex-direction: column;
}
.trad-list {
  padding: 10px;
  border: 2px solid #1f9999;
  margin: 20px;
  margin-top: 30px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.trad-list img {
  width: 64px;
  height: 64px;
  margin: 10px 0;
}
.trad-list .block {
  width: 60px;
  height: 3px;
  border-top: 4px solid #000;
}
.trad-list p {
  text-align: center;
  color: #333333;
}
/* 渠道 */
.channel {
  width: 100%;
  height: 255px;
}
.channel img {
  width: 100%;
  height: 100%;
}
.drap {
  margin: 20px 0;
  display: flex;
  justify-content: center;
}
.drap img {
  width: 41px;
  height: 22px;
}

/* 产品线 */
.prad-line {
  justify-content: center;
  display: flex;
  flex-direction: row;
}

.lin-list {
  width: 170px;
}
.lin-list img {
  width: 100%;
  height: 205px;
}
.lin-box {
  width: 100%;
  height: 142px;
  background-color: #33aaaa;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  line-height: 30px;
  font-size: 18px;
  text-align: center;
}

/* 八大优势 */
.advantage {
  width: 100%;
  display: flex;
  justify-content: center;
  margin: 38px 0;
}

.advantage img {
  width: 592px;
  height: 89px;
}
.block {
  color: #000;
}
/* 六大扶持 */
.support-bg {
  width: 100%;
  height: 261px;
  background: url("../assets/bg2.png") no-repeat;
  background-size: 100% 100%;
}
.support-title {
  display: flex;
  justify-content: center;
  margin-top: -222px;
}
.support-title img {
  width: 505px;
  height: 94px;
}
.support-box {
  width: 505px;
  display: flex;
  justify-content: center;
  flex-direction: row;
  margin: auto;
}
.support-ul {
  display: flex;
  flex: 1;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.support-list {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.support-list img {
  width: 185px;
  height: 185px;
  margin-bottom: 10px;
  margin-top: 40px;
}
.support-text {
  width: 267px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #000;
  background: #eeeeee;
}
/* 加盟 */
.join {
  width: 100%;
  height: 279px;
  margin-top: 36px;
}
.join img {
  width: 100%;
  height: 100%;
}
/* 树状 */
.shu {
  margin-top: 52px;
  width: 100%;
  height: 361px;
}
.shu img {
  width: 100%;
  height: 100%;
}
/* 流式布局图片 */
.flex-img {
  width: 99%;
  margin: auto;
  justify-content: center;
  display: flex;
  flex-wrap: wrap;
}
.flex-img img {
  margin-right: 5px;
}
.img1 {
  width: 263px;
  height: 186px;
}
.img2 {
  width: 277px;
  height: 186px;
}
.img3 {
  width: 144px;
  height: 216px;
}
.img7 {
  width: 179px;
  height: 301px;
  margin-top: -10px;
}
.img4 {
  width: 183px;
  height: 122px;
  margin-top: -10px;
}
.img5 {
  width: 171px;
  height: 122px;
  margin-top: -10px;
}
.img6 {
  width: 146px;
  height: 97px;
  margin-top: 10px;
}
.img8 {
  width: 243px;
  height: 156px;
  margin-left: 180px;
  margin-top: -160px;
}
.img9 {
  width: 256px;
  height: 156px;
  margin-top: -160px;
}
/* 荣誉资质 */
.zizhi {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  margin-top: 47px;
}

.zizhi img {
  width: 180px;
  height: 47px;
}

.zizhi-list {
  display: flex;
  flex-direction: row;
  margin-top: 31px;
}
.zizhi-list img {
  width: 180px;
  height: 140px;
  margin-left: 20px;
}
.zizhi3 {
  margin-left: 0;
}
/* 底部 */
.footer {
  margin-top: 40px;
  width: 100%;
  height: 320px;
  background: url("../assets/footer.png") no-repeat;
  background-size: 100% 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footer input {
  width: 380px;
  height: 45px;
  line-height: 45px;
  border-radius: 20px;
  border: none;
  margin-top: 45px;
  padding-left: 20px;
}
input::-webkit-input-placeholder {
  color: #000;
  font-size: 18px;
  font-weight: bold;
}

.footer button {
  margin-top: 30px;
  width: 156px;
  height: 44px;
  border-radius: 22px;
  background-color: #e60012;
  color: #fff;
  font-size: 18px;
  border: none;
}

.footer-text {
  color: #209a9a;
  margin-top: 35px;
  font-size: 17px;
}

.footer-text span:first-child {
  margin-right: 30px;
}
.swiper {
  top: 2.6rem;
}
.swiper .swiper-slide {
  height: 294px;
}
.swiper img {
  height: 294px;
}
.swiper-slide-next {
  transform: scale(0.9);
  z-index: -1;
}
.swiper-slide-prev {
  transform: scale(0.9);
  z-index: -1;
}

.swiper-container {
  --swiper-theme-color: #ff6600; /* 设置Swiper风格 */
  --swiper-navigation-color: #00ff33; /* 单独设置按钮颜色 */
  --swiper-navigation-size: 30px; /* 设置按钮大小 */
}
</style>

<template>
   <div>
       <!-- 头部 -->
       <div class="header">
            <!-- logo -->
            <img class="logo" src="../assets/logo.png" alt="">
            <div class="phone">
                <img src="../assets/phone.png" alt="">
                <div class="phone_text">
                    <p>咨询热线</p>
                    <span>0571-87175961</span>
                </div>
            </div>
        </div>
        <!-- 内容 -->
        <div class="conter">
            <img src="../assets/banner.png" alt="">
        </div>

        <!-- 品牌logo介绍 -->
        <div class="logo-duce">
            <div class="logo-box">
                <img src="../assets/dianpu1.png" alt="">
                <div class="logo-text">
                    <h3>强品牌</h3>
                    <p>10000+家店</p>
                </div>
            </div>
            <div class="logo-box">
                <img src="../assets/dianpu1.png" alt="">
                <div class="logo-text">
                    <h3>强品牌</h3>
                    <p>10000+家店</p>
                </div>
            </div>
            <div class="logo-box">
                <img src="../assets/dianpu1.png" alt="">
                <div class="logo-text">
                    <h3>强品牌</h3>
                    <p>10000+家店</p>
                </div>
            </div>
            <div class="logo-box">
                <img src="../assets/dianpu1.png" alt="">
                <div class="logo-text">
                    <h3>强品牌</h3>
                    <p>10000+家店</p>
                </div>
            </div>
        </div>

        <!-- 产品介绍 -->
        <div class="product">
                <div class="product-title">
                    <div class="title">
                        <h2>圣韩熙美白祛斑</br>重塑美业新生态</h2>
                        <h3>New ecology >></h3>
                    </div>
                    <p>聚美时光打造的是一个完善的美容院线生态系统。公司旗下分别有一个美容祛斑技术研发中心：杭州聚美时光祛斑技术研究所；产品研发与生产基地：浙江聚美时光皮肤医学研究院、。一个美容技术与门店运营的培训中心：聚美时光商学院独言文化传媒有限公司。是国内专业美容院线品牌。</p>
                </div>
        </div>
        <!-- 轮播图 -->
        <div class="swiper">
    <div class="swiper-container">
    <div class="swiper-wrapper">
      <div class="swiper-slide">
        <img src="../assets/sm1.png" alt="">
      </div>
      <div class="swiper-slide">
        <img src="../assets/sm2.png" alt="">
      </div>
      <div class="swiper-slide">
        <img src="../assets/sm3.png" alt="">
      </div>
    </div>
      <!-- <div class="swiper-button-prev"></div>
    <div class="swiper-button-next"></div> -->
  </div>
        </div>
        <!-- 传统美业那些 -->
        <div class="tradition">
            <div class="bg bg1"></div>
            <div class="img-trad">
                <img src="../assets/chuantong.png" alt="">
            </div>
            <!-- 内容  -->
            <div class="trad-box">
                    <!-- 显示 -->
                    <div class="trad-li">
                        <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                         <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                         <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                         <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                    </div>
                    <div class="trad-li">
                        <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                         <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                         <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                         <div class="trad-list">
                            <img src="../assets/fuwu.png" alt="">
                            <div class="block"></div>
                            <p>成本上升</br>美容院盈利缩小</p>
                        </div>
                    </div>
            </div>
        </div>
        <!-- 渠道 -->
        <div class="channel">
            <img src="../assets/channel.png" alt="">
        </div>

        <!-- 下拉图标 -->
        <div class="drap">
            <img src="../assets/xiala.png" alt="">
        </div>

        <!-- 产品图片 -->
        <div class="prad-line">
            <div class="lin-list">
                <img src="../assets/lin2.png" alt="">
                <div class="lin-box">
                    产品见效快</br>无毒副作用</br>消费者认可
                </div>
            </div>
            <div class="lin-list">
                <div class="lin-box">
                   产品线齐全</br>技术齐全</br>一店多盈
                </div>
                <img src="../assets/lin2.png" alt="">
            </div>
            <div class="lin-list">
                <img src="../assets/lin2.png" alt="">
                <div class="lin-box">
                    产品资质齐全</br>培训证书资质齐全
                </div>
            </div>
             <div class="lin-list">
                <div class="lin-box">
                    后期持续更新技术</br>保持市场领先
                </div>
                <img src="../assets/lin2.png" alt="">
            </div>
        </div>

        <!-- 八大优势  -->
        <div class="advantage">
            <img src="../assets/bada.png" alt="">
        </div>
         <div class="prad-line">
            <div class="lin-list">
                <div class="lin-box block">
                    产品见效快</br>无毒副作用</br>消费者认可
                </div>
                <img src="../assets/lin2.png" alt="">
                
            </div>
            <div class="lin-list">
                
                <img src="../assets/lin2.png" alt="">
                <div class="lin-box block">
                   产品线齐全</br>技术齐全</br>一店多盈
                </div>
            </div>
          
             <div class="lin-list">
                <div class="lin-box block">
                    后期持续更新技术</br>保持市场领先
                </div>
                <img src="../assets/lin2.png" alt="">
            </div>
              <div class="lin-list">
                <img src="../assets/lin2.png" alt="">
                <div class="lin-box block">
                    产品资质齐全</br>培训证书资质齐全
                </div>
            </div>
        </div>
           <!-- 下拉图标 -->
        <div class="drap">
            <img src="../assets/xiala.png" alt="">
        </div>

        <!-- 六大扶持 -->
        <div class="support">
            <div class="support-bg"></div>
            <div class="support-title">
                <img src="../assets/liuda.png" alt="">
            </div>
            <!-- 盒子 -->
            <div class="support-box">
                <div class="support-ul">
                    <div class="support-list">
                        <img src="../assets/yuan.png" alt="">
                       <div class="support-text">
                           不会开店？</br> 强大的开店运营团队，</br> 从选址到装修，开业全程扶持
                       </div>
                    </div>
                    <div class="support-list">
                        <img src="../assets/yuan.png" alt="">
                       <div class="support-text">
                           不会开店？</br> 强大的开店运营团队，</br> 从选址到装修，开业全程扶持
                       </div>
                    </div>
                    <div class="support-list">
                        <img src="../assets/yuan.png" alt="">
                       <div class="support-text">
                           不会开店？</br> 强大的开店运营团队，</br> 从选址到装修，开业全程扶持
                       </div>
                    </div>
                    </div>
                    <div class="support-ul">
                    <div class="support-list">
                        <img src="../assets/yuan.png" alt="">
                       <div class="support-text">
                           不会开店？</br> 强大的开店运营团队，</br> 从选址到装修，开业全程扶持
                       </div>
                    </div>
                    <div class="support-list">
                        <img src="../assets/yuan.png" alt="">
                       <div class="support-text">
                           不会开店？</br> 强大的开店运营团队，</br> 从选址到装修，开业全程扶持
                       </div>
                    </div>
                    <div class="support-list">
                        <img src="../assets/yuan.png" alt="">
                       <div class="support-text">
                           不会开店？</br> 强大的开店运营团队，</br> 从选址到装修，开业全程扶持
                       </div>
                    </div>
                    </div>
                    
            </div>
        </div>
        <!-- 加盟 -->
        <div class="join">
            <img src="../assets/jiameng.png" alt="">
        </div>
        <!-- 树状 -->
         <div class="shu">
            <img src="../assets/shu.png" alt="">
        </div>
        <!-- 流失布局图片 -->
        <div class="flex-img">
            <img src="../assets/dian1.jpg" alt="" class="img1">
            <img src="../assets/dian1.jpg" alt="" class="img2">
            <img src="../assets/dian1.jpg" alt="" class="img3">
             <img src="../assets/dian1.jpg" alt="" class="img7">
            <img src="../assets/dian1.jpg" alt="" class="img4">
            <img src="../assets/dian1.jpg" alt="" class="img5">
            <img src="../assets/dian1.jpg" alt="" class="img6">
           
            <img src="../assets/dian1.jpg" alt="" class="img8">
            <img src="../assets/dian1.jpg" alt="" class="img9">
        </div>
        <!-- 荣誉资质 -->
        <div class="zizhi">
            <img src="../assets/zizhi.png" alt="">
            <div class="zizhi-list">
              <img src="../assets/zizhi1.jpg" alt="">
              <img src="../assets/zizhi1.jpg" alt="">
              <img src="../assets/zizhi1.jpg" class="zizhi3" alt="">
            </div>
        </div>
        <!-- 底部 -->
        <div class="footer">
            <input type="text" placeholder="电话">
            <input type="text" placeholder="留言">
            <button>在线咨询</button>
            <div class="footer-text">
              <span>联系我们 CONTANCT US </span>         <span>投资热线：400-3338-5376</span>
            </div>
        </div>
  </div>
</template>

<script>
import { Loading } from "vant";
import Swiper from "swiper";
import "swiper/swiper-bundle.css";
const c_swiper = document.getElementsByClassName("swiper-container");
export default {
  components: {
    [Loading.name]: Loading,
  },
  mounted() {
    new Swiper(".swiper-container", {
      slidesPerView: 3,
      centeredSlides: true,
      centeredSlidesBounds: true,
      loop: true,
      loopAdditionalSlides: 3,
      navigation: {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev",
      },
      coverflow: {
        rotate: 0,
        stretch: 0,
        depth: 160,
        modifier: 1,
        slideShadows: false,
      },
    });
  },
};
</script>