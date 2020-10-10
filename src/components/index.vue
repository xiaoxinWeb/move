<style>
    .header {
        width:100%;
        height:99px;
        background-color:#216767;
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
        color: #F2D397;
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
    .conter{
        width:100%;
        height:613px;
    }
    .conter img {
        width: 100%;
        height:100%;
    }

    /* logo 介绍 */
    .logo-duce {
        display: flex;
        flex-direction: row;
        padding: 20px 0;
        background:url('../assets/bg.png') no-repeat;
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
    .logo-text  {
        color: #216B6C;
        text-align: center;
    }
    .logo-text h3{
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

    .product-title::after{
        content: "";
        position: absolute;
        width: 5px;
        height: 100%;
        top: 0px;
        left: 0;
        background-color: #206969;
    }
    .product-title::before{
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
        color: #EFD095;
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
    .tradition{
        margin-top: 51px;
        background-color: #eee;
        padding-bottom: 53px;
    }
    .bg {
        width: 100%;
        height: 296px;
    }
    .bg1 {
        background: url('../assets/bg1.png') no-repeat;
        background-size: 100% 100%;
    }
    .img-trad {
        width:100%;
        height: 92.7px;
        display: flex;
        justify-content: center;
        margin-top: -251px;
    }
    .img-trad  img {
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
        border: 2px solid #1F9999;
        margin: 20px;
        margin-top: 30px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .trad-list img{
        width: 64px;
        height: 64px;
        margin: 10px 0;
    }
    .trad-list .block {
        width: 60px;
        height: 3px;
        border-top:4px solid  #000;
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

    .lin-list{
        width: 170px;
    }
    .lin-list img {
        width: 100%;
        height: 205px;
    }
    .lin-box {
        width: 100%;
        height: 142px;
        background-color: #33AAAA;
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
        background: url('../assets/bg2.png') no-repeat;
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
        background: #EEEEEE;
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
  </div>
</template>

<script>
import { Loading } from 'vant'
export default {
  components: {
    [Loading.name]: Loading
  },
  methods:{

  }
}
</script>