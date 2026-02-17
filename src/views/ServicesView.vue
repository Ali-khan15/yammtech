<template>
  <div class="servicesPage">
    <base-hero class="baseHero" :imgUrl="imgUrl">
      <template #head>what we do</template>
      <template #nav>what we do</template>
    </base-hero>

    <!-- CORE SERVICES - UPGRADED -->
    <div class="coreServices topPaddingO">
      <div class="container">
        <div class="content">
          <div class="head">
            <div class="homeheadsec">our expertise</div>
            <div class="mainTitle">Engineering digital excellence</div>
          </div>
          <div class="row">
            <div class="col-xl-5 col-lg-6 col-12">
              <div class="slider-container">
                <div class="imgs-container">
                  <img
                    loading="lazy"
                    data-imgNum="1"
                    class="activeClip"
                    src="../../imgs/servicesAssets/service_7.webp"
                    alt="web development"
                  />
                  <img
                    loading="lazy"
                    data-imgNum="2"
                    class=""
                    src="../../imgs/servicesAssets/service_8.webp"
                    alt="mobile development"
                  />
                  <img
                    loading="lazy"
                    data-imgNum="3"
                    class=""
                    src="../../imgs/servicesAssets/service_9.webp"
                    alt="cloud solutions"
                  />
                  <img
                    loading="lazy"
                    data-imgNum="4"
                    class=""
                    src="../../imgs/servicesAssets/service_10.webp"
                    alt="ai ml"
                  />
                </div>
              </div>
            </div>
            <div class="col-xl-7 col-lg-6 col-12">
              <ul>
                <li>
                  <div
                    data-imgNum="1"
                    @mouseenter="hoverCoreServ($event, '1')"
                    :class="['linkcont', { active: activeService === '1' }]"
                  >
                    <div class="info">
                      <div class="servname">Web Development</div>
                      <p>
                        Scalable, high-performance web applications built with
                        modern frameworks like React, Vue, and Node.js. From
                        SPAs to enterprise portals.
                      </p>
                    </div>
                    <div class="arrowIcon">
                      <font-awesome-icon
                        icon="fa-solid fa-arrow-up-right-from-square"
                      />
                    </div>
                  </div>
                </li>
                <li>
                  <div
                    data-imgNum="2"
                    @mouseenter="hoverCoreServ($event, '2')"
                    :class="['linkcont', { active: activeService === '2' }]"
                  >
                    <div class="info">
                      <div class="servname">Mobile Development</div>
                      <p>
                        Native and cross-platform mobile apps for iOS and
                        Android. Flutter, React Native, and Kotlin expertise for
                        seamless user experiences.
                      </p>
                    </div>
                    <div class="arrowIcon">
                      <font-awesome-icon
                        icon="fa-solid fa-arrow-up-right-from-square"
                      />
                    </div>
                  </div>
                </li>
                <li>
                  <div
                    data-imgNum="3"
                    @mouseenter="hoverCoreServ($event, '3')"
                    :class="['linkcont', { active: activeService === '3' }]"
                  >
                    <div class="info">
                      <div class="servname">Cloud & DevOps</div>
                      <p>
                        AWS, Azure, and Google Cloud solutions with CI/CD
                        pipelines, containerization, and infrastructure as code
                        for scalable, reliable systems.
                      </p>
                    </div>
                    <div class="arrowIcon">
                      <font-awesome-icon
                        icon="fa-solid fa-arrow-up-right-from-square"
                      />
                    </div>
                  </div>
                </li>
                <li>
                  <div
                    data-imgNum="4"
                    @mouseenter="hoverCoreServ($event, '4')"
                    :class="['linkcont', { active: activeService === '4' }]"
                  >
                    <div class="info">
                      <div class="servname">AI & Machine Learning</div>
                      <p>
                        Intelligent systems powered by LLMs, computer vision,
                        and predictive analytics. Custom AI solutions that
                        transform data into decisions.
                      </p>
                    </div>
                    <div class="arrowIcon">
                      <font-awesome-icon
                        icon="fa-solid fa-arrow-up-right-from-square"
                      />
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- TECH STACK SECTION - UPGRADED -->
    <div class="relatedServices">
      <div class="container">
        <div class="content row">
          <div class="col-xl-5 col-lg-6 col-12">
            <div class="img-container glasseffect">
              <img
                loading="lazy"
                src="../../imgs/servicesAssets/service_img_1.webp"
                alt="technology stack"
              />
            </div>
          </div>
          <div class="col-lg-6 col-12 offset-xl-1">
            <div class="info-container">
              <div class="mainTitle">Our technology ecosystem</div>
              <div class="row">
                <div class="col-md-6 col-12">
                  <ul>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">React / Next.js</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">Vue / Nuxt</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">Node.js / Python</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">AWS / Azure / GCP</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">Docker / Kubernetes</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">TensorFlow / PyTorch</div>
                      </div>
                    </li>
                  </ul>
                </div>
                <div class="col-md-6 col-12">
                  <ul>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">PostgreSQL / MongoDB</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">GraphQL / REST APIs</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">Flutter / React Native</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">Figma / Adobe XD</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">Jest / Cypress</div>
                      </div>
                    </li>
                    <li>
                      <div class="goToBtn">
                        <font-awesome-icon
                          icon="fa-solid fa-arrow-right-long"
                        />
                        <div class="hoveranim">GitHub Actions / Jenkins</div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- NEW SECTION 1: DEVELOPMENT APPROACH -->
    <div class="approachSection">
      <div class="container">
        <div class="content">
          <div class="head text-center">
            <div class="homeheadsec">our delivery framework</div>
            <div class="mainTitle">Engineering excellence, every step</div>
          </div>
          <div class="approach-timeline">
            <div class="timeline-line"></div>
            <div class="row approach-grid">
              <div class="col-lg-3 col-md-6 col-12">
                <div class="approach-card">
                  <div class="approach-icon">📋</div>
                  <h3>Discovery & Strategy</h3>
                  <p>
                    We analyze your business, users, and competitors to define
                    the perfect solution architecture and technology stack.
                  </p>
                  <div class="approach-tag">2-3 weeks</div>
                </div>
              </div>
              <div class="col-lg-3 col-md-6 col-12">
                <div class="approach-card">
                  <div class="approach-icon">🎯</div>
                  <h3>Agile Sprints</h3>
                  <p>
                    Two-week sprints with continuous delivery, daily standups,
                    and regular demos so you see progress in real-time.
                  </p>
                  <div class="approach-tag">2-6 weeks</div>
                </div>
              </div>
              <div class="col-lg-3 col-md-6 col-12">
                <div class="approach-card">
                  <div class="approach-icon">🧪</div>
                  <h3>QA & Testing</h3>
                  <p>
                    Automated testing, security audits, and performance
                    optimization before every release. Zero compromises.
                  </p>
                  <div class="approach-tag">1-2 weeks</div>
                </div>
              </div>
              <div class="col-lg-3 col-md-6 col-12">
                <div class="approach-card">
                  <div class="approach-icon">🚀</div>
                  <h3>Deployment & Beyond</h3>
                  <p>
                    Seamless deployment, 24/7 monitoring, and ongoing support to
                    ensure your success long after launch.
                  </p>
                  <div class="approach-tag">ongoing</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- NEW SECTION 2: INDUSTRY VERTICALS -->
    <div class="industriesSection">
      <div class="container">
        <div class="content">
          <div class="row align-items-center">
            <div class="col-lg-5">
              <div class="head text-start">
                <div class="homeheadsec">industries we serve</div>
                <div class="mainTitle">Domain expertise across sectors</div>
                <p class="industries-desc">
                  We combine technical excellence with deep industry knowledge
                  to deliver solutions that understand your unique challenges
                  and opportunities.
                </p>
              </div>
              <div class="industries-stats">
                <div class="stat-row">
                  <div class="stat-block">
                    <div class="stat-value">12+</div>
                    <div class="stat-label">Industries</div>
                  </div>
                  <div class="stat-block">
                    <div class="stat-value">35+</div>
                    <div class="stat-label">Domain Experts</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-7">
              <div class="industries-grid">
                <div class="industry-item">
                  <div class="industry-icon">🏦</div>
                  <span>FinTech & Banking</span>
                </div>
                <div class="industry-item">
                  <div class="industry-icon">🏥</div>
                  <span>Healthcare & MedTech</span>
                </div>
                <div class="industry-item">
                  <div class="industry-icon">🛒</div>
                  <span>E-Commerce & Retail</span>
                </div>
                <div class="industry-item">
                  <div class="industry-icon">🎓</div>
                  <span>EdTech & E-Learning</span>
                </div>
                <div class="industry-item">
                  <div class="industry-icon">🚚</div>
                  <span>Logistics & Supply Chain</span>
                </div>
                <div class="industry-item">
                  <div class="industry-icon">🏨</div>
                  <span>Travel & Hospitality</span>
                </div>
                <div class="industry-item">
                  <div class="industry-icon">📊</div>
                  <span>Real Estate & PropTech</span>
                </div>
                <div class="industry-item">
                  <div class="industry-icon">🎮</div>
                  <span>Media & Entertainment</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- CTA SECTION (from home page consistency) -->
    <base-meeting :btn="true">
      <template #default>
        Ready to build your next <br />
        software project?
      </template>
    </base-meeting>
  </div>
