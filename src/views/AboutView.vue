<template>
  <div class="aboutPage">
    <base-hero class="baseHero" :imgUrl="imgUrl">
      <template #head>about us</template>
      <template #nav>about us</template>
    </base-hero>
    <div class="aboutAgency topPaddingO">
      <div class="container">
        <div class="content row">
          <div class="col-lg-7 col-12 spec-col">
            <div class="info">
              <div class="homeheadsec">about our agency</div>
              <div class="mainTitle">
                About YammTech – <br />
                Your Partner in Digital Success
              </div>
              <p class="mainP">
                We're YammTech — a passionate software development and digital
                marketing agency helping companies of all sizes win online.
                Whether you need standout UI/UX design, a high-converting
                website, a next-level mobile app, smarter SEO, fintech tools,
                AI-powered videos, or lifelike 3D interior renderings, we've got
                you covered. Every business is different, so we listen first —
                then deliver tailored digital solutions that boost efficiency,
                visibility, and revenue. Creativity + modern tech + real data =
                results you can measure.
              </p>
            </div>
          </div>
          <div class="col-lg-5 col-12">
            <div class="img-container">
              <img
                loading="lazy"
                src="../../imgs/aboutAssets/about_img_1.webp"
                alt="client"
              />
            </div>
          </div>
          <div class="col-lg-7 col-12">
            <div class="img-container">
              <img
                loading="lazy"
                src="../../imgs/aboutAssets/about_img_2.webp"
                alt="client"
              />
            </div>
          </div>
          <div class="col-lg-5 col-12">
            <div class="img-container">
              <img
                loading="lazy"
                src="../../imgs/aboutAssets/about_img_3.webp"
                alt="client"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="whyChooseUs">
      <div class="container">
        <div class="content row">
          <div class="col-xl-5 col-lg-6 col-12">
            <div class="imgcontent">
              <div class="img-container">
                <img
                  loading="lazy"
                  src="../../imgs/aboutAssets/about_img_4.webp"
                  alt="client"
                />
              </div>
            </div>
          </div>
          <div class="col-xl-5 col-lg-6 offset-xl-1 offset-0 col-12">
            <div class="homeheadsec">Our Vision & Mission</div>
            <div class="mainTitle">
              Innovation, Dependability, and Business Growth
            </div>
            <p>
              <strong>Our Vision:</strong> To be the go-to global technology
              partner known for innovation, dependability, and consistent
              business growth.
            </p>
            <p class="mainP">
              <strong>Our Mission:</strong> Deliver secure, scalable,
              high-performance digital products and strategies that help
              companies compete — and win — in today's fast-moving world.
            </p>
          </div>
        </div>
      </div>
    </div>
    <base-meeting :btn="true">
      <template #default>
        Let's discuss make <br />
        something cool together
      </template>
    </base-meeting>
  </div>
</template>

<script>
export default {
  data() {
    return {
      imgUrl: require("../../imgs/aboutAssets/about_hero_bg.webp"),
    };
  },
  methods: {
    gsapAnimation() {
      const mm1 = this.$gsap.matchMedia();

      mm1.add(
        {
          mobile: "(max-width: 575px)",
          desktop: "(min-width: 768px)",
        },
        (context) => {
          let { mobile } = context.conditions;

          const tl1 = this.$gsap.timeline({
            scrollTrigger: {
              trigger: ".whyChooseUs .imgcontent",
              start: "bottom bottom",
              end: "bottom center",
              scrub: false,
              markers: false,
              ease: "power4.inOut",
              toggleActions: "play none none reverse",
            },
          });

          tl1.from(
            ".whyChooseUs .imgcontent img",
            {
              bottom: mobile ? -30 : -60,
              right: mobile ? -30 : -60,
              duration: 0.6,
            },
            0
          );
        }
      );
    },
    doneLoading() {
      const content = document.querySelector(".baseHero");
      const imgload = this.$imagesLoaded(content);

      imgload.on("done", () => {
        this.$store.dispatch("doneLoading", true);
        this.$nextTick(() => {
          this.$ScrollTrigger.refresh();
        });
      });
    },
  },
  mounted() {
    this.gsapAnimation();
    this.doneLoading();
  },
  beforeRouteUpdate() {
    this.gsapAnimation();
  },
};
</script>

<style lang="scss" scoped>
.aboutPage {
  .aboutAgency {
    .content {
      @media (min-width: 1199px) {
        .spec-col {
          .info {
            width: 70% !important;
          }
        }
      }
      @media (max-width: 991px) {
        .spec-col {
          margin-bottom: 40px !important;
        }
      }
      .spec-col {
        margin-bottom: 25px;
        .mainTitle {
          margin-bottom: 30px !important;
        }
      }
      .img-container {
        margin-bottom: 25px;
        img {
          max-width: 100%;
          width: 100%;
          border-radius: 18px;
        }
      }
    }
  }
  @media (max-width: 991px) {
    .whyChooseUs {
      margin-top: 80px !important;
    }
  }
  .whyChooseUs {
    margin-top: 150px;
    @media (max-width: 991px) {
      .img-container {
        margin-bottom: 40px !important;
      }
    }
    @media (max-width: 575px) {
      .imgcontent {
        padding: 0 30px 30px 0 !important;
        .img-container {
          &::after {
            --afterPositionRight: -30px !important;
            --afterPositionBottom: -30px !important;
          }
        }
      }
    }
    .imgcontent {
      padding: 0 60px 60px 0;
      .img-container {
        position: relative;
        overflow: initial;
        --afterPositionBottom: -60px;
        --afterPositionRight: -60px;
        &::after {
          content: "";
          position: absolute;
          bottom: var(--afterPositionBottom);
          right: var(--afterPositionRight);
          width: 100%;
          height: 100%;
          background-color: var(--prim-color);
          border-radius: 15px;
          z-index: 1;
        }
        img {
          position: relative;
          max-width: 100%;
          width: 100%;
          border-radius: 15px;
          z-index: 2;
        }
      }
    }
    p:first-of-type {
      display: block;
      margin-bottom: 15px;
      color: #6b7280;
      font-size: 17px;
    }
  }
}
</style>
