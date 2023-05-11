<template>
  <div id="data-view">
    <dv-full-screen-container>
      <div class="main-header">
        <div class="time">时间：2023年5月11日 14:12：52</div>
        <div class="heading">兔比兔名片数据管理后台</div>
      </div>
      <div class="content-view">
        <div class="leftSide">
          <div class="active-user">
            <div class="title">活跃用户</div>
          </div>
          <div class="user-count">
            <div class="title">用户数量及行业</div>
          </div>
        </div>
        <div class="mid">
          <div class="roll">
            <div class="title">生产力促进协会入住兔比兔平台</div>
          </div>
          <div class="transport-volume">
            <div class="title">累计发送量</div>
          </div>
          <div class="card-transport">
            <div class="title">名片发送量&交易额</div>
          </div>
        </div>
        <div class="rightSide">
          <div class="celebrity-number">
            <div class="title">名人数量</div>
          </div>
        </div>
      </div>
    </dv-full-screen-container>
  </div>
</template>

<script>


export default {
  name: 'HomeView',
  components: {
    // HelloWorld
  },
  data() {
    return {}
  },
}
</script>


<style lang="less">
#data-view {
  width: 100%;
  height: 100%;
  background-color: #030409;
  color: #fff;
  #dv-full-screen-container {
    display: flex;
    flex-direction: column;
    background: url(https://pic.rainmakerclub.cn/face41c649a54d02951085b8fbadf9a2.png)
      no-repeat;
    background-size: 100% 100%;
  }
  .main-header {
    width: calc(100% - 40px);
    border: 1px solid red;
    height: 91px;
    background: url("https://pic.rainmakerclub.cn/5b92befa99e445988870c87e5287559a.png")
      no-repeat;
    background-size: 100% 100%;
    margin: 33px auto 35px auto;
    .time {
      padding: 14px 0 0 160px;
      box-sizing: border-box;
    }
    .heading {
      display: flex;
      justify-content: center;
      font-size: 48px;
      line-height: 15px;
      font-family: Source Han Sans CN;
      font-weight: bold;
      color: #0febff;
      box-sizing: border-box;
    }
  }
  .content-view {
    width: calc(100% - 40px);
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    .leftSide {
      width: 33%;
      border: 1px solid red;
      .active-user {
        background: url("https://pic.rainmakerclub.cn/3432020565424f40ac1126e0fe9a7647.png")
          no-repeat;
        background-size: 100% 100%;
        width: 100%;
        height: 404px;
        .title {
          font-size: 24px;
          font-family: Source Han Sans CN;
          font-weight: 400;
          color: #a7dbff;
          text-align: center;
        }
      }
      .user-count {
        background: url("https://pic.rainmakerclub.cn/3432020565424f40ac1126e0fe9a7647.png")
          no-repeat;
        background-size: 100% 100%;
        width: 100%;
        height: 404px;
        .title {
          font-size: 24px;
          font-family: Source Han Sans CN;
          font-weight: 400;
          color: #a7dbff;
          text-align: center;
        }
      }
    }
    .mid {
      width: 33%;
      border: 1px solid green;
      .roll {
        width: 100%;
        height: 60px;
        border: 1px solid skyblue;
      }
      .transport-volume {
        width: 100%;
        height: 454px;
        background: url("https://pic.rainmakerclub.cn/3432020565424f40ac1126e0fe9a7647.png")
          no-repeat;
        background-size: 100% 100%;
        .title {
          font-size: 24px;
          font-family: Source Han Sans CN;
          font-weight: 400;
          color: #a7dbff;
          text-align: center;
        }
      }
      .card-transport {
        width: 100%;
        height: 292px;
        background: url("https://pic.rainmakerclub.cn/3432020565424f40ac1126e0fe9a7647.png")
          no-repeat;
        background-size: 100% 100%;
        .title {
          font-size: 24px;
          font-family: Source Han Sans CN;
          font-weight: 400;
          color: #a7dbff;
          text-align: center;
        }
      }
    }
    .rightSide {
      width: 33%;
      border: 1px solid yellow;
      .celebrity-number {
        width: 100%;
        height: 404px;
        background: url("https://pic.rainmakerclub.cn/3432020565424f40ac1126e0fe9a7647.png")
          no-repeat;
        background-size: 100% 100%;
        .title {
          font-size: 24px;
          font-family: Source Han Sans CN;
          font-weight: 400;
          color: #a7dbff;
          text-align: center;
        }
      }
    }
  }
}
</style>