</template>

<script>
export default {
  data() {
    return {
      imgUrl: require("../../imgs/servicesAssets/service_hero_bg.webp"),
      activeService: 1,
    };
  },
  methods: {
    hoverCoreServ(e, imgNum) {
      this.activeService = imgNum;
      const imgs = document.querySelectorAll(
        ".slider-container .imgs-container img"
      );
      const container = document.querySelector(
        ".slider-container .imgs-container"
      );
      imgs.forEach((img) => {
        if (img.dataset.imgnum === e.target.dataset.imgnum) {
          if (container.lastChild === img) {
            return;
          }
          img.classList.add("activeClip");
          container.appendChild(img);
          setTimeout(() => {
            img.classList.remove("activeClip");
          }, 1000);
        }
      });
    },
    doneLoading() {
      const content = document.querySelector(".baseHero");
      const imgload = this.$imagesLoaded(content);
      imgload.on("done", () => {
        this.$store.dispatch("doneLoading", true);
      });
    },
  },
  mounted() {
    this.doneLoading();
  },
};
</script>

<style lang="scss" scoped>
.servicesPage {
  .coreServices {
    @media (max-width: 991px) {
      .head {
        margin-bottom: 45px !important;
      }
    }
    .head {
      text-align: center;
      margin-bottom: 90px;
      .homeheadsec {
        width: 100%;
      }
    }
    ul {
      li {
        @media (max-width: 575px) {
          .linkcont {
            flex-direction: column-reverse;
            .arrowIcon {
              margin-right: auto;
              margin-bottom: 20px;
              width: 60px !important;
              height: 60px !important;
            }
          }
        }
        &:nth-child(1) {
          .linkcont {
            padding: 0 0 25px 0;
          }
        }
        .linkcont {
          color: #fefefe;
          display: flex;
          align-items: center;
          justify-content: space-between;
          padding: 25px 0;
          border-bottom: 1px solid #4d4d4d;
          cursor: pointer;
          &.active {
            .arrowIcon {
              background-color: var(--prim-color);
              border: 2px solid var(--prim-color);
              color: white;
            }
          }
          @media (max-width: 1199px) and (min-width: 991px) {
            .info {
              max-width: 345px !important;
            }
          }
          @media (max-width: 767px) and (min-width: 575px) {
            .info {
              max-width: 400px !important;
            }
          }
          .info {
            max-width: 480px;
            margin-right: 30px;
            .servname {
              font-size: 30px;
              margin-bottom: 15px;
              font-weight: 700;
            }
            p {
              font-size: 17px;
              color: #fefefeb3;
              margin-bottom: 0;
            }
          }
          .arrowIcon {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            color: #999696;
            background-color: transparent;
            border: 2px solid #999696;
            transition-duration: 0.3s;
            svg {
              font-size: 25px;
            }
          }
        }
      }
    }
    @media (max-width: 991px) {
      .slider-container {
        margin-bottom: 50px;
      }
    }
    .slider-container {
      padding: 0px 20px 20px 0;
      @media (max-width: 991px) {
        .imgs-container {
          max-width: 100% !important;
          width: 100%;
        }
      }
      .imgs-container {
        position: relative;
        height: 600px;
        max-width: 416px;
        &::after {
          content: "";
          position: absolute;
          bottom: -20px;
          right: -20px;
          width: 100%;
          height: 100%;
          background-color: var(--prim-color);
          border-radius: 15px;
          z-index: 1;
        }
        img {
          position: absolute;
          top: 0;
          left: 0;
          height: 100%;
          max-width: 100%;
          width: 100%;
          z-index: 2;
          border-radius: 15px;
          object-fit: cover;
          transition: clip-path 1s;
          &.activeClip {
            animation: imgTransAnimation 0.7s;
          }
        }
      }
    }
  }
  @media (max-width: 991px) {
    .relatedServices {
      margin-top: 80px !important;
    }
  }
  .relatedServices {
    margin-top: 140px;
    .content {
      display: flex;
      align-items: center;
      .img-container {
        border-radius: 15px;
        position: relative;
        overflow: hidden;
        &.glasseffect {
          position: relative;
          &:hover::after {
            animation: glassEf 1.3s;
          }
          &::after {
            content: "";
            position: absolute;
            top: 0;
            left: -80%;
            width: 50%;
            height: 100%;
            background: linear-gradient(
              to right,
              transparent 0%,
              rgba(255, 255, 255, 0.15) 100%
            );
            z-index: 2;
            transform: skewX(-25deg);
            transition-duration: 0.7s;
          }
        }
        img {
          position: relative;
          z-index: 1;
          width: 100%;
          max-width: 100%;
        }
      }
      @media (max-width: 991px) {
        .info-container {
          margin-top: 40px;
        }
      }
      .info-container {
        .mainTitle {
          margin-bottom: 50px !important;
        }
        ul {
          display: flex;
          flex-wrap: wrap;
          flex-direction: column;
          @media (max-width: 991px) {
            li {
              margin-bottom: 10px !important;
            }
          }
          li {
            margin-bottom: 20px;
            width: fit-content;
            svg {
              margin: 0 15px 0 0;
              color: var(--prim-color);
              font-size: 25px;
            }
          }
        }
      }
    }
  }

  // NEW STYLES - Approach Section
  .approachSection {
    margin-top: 140px;
    position: relative;

    .head {
      margin-bottom: 60px;
    }

    .approach-timeline {
      position: relative;

      .timeline-line {
        position: absolute;
        top: 100px;
        left: 0;
        width: 100%;
        height: 2px;
        background: linear-gradient(
          90deg,
          transparent,
          var(--prim-color),
          transparent
        );
        @media (max-width: 991px) {
          display: none;
        }
      }
    }

    .approach-card {
      background: linear-gradient(267.18deg, #161616 0%, #080808 100%);
      border-radius: 15px;
      padding: 40px 30px;
      position: relative;
      margin-bottom: 30px;
      border: 1px solid rgba(255, 255, 255, 0.05);
      transition: all 0.4s ease;
      height: 100%;

      &:hover {
        transform: translateY(-10px);
        border-color: var(--prim-color);
        box-shadow: 0 20px 40px rgba(255, 74, 23, 0.15);

        .approach-icon {
          background-color: var(--prim-color);
          color: white;
        }
      }

      .approach-icon {
        width: 70px;
        height: 70px;
        border-radius: 50%;
        background-color: rgba(255, 74, 23, 0.1);
        color: var(--prim-color);
        font-size: 32px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: 25px;
        transition: all 0.4s ease;
      }

      h3 {
        color: #fefefe;
        font-size: 22px;
        font-weight: 600;
        margin-bottom: 15px;
      }

      p {
        color: #fefefeb3;
        font-size: 16px;
        line-height: 1.7;
        margin-bottom: 25px;
      }

      .approach-tag {
        display: inline-block;
        padding: 5px 15px;
        background-color: rgba(255, 74, 23, 0.15);
        color: var(--prim-color);
        border-radius: 30px;
        font-size: 14px;
        font-weight: 500;
      }
    }
  }

  // NEW STYLES - Industries Section
  .industriesSection {
    margin-top: 140px;
    margin-bottom: 140px;

    .industries-desc {
      color: #fefefeb3;
      font-size: 18px;
      line-height: 1.8;
      margin: 30px 0;
    }

    .industries-stats {
      .stat-row {
        display: flex;
        gap: 40px;

        .stat-block {
          .stat-value {
            color: var(--prim-color);
            font-size: 48px;
            font-weight: 700;
            line-height: 1.2;
          }
          .stat-label {
            color: #fefefe;
            font-size: 16px;
            opacity: 0.8;
          }
        }
      }
    }

    .industries-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 20px;

      @media (max-width: 575px) {
        grid-template-columns: 1fr;
      }

      .industry-item {
        background: linear-gradient(267.18deg, #161616 0%, #080808 100%);
        border-radius: 12px;
        padding: 25px;
        display: flex;
        align-items: center;
        gap: 15px;
        transition: all 0.3s ease;
        border: 1px solid rgba(255, 255, 255, 0.05);

        &:hover {
          transform: translateX(10px);
          border-color: var(--prim-color);
          box-shadow: 0 10px 30px rgba(255, 74, 23, 0.1);

          .industry-icon {
            transform: scale(1.1);
          }
        }

        .industry-icon {
          font-size: 32px;
          transition: transform 0.3s ease;
        }

        span {
          color: #fefefe;
          font-size: 16px;
          font-weight: 500;
        }
      }
    }
  }
}

@keyframes imgTransAnimation {
  0% {
    clip-path: polygon(100% 0, 100% 0, 100% 100%, 100% 100%);
  }
  100% {
    clip-path: polygon(100% 0, 0 0, 0 100%, 100% 100%);
  }
}

@keyframes glassEf {
  0% {
    left: -80%;
  }
  100% {
    left: 120%;
  }
}
</style>
