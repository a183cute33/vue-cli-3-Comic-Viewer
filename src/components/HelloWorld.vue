<template>
<div>
  <nav class='navbar navbar-default'>
    <div class='container'>
      <div class='navbar-header'>
        Comicomic
      </div>
    </div>
  </nav>
  <b-container class='bv-example-row'>
    <div class='left'>
      <img src='https://hexschool.github.io/THE_F2E_Design/week5-comic%20viewer/assets/comic%20cover.png' alt=''>
    </div>
    <div class='right'>
      <div class='title'><p>MY HEXSCHOOL</p></div>
      <div class='content'>
        <div class='both'>
          <div class='b'><b>Genres</b></div>
          <span>Fusce/vehicula/dolor</span>
        </div>
        <div class='both'>
          <div class='b'><b>Author</b></div>
          <span>Namae Shiranai</span>
        </div>
        <div class='both'>
          <div class='b'><b>Status</b></div>
          <span>Ongoing</span>
        </div>
        <div class='both'>
          <div class='b'><b>Rate</b></div>
          <i class='fas fa-star'></i>
          <i class='fas fa-star'></i>
          <i class='fas fa-star'></i>
          <i class='fas fa-star'></i>
          <i class='far fa-star'></i>
        </div>
         <div class='both'>
          <div class='summary'>
            <b>Summary</b>
          </div>
          <p>If your banker breaks, you snap; if your apothecary by mistake sends you poison in your pills, you die. </p>
          <p>Therefore, I say, I saw that this situation of mine was the precise situation of every mortal that has this Siamese 
            connexion with a plurality of other mortals. </p>
         </div>
      </div>
    </div>
    <div class='center'>
      <div class='title'>
        <span>All Chapters</span>
    </div>
      <div class='main'>
        <span>Chapter 1: The F2E Challenge Start!</span>
        <span>Chapter 2: Todo List is Going Crazy! <p>NEW</p></span>
      </div>
    </div>
    <div class='ad'>
      <img src='/static/' alt=''>
    </div>
  </b-container>
</div>
</template>
<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>
<style lang='scss' scoped>
@import url('https://fonts.googleapis.com/css?family=Roboto:700i');
$_font: 'Roboto', sans-serif;

nav {
  width: 100%;
  height: 74px;
  background: #000000;
  .navbar-header {
    font-size: 36px;
    color: #50ff44;
    padding-top: 16px;
    font-weight: bold;
  }
}
.bv-example-row {
  display: inline-block;
  width: 100%;
  max-width: 620px;
  margin: 24px auto;
  .left {
    display: inline-block;
    border: 4px solid black;
    width: 303px;
    height: 438px;
    img {
      width: 100%;
      height: 100%;
    }
  }
  .right {
    display: inline-block;
    float: right;
    height: 438px;
    width: 317px;
    .title {
      display: inline-block;
      background: #000000;
      width: 100%;
      height: 52px;
      font-size: 36px;
      color: #ffffff;
      line-height: 36px;
      p {
        padding-top: 8px;
      }
    }
    .content {
      width: calc(438px - 52px);
      .both {
        margin-left: 20px;
        margin-top: 16px;
        text-align: left;
        .b,
        .summary {
          display: inline-block;
          width: 72px;
        }
        b {
          font-size: 16px;
          color: #000000;
          line-height: 24px;
        }
        span {
          font-size: 16px;
          color: #000000;
          line-height: 24px;
        }
        .summary {
          margin-top: 24px;
          font-weight: bold;
        }
        p {
          width: 300px;
          font-size: 16px;
          color: #000000;
          line-height: 24px;
        }
      }
    }
  }
  .center {
    display: inline-block;
    width: 100%;
    margin-top: 24px;
    .title {
      width: 181px;
      height: 44px;
      background: #000000;
      span {
        color: #ffffff;
        font-size: 24px;
        line-height: 44px;
      }
    }
    .main {
      width: 620px;
      height: 106px;
      background: #ffffff;
      border: 4px solid #000000;
      span {
        display: inline-block;
        text-align: left;
        width: 100%;
        font-size: 16px;
        color: #000000;
        line-height: 24px;
        margin-top: 15px;
        margin-left: 24px;
        &:first-child {
          margin-top: 22px;
        }
        p {
          display: inline-block;
          background: #50ff44;
          font-size: 14px;
          color: #000000;
          line-height: 14px;
          padding: 2px 12px;
          margin-left: 16px;
        }
      }
    }
  }
  .ad{

  }
}
</style>
