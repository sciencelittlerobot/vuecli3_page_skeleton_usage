<template>
  <div class="home">
    <ul class="list-wrap">
      <li class="list-item">
        <img src="../assets/images/pic_1.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
      <li class="list-item">
        <img src="../assets/images/pic_2.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
      <li class="list-item">
        <img src="../assets/images/pic_3.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
      <li class="list-item">
        <img src="../assets/images/pic_4.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
      <li class="list-item">
        <img src="../assets/images/pic_1.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
      <li class="list-item">
        <img src="../assets/images/pic_2.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
      <li class="list-item">
        <img src="../assets/images/pic_3.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
      <li class="list-item">
        <img src="../assets/images/pic_4.jpg" />
        <span>棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪棠梨煎雪</span>
      </li>
    </ul>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'home'
}
</script>

<style lang="scss" scoped>
  .clearfix:after {
    content: " ";display: block;clear: both;height: 0;
  }
  .clearfix {
    zoom: 1;
  }
  span{
    padding: 0;
    margin: 0;
  }
  ul,li{
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .home{
    width: 500px;
    height: 100%;
    overflow: hidden;
    font-size: 14px;
    margin: 0 auto;

    .list-wrap{
      width: 100%;
      margin: 0 auto;

      .list-item{
        width: 100%;
        margin-top: 15px;
        display: flex;
        align-items: center;
        word-break: break-all;
        overflow: hidden;

        img{
          width: 100px;
          height: 100px;
          margin-right: 20px;
          object-fit: cover;
        }

        span{
          padding: 0;
          margin: 0;
          width: calc(100% - 120px);
          word-break: break-all;
        }
      }
    }
}
</style>
