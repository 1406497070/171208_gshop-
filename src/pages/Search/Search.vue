<template>
  <div class="search">
    <header class="header">
      <a class="header_title">
        <span class="header_title_text">搜索</span>
      </a>
    </header>
    <form class="search_form" action="#">
      <input type="search" name="search" placeholder="请输入商家或美食名称" class="search_input">
      <input type="submit" name="submit" class="search_submit">
    </form>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .search
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
  .search_form
    width: 100%
    background-color: #fff;
    height: 41px
    position absolute
    top   50px
    padding 7px 5px
  .search_input
    width: 80%
    background-color: rgba(228, 228, 228, 0.5);
    height: 40px
    text-indent 5px
    font-size: 15px;
    font-weight: 700;
  .search_submit
    width: 15%
    height: 37px
    color white
    background-color: #02a774;
    font-weight: 700;

</style>
