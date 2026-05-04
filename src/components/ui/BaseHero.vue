<template>
  <div class="heroSec">
    <div class="content">
      <div class="container">
        <div class="head">
          <slot name="head"></slot>
        </div>
        <div class="nav">
          <router-link to="/">HOME</router-link>
          <span>
            <slot name="nav"></slot>
          </span>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ["imgUrl"],
};
</script>

<style lang="scss" scoped>
.heroSec {
  @media (max-width: 1380px) {
    .content {
      height: 550px !important;
    }
  }
  @media (max-width: 1199px) {
    .content {
      height: 450px !important;
    }
  }
  @media (max-width: 991px) {
    .content {
      height: 400px !important;
      padding: 100px 0 50px !important;
    }
  }
  .content {
    position: relative;
    background: radial-gradient(
        ellipse 80% 70% at 15% 60%,
        rgba(59, 130, 246, 0.35) 0%,
        transparent 60%
      ),
      radial-gradient(
        ellipse 55% 50% at 80% 15%,
        rgba(99, 102, 241, 0.2) 0%,
        transparent 55%
      ),
      linear-gradient(
        145deg,
        #0a1628 0%,
        #0f2460 30%,
        #1d4ed8 65%,
        #1e3a8a 100%
      );
    width: 100%;
    height: 650px;
    padding: 120px 0 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    &::after {
      content: "";
      position: absolute;
      bottom: -60px;
      left: 50%;
      transform: translateX(-50%);
      width: 70%;
      height: 120px;
      background: rgba(29, 78, 216, 0.15);
      filter: blur(60px);
      border-radius: 50%;
    }
    .head {
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      font-size: 42px;
      font-weight: 700;
      margin-bottom: 18px;
      text-transform: capitalize;
      color: white;
    }
    .nav {
      display: flex;
      align-items: center;
      justify-content: center;
      text-transform: uppercase;
      a,
      span {
        text-decoration: none;
        font-size: 17px;
        font-weight: 500;
      }
      a {
        color: rgba(255, 255, 255, 0.6);
        padding-right: 14px;
        position: relative;
        transition-duration: 0.3s;
        &::after {
          content: "";
          position: absolute;
          top: 50%;
          transform: translateY(-50%);
          right: 0;
          height: 70%;
          width: 2px;
          background-color: rgba(255, 255, 255, 0.4);
        }
        @media (min-width: 992px) {
          &:hover {
            color: #f4b400;
          }
        }
      }
      span {
        display: block;
        padding-left: 14px;
        color: white;
      }
    }
  }
}
</style>
