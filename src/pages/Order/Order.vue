<template>
  <div class="order">
    <header class="header">
      <a class="header_title">
        <span class="header_title_text">订单列表</span>
      </a>
    </header>
    <section class="order_no_login">
      <img class="img_person" src="./person.png" alt="">
      <h3>登录后查看外卖订单</h3>
      <button>立即登录</button>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .order
    width: 100%
    height 100%
    background-color: #F5F5F5;
  .header
    background-color: #02a774;
    position: fixed;
    z-index: 100;
    left: 0;
    top: 0;
    width: 100%;
    height: 45px;
    line-height 45px
  .header_title
    text-align center
    display block
  .header_title_text
    color white
    font-size 22px
  .order_no_login
    width: 59%
    margin auto
    text-align center
  .img_person
    width 100%
    height 30%
    margin-top 75%
  h3
    font-size: 18px;
    margin-bottom 10px
    color #777
  button
    display: inline-block;
    background: #02a774;
    font-size: 14px;
    color: #fff;
    border: 0;
    outline: none;
    border-radius: 5px;
    padding: 10px 20px;

</style>
