<template>
  <div class="contactPage">
    <base-hero class="baseHero" :imgUrl="imgUrl">
      <template #head>contact us</template>
      <template #nav>contact</template>
    </base-hero>
    <div class="content topPaddingO">
      <div class="container">
        <div class="row">
          <div class="col-lg-6">
            <div class="head">
              <div class="homeheadsec">Getting Touch</div>
              <div class="mainTitle">
                Ready to Start? <br />
                Let's Talk About Your Project
              </div>
            </div>
            <div class="info">
              <ul>
                <li>
                  <font-awesome-icon icon="fa-solid fa-phone" />
                  +1 (437) 559-1485
                </li>
                <li>
                  <font-awesome-icon icon="fa-solid fa-envelope" />
                  info@yammtech.com
                </li>
                <li class="add">
                  <font-awesome-icon icon="fa-solid fa-location-dot" />
                  <p>Toronto, Canada</p>
                </li>
              </ul>
              <div class="contact-note" style="margin-top: 30px">
                <p style="color: #6b7280; font-size: 16px; line-height: 1.6">
                  Whether you're looking for a reliable software development
                  company, UI/UX design agency, mobile app development services,
                  expert SEO, or something else entirely we're excited to hear
                  your vision.
                </p>
                <p
                  style="
                    color: #6b7280;
                    font-size: 16px;
                    line-height: 1.6;
                    margin-top: 15px;
                  "
                >
                  Drop us a message for a no-pressure, free consultation. We
                  usually reply within 1 hour.
                </p>
                <p
                  style="
                    color: var(--prim-color);
                    font-size: 16px;
                    margin-top: 20px;
                    font-weight: 500;
                  "
                >
                  Looking forward to building something amazing together!
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <form action="#">
              <div class="row">
                <div class="col-sm-6">
                  <div class="mainInput">
                    <label for="name">Full Name*</label>
                    <input id="name" type="text" />
                  </div>
                </div>
                <div class="col-sm-6">
                  <div class="mainInput">
                    <label for="email">Email*</label>
                    <input id="email" type="email" />
                  </div>
                </div>
                <div class="col-sm-6">
                  <div class="mainInput">
                    <label for="ProjectType">Project Type*</label>
                    <input id="ProjectType" type="text" />
                  </div>
                </div>
                <div class="col-sm-6">
                  <div class="mainInput">
                    <label for="Mobile">Mobile*</label>
                    <input id="Mobile" type="number" />
                  </div>
                </div>
                <div class="col-lg-12">
                  <div class="mainInput">
                    <label for="ProjectDetails">Write Project Details*</label>
                    <textarea cols="30" rows="7" id="ProjectDetails"></textarea>
                  </div>
                </div>
              </div>
            </form>
            <button class="mainBtn">send</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      imgUrl: require("../../../imgs/pages/contact/contact_hero_bg.webp"),
    };
  },
  mounted() {
    this.$nextTick(() => {
      this.$store.dispatch("doneLoading", true);
    });
  },
};
</script>

<style lang="scss" scoped>
.contactPage {
  @media (max-width: 991px) {
    .content {
      .head {
        margin-bottom: 30px !important;
      }
    }
  }
  .content {
    .head {
      margin-bottom: 55px;
    }
    .info {
      ul {
        li {
          &.add {
            display: flex;
            svg {
              margin-right: 20px;
            }
          }
          color: #4b5563;
          margin-bottom: 22px;
          font-size: 16px;
          &:last-of-type {
            margin-bottom: 0px;
          }
          svg {
            font-size: 20px;
            margin-right: 10px;
            color: var(--prim-color);
          }
        }
      }
    }
    @media (max-width: 991px) {
      form {
        margin-top: 50px;
      }
    }
  }
}
</style>
