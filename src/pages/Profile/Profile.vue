<template>
  <div class="profile">
    <header class="profile_header">
      <a class="profile_header_title">
        <span class="header_title_text">我的</span>
      </a>
    </header>
    <section class="profile-number">
      <router-link to="/login" class="profile-link">
      <div class="profile_image">
          <i class="iconfont icon-person"></i>
        </div>
        <div class="user-info">
          <p class="user-info-top">登录/注册</p>
          <p>
                <span class="user-icon biguser-icon">
                  <i class="iconfont icon-shouji icon-mobile"></i>
                </span>
            <span class="icon-mobile-number biguser-icon">暂无绑定手机号</span>
          </p>
        </div>
        <span class="arrow">
              <i class="iconfont icon-jiantou1"></i>
            </span>
      </router-link>
    </section>
    <section class="profile_info_data border-1px">
      <ul class="info_data_list">
        <a href="javascript:" class="info_data_link">
          <span class="info_data_top"><span class="money">0.00</span><em>元</em></span>
          <span class="info_data_bottom">我的余额</span>
        </a>
        <a href="javascript:" class="info_data_link">
          <span class="info_data_top"><span class="money">0</span><em>个</em></span>
          <span class="info_data_bottom">我的优惠</span>
        </a>
        <a href="javascript:" class="info_data_link">
          <span class="info_data_top"><span class="money">0</span><em>分</em></span>
          <span class="info_data_bottom">我的积分</span>
        </a>
      </ul>
    </section>
    <section class="profile_my_order border-1px">
      <!-- 我的订单 -->
      <a href='javascript:' class="my_order">
            <span>
              <i class="iconfont icon-order-s"></i>
            </span>
        <div class="my_order_div">
          <span class="myprofile">我的订单</span>
          <span class="my_order_icon">
                <i class="iconfont icon-jiantou1"></i>
              </span>
        </div>
      </a>
      <!-- 积分商城 -->
      <a href='javascript:' class="my_order">
            <span>
              <i class="iconfont icon-jifen"></i>
            </span>
        <div class="my_order_div">
          <span class="myprofile">积分商城</span>
          <span class="my_order_icon">
                <i class="iconfont icon-jiantou1"></i>
              </span>
        </div>
      </a>
      <!-- 硅谷外卖会员卡 -->
      <a href="javascript:" class="my_order">
            <span>
              <i class="iconfont icon-vip"></i>
            </span>
        <div class="my_order_div">
          <span class="myprofile">硅谷外卖会员卡</span>
          <span class="my_order_icon">
                <i class="iconfont icon-jiantou1"></i>
              </span>
        </div>
      </a>
    </section>
    <section class="profile_my_order border-1px">
      <!-- 服务中心 -->
      <a href="javascript:" class="my_order">
            <span>
              <i class="iconfont icon-fuwu"></i>
            </span>
        <div class="my_order_div">
          <span class="myprofile">服务中心</span>
          <span class="my_order_icon">
                <i class="iconfont icon-jiantou1"></i>
              </span>
        </div>
      </a>
    </section>
  </div>
</template>

<script>
export default {

}
</script>

  <style lang="stylus" rel="stylesheet/stylus">
    .profile
      width: 100%
      height 100%
      background-color: #F5F5F5;
    .profile_header
      background-color: #02a774;
      border-bottom: 1px solid #fff;
      text-align center
    .profile_header_title
      width: 100%;
      height: 45px;
      line-height 45px

    .header_title_text
      color white
      font-size 22px
    .profile-number
      width: 100%
      background-color: #02a774;
      padding 15px  5px 0
    .profile-link
      display block
      width: 320px
      height: 100px
    .profile_image
      float: left;
      width 62px
      height 62px
      border-radius 50%
      overflow hidden
      margin 10px 5px 0
    .icon-person
      width 62px
      height  62px
      border-radius 50%
    .profile_image .iconfont::before
      width 62px
      height  62px
      font-size: 62px;
      background #e4e4e4
      border-radius 50%
    .user-info
      float left
      margin-top 8px
      margin-left 15px
    p
      font-weight: 700
      font-size 18px
      color #fff
    p.user-info-top
      margin-top 10px
      padding-bottom 8px
    .biguser-icon
      display inline
    p>span.user-icon
      margin-left -15px
      width 20px
      height 20px
    .icon-mobile
      vertical-align text-top
    .icon-mobile::before
      vertical-align middle
      font-size 30px
      color white

    p>span.icon-mobile-number
      font-size 14px
      color #fff
      margin-left: -15px
    .arrow
      float right
      margin-top 30px
      margin-right 20px
    .icon-jiantou1
      color #fff
    .icon-jiantou1::before
      color #fff
      font-size 15px
    .arrow
      width 12px
      height 12px
      position absolute
      right 15px
      top 8%
    .profile_info_data
      bottom-border-1px(#e4e4e4)
      width 100%
      background #fff
      overflow hidden
    .info_data_list
      clearFix()
    .info_data_link
        float left
        width 33%
        text-align center
        border-right 1px solid #f1f1f1
    .info_data_top
          display block
          width 100%
          font-size 14px
          color #333
          padding 15px 5px 10px
    .info_data_top>span
            display inline-block
            font-size 30px
            color #f90
            font-weight 700
            line-height 30px
      em
        font-style: normal;
    .info_data_bottom
          display inline-block
          font-size 14px
          color #666
          font-weight 400
          padding-bottom 10px

    .info_data_top span
            color #ff5f3e
    .span.money
        display inline
    .info_data_link:nth-of-type(3)
        border 0


    .profile_my_order
      top-border-1px(#e4e4e4)
      margin-top 10px
      background #fff
    .my_order
        display flex
        align-items center
        padding-left 15px
    .my_order>span
          display flex
          align-items center
          font-size 20px
          width 20px
          height 20px
          margin-right 8px
    span.myprofile
          text-align left
    .icon-order-s::before
            font-size 30px

    .icon-order-s
            color #02a774
    .icon-jifen
            color #ff5f3e
    .icon-vip
            color #f90
    .icon-fuwu
            color #02a774
    .my_order_div
          width 100%
          border-bottom 1px solid #f1f1f1
          padding 18px 10px 18px 0
          font-size 16px
          color #333
          display flex
          justify-content space-between
    .my_order_div>span
            display block
            font-size 18px
    .my_order_icon
            width 10px
            height 10px
    .my_order_icon>.icon-jiantou1
              color #bbb
              font-size 10px
    .my_order_icon>.icon-jiantou1::before
              color #bbb
              font-size 10px
</style>
