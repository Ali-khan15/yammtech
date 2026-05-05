<template>
  <div class="homePage">
    <!-- HERO SECTION - ONLY CONTENT UPDATED -->
    <div class="hero">
      <div class="container">
        <div class="content">
          <div class="shape"></div>
          <div class="shape"></div>
          <div class="shape"></div>
          <h1 class="head">
            YammTech — Your Trusted Software Development Partner for Scalable
            Digital Solutions
          </h1>
          <div class="getaQuote">
            <div class="getaq-btn">
              <router-link to="/contact">
                <div class="cont goToBtn">
                  <span class="hoveranim">Book Your Free Consultation</span>
                  <font-awesome-icon icon="fa-solid fa-arrow-right-long" />
                </div>
              </router-link>
            </div>
            <p>
              We design, build, and scale powerful digital products — from
              websites to AI-driven systems — helping businesses grow faster and
              smarter.
            </p>
          </div>
          <div class="scrollDown"></div>
        </div>
      </div>
      <div class="follow-us">
        <span>follow us</span>
        <span>linkedin</span>
        <span>github</span>
        <span>twitter</span>
      </div>
    </div>

    <!-- ABOUT SECTION - UPDATED CONTENT -->
    <div class="ourFunFact">
      <div class="container">
        <div class="statusBorder">
          <img
            src="../../imgs/homeAssets/funfact_shape_bg.svg"
            alt="ourFunfact Svg"
          />
          <div class="status">
            <div class="info">
              <h1>Who We Are</h1>
              <p>
                YammTech is a full-service digital agency helping startups,
                growing businesses, and established brands turn ideas into
                high-performing digital products. We bring together expert
                developers, designers, SEO specialists, and marketers under one
                roof — so everything works together to drive real business
                growth. We care about performance, clean user experiences, and
                long-term success — not just shipping a project and moving on.
              </p>
            </div>
            <div class="nums row gy-3">
              <div class="num col-md-6 col-12">
                <div class="odo">
                  <span data-numm="99" class="odometer">5</span>
                  <span class="kword">+</span>
                </div>
                <div class="title">
                  <span>Global Happy Clients</span>
                </div>
              </div>
              <div class="num col-md-6 col-12">
                <div class="odo">
                  <span data-numm="300" class="odometer">50</span>
                  <span class="kword">+</span>
                </div>
                <div class="title">
                  <span>Project Completed</span>
                </div>
              </div>
              <div class="num col-md-6 col-12">
                <span data-numm="25" class="odometer">25</span>
                <span class="kword">+</span>
                <div class="title">
                  <span>Team Members</span>
                </div>
              </div>
              <div class="num col-md-6 col-12">
                <span data-numm="50" class="odometer">550</span>
                <div class="title">
                  <span>Digital products</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- CORE SERVICES SECTION - ROW 1 -->
    <div class="services" id="#services">
      <div class="container">
        <div class="content">
          <div class="row">
            <div class="col-xl-4 col-12 info">
              <span class="homeheadsec">What We Do</span>
              <p class="mainTitle">Expert Solutions for Every Business Need</p>
              <router-link aria-label="services" to="/services">
                <div class="servicesbtn goToBtn">
                  <div class="hoveranim">See All Services</div>
                  <font-awesome-icon icon="fa-solid fa-arrow-right-long" />
                </div>
              </router-link>
            </div>
            <div class="col-xl-8 col-12 row projects">
              <div class="box col-lg-3 col-sm-6 col-12 d-none d-lg-block"></div>
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_1.webp"
                    alt="UI/UX design"
                  />
                  <span class="title">UI/UX Design</span>
                </div>
              </div>
              <div class="box col-lg-3 col-sm-6 col-12 d-none d-lg-block"></div>
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_2.webp"
                    alt="Website Development"
                  />
                  <span class="title">Web Development</span>
                </div>
              </div>
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_3.webp"
                    alt="Mobile App Development"
                  />
                  <span class="title">Mobile App Development</span>
                </div>
              </div>
              <div class="box col-lg-3 col-sm-6 col-12 d-none d-lg-block"></div>
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_4.webp"
                    alt="SEO Services"
                  />
                  <span class="title">Digital Marketing & SEO</span>
                </div>
              </div>
              <div class="box col-lg-3 col-sm-6 col-12 d-none d-lg-block"></div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- CORE SERVICES SECTION - ROW 2 (Digital Marketing, Fintech, AI Video, 3D Rendering) -->
    <div class="services" style="margin-top: -80px">
      <div class="container">
        <div class="content">
          <div class="row">
            <div class="col-xl-4 col-12 info">
              <!-- Empty for alignment -->
            </div>
            <div class="col-xl-8 col-12 row projects">
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_1.webp"
                    alt="Digital Marketing"
                  />
                  <span class="title">AI & Automation Solutions</span>
                </div>
              </div>
              <div class="box col-lg-3 col-sm-6 col-12 d-none d-lg-block"></div>
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_2.webp"
                    alt="Fintech Development"
                  />
                  <span class="title">Fintech & Custom Software</span>
                </div>
              </div>
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_3.webp"
                    alt="AI Video Creation"
                  />
                  <span class="title">AI Video Creation Services</span>
                </div>
              </div>
              <div class="box col-lg-3 col-sm-6 col-12 d-none d-lg-block"></div>
              <div class="box box-tilt col-lg-3 col-sm-6 col-12">
                <div class="box-container">
                  <img
                    loading="lazy"
                    src="../../imgs/homeAssets/service_4.webp"
                    alt="3D Rendering"
                  />
                  <span class="title">Interior Design & 3D Rendering</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- HOW WE WORK SECTION -->
    <div class="howWeWork">
      <div class="container">
        <div class="section-head text-center">
          <span class="homeheadsec">Our Process</span>
          <p class="mainTitle">How We Work</p>
        </div>
        <div class="row steps justify-content-center">
          <div class="col-lg-3 col-sm-6 col-12">
            <div class="step">
              <div class="step-num">01</div>
              <h4>Consultation</h4>
              <p>
                We start with a free discovery call to understand your goals,
                challenges, and vision before anything else.
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 col-12">
            <div class="step">
              <div class="step-num">02</div>
              <h4>Planning</h4>
              <p>
                We build a detailed project roadmap — scope, timeline,
                technology stack, and design strategy — aligned to your goals.
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 col-12">
            <div class="step">
              <div class="step-num">03</div>
              <h4>Development</h4>
              <p>
                Our engineers build your product with clean, scalable code using
                modern frameworks — tested rigorously at every stage.
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 col-12">
            <div class="step">
              <div class="step-num">04</div>
              <h4>Launch</h4>
              <p>
                We deploy your product with full QA testing, performance
                optimization, and a smooth go-live process.
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 col-12">
            <div class="step">
              <div class="step-num">05</div>
              <h4>Support</h4>
              <p>
                After launch, we monitor, maintain, and continuously improve
                your product so it keeps growing with your business.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- TECHNOLOGIES SECTION -->
    <div class="techStack">
      <div class="container">
        <div class="section-head text-center">
          <span class="homeheadsec">What We Build With</span>
          <p class="mainTitle">Technologies We Use</p>
        </div>
        <div class="row tech-grid">
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-react" />
              <span>React</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-vuejs" />
              <span>Vue.js</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-node-js" />
              <span>Node.js</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-python" />
              <span>Python</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-aws" />
              <span>AWS</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-bootstrap" />
              <span>Bootstrap</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-docker" />
              <span>Docker</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-android" />
              <span>Android</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-apple" />
              <span>iOS</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-figma" />
              <span>Figma</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-github" />
              <span>GitHub</span>
            </div>
          </div>
          <div class="col-lg-2 col-md-3 col-4">
            <div class="tech-card">
              <font-awesome-icon icon="fa-brands fa-js" />
              <span>TypeScript</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- WHY CHOOSE YAMMTECH SECTION -->
    <div class="ourFunFact" style="margin-bottom: 0; margin-top: 220px">
      <div class="container">
        <div
          class="statusBorder"
          style="
            background: linear-gradient(
              135deg,
              #f4b400 0%,
              #f59e0b 50%,
              #d97706 100%
            );
          "
        >
          <img
            src="../../imgs/homeAssets/funfact_shape_bg.svg"
            alt="why choose us"
          />
          <div class="status">
            <div class="info" style="width: 100%">
              <h1 style="color: #111827">Why Choose YammTech?</h1>
              <ul
                style="list-style: none; padding: 0; margin: 0; color: #1f2937"
              >
                <li
                  style="
                    margin-bottom: 14px;
                    display: flex;
                    align-items: flex-start;
                    gap: 10px;
                  "
                >
                  <font-awesome-icon
                    icon="fa-solid fa-check-circle"
                    style="color: #111827; margin-top: 3px; flex-shrink: 0"
                  />
                  <span
                    >Seasoned developers, designers, SEO specialists, and
                    marketers under one roof</span
                  >
                </li>
                <li
                  style="
                    margin-bottom: 14px;
                    display: flex;
                    align-items: flex-start;
                    gap: 10px;
                  "
                >
                  <font-awesome-icon
                    icon="fa-solid fa-check-circle"
                    style="color: #111827; margin-top: 3px; flex-shrink: 0"
                  />
                  <span
                    >Fully custom solutions tailored to your industry and
                    goals</span
                  >
                </li>
                <li
                  style="
                    margin-bottom: 14px;
                    display: flex;
                    align-items: flex-start;
                    gap: 10px;
                  "
                >
                  <font-awesome-icon
                    icon="fa-solid fa-check-circle"
                    style="color: #111827; margin-top: 3px; flex-shrink: 0"
                  />
                  <span
                    >On-time delivery with clear communication at every
                    step</span
                  >
                </li>
                <li
                  style="
                    margin-bottom: 14px;
                    display: flex;
                    align-items: flex-start;
                    gap: 10px;
                  "
                >
                  <font-awesome-icon
                    icon="fa-solid fa-check-circle"
                    style="color: #111827; margin-top: 3px; flex-shrink: 0"
                  />
                  <span
                    >Ongoing support so your product keeps improving after
                    launch</span
                  >
                </li>
                <li style="display: flex; align-items: flex-start; gap: 10px">
                  <font-awesome-icon
                    icon="fa-solid fa-check-circle"
                    style="color: #111827; margin-top: 3px; flex-shrink: 0"
                  />
                  <span
                    >Focus on ROI — we build for growth, not just looks</span
                  >
                </li>
              </ul>
              <p style="margin-top: 30px; font-style: italic; color: #1f2937">
                We don't just create apps or websites — we build digital systems
                that help your business thrive.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- TESTIMONIALS SECTION - Keep -->
    <div class="comments">
      <img
        class="commentsSvg d-none d-lg-block"
        src="../../imgs/homeAssets/9c900a56-7712-4f59-b42e-99af2d226e5b.svg"
        alt="commentsSvg"
      />
      <div class="container">
        <div class="content">
          <div class="row">
            <div class="col-xl-4 col-lg-5 col-12 ppcol">
              <div class="swiper-container" ref="pplSwiper">
                <div class="swiper-wrapper">
                  <div class="swiper-slide">
                    <div class="img-container">
                      <img
                        loading="lazy"
                        src="../../imgs/homeAssets/testimonial_1.webp"
                        alt="client"
                      />
                    </div>
                  </div>
                  <div class="swiper-slide">
                    <div class="img-container">
                      <img
                        loading="lazy"
                        src="../../imgs/homeAssets/testimonial_2.webp"
                        alt="client"
                      />
                    </div>
                  </div>
                  <div class="swiper-slide">
                    <div class="img-container">
                      <img
                        loading="lazy"
                        src="../../imgs/homeAssets/testimonial_3.webp"
                        alt="client"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-xl-8 col-lg-7 col-12 cmmtcol">
              <div class="swiper-container" ref="commentsSwiper">
                <div class="swiper-wrapper">
                  <div class="swiper-slide">
                    <div class="commentContainer">
                      <p>
                        I wish I would have thought of it first. Creative agency
                        is the most tech valuable business resource we have ever
                        purchased. Dude your stuff is the bomb! eaque ipsa quae
                        ab illo inventore veritatis et quasi architecto beatae
                        vitae dicta sunt to the explicabo.
                      </p>
                      <div class="stars">
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon
                          icon="fa-solid fa-star"
                          class="deactive"
                        />
                      </div>
                      <div class="pplInfo">
                        <div class="name">Jasmine Rivera</div>
                        <div class="rule">Marketing Analyst</div>
                      </div>
                      <font-awesome-icon icon="fa-solid fa-quote-left" />
                    </div>
                  </div>
                  <div class="swiper-slide">
                    <div class="commentContainer">
                      <p>
                        I really wish I had come up with that idea initially.
                        Investing in creative agency has proven to be the most
                        invaluable tech resource we've ever acquired. Your work
                        is absolutely fantastic! It's like the words of praise
                        that come straight from the creator himself, unveiling
                        the truth and beauty of life.
                      </p>
                      <div class="stars">
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon
                          icon="fa-solid fa-star"
                          class="deactive"
                        />
                        <font-awesome-icon
                          icon="fa-solid fa-star"
                          class="deactive"
                        />
                      </div>
                      <div class="pplInfo">
                        <div class="name">Ethan Carter</div>
                        <div class="rule">Software Engineer</div>
                      </div>
                      <font-awesome-icon icon="fa-solid fa-quote-left" />
                    </div>
                  </div>
                  <div class="swiper-slide">
                    <div class="commentContainer">
                      <p>
                        I'm kicking myself for not thinking of that brilliant
                        idea sooner. Our investment in creative agency has
                        turned out to be the ultimate tech asset we've ever
                        secured. Your work is simply mind-blowing! It's as if
                        every word you craft unveils the secrets of existence
                        itself, spoken by the architect of life.
                      </p>
                      <div class="stars">
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                      </div>
                      <div class="pplInfo">
                        <div class="name">Olivia Bennett</div>
                        <div class="rule">Financial Planner</div>
                      </div>
                      <font-awesome-icon icon="fa-solid fa-quote-left" />
                    </div>
                  </div>
                </div>
              </div>
              <div class="myCustomNav">
                <button
                  aria-label="prevbtn"
                  class="prevbtn"
                  @click="prevSwiper('commentsSwiper')"
                >
                  <font-awesome-icon icon="fa-solid fa-arrow-left-long" />
                </button>
                <button
                  aria-label="nextbtn"
                  class="nextbtn"
                  @click="nextSwiper('commentsSwiper')"
                >
                  <font-awesome-icon icon="fa-solid fa-arrow-right-long" />
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- PARTNERS SECTION - Keep -->
    <div class="partners">
      <div class="scroller">
        <div class="scroller_inner">
          Our reputed world wide partners Our reputed world wide partners
        </div>
      </div>
      <div class="container">
        <div class="content">
          <div class="brand-logo">
            <img src="../../imgs/homeAssets/partner_1.svg" alt="partner_1" />
          </div>
          <div class="brand-logo">
            <img src="../../imgs/homeAssets/partner_2.svg" alt="partner_2" />
          </div>
          <div class="brand-logo">
            <img src="../../imgs/homeAssets/partner_3.svg" alt="partner_3" />
          </div>
          <div class="brand-logo">
            <img src="../../imgs/homeAssets/partner_4.svg" alt="partner_4" />
          </div>
          <div class="brand-logo">
            <img src="../../imgs/homeAssets/partner_5.svg" alt="partner_5" />
          </div>
        </div>
      </div>
    </div>

    <!-- CTA SECTION - Keep -->
    <base-meeting :btn="true">
      <template #default>
        Ready to Grow Your Business? <br />
        Let's build something amazing together.
      </template>
    </base-meeting>
  </div>
</template>

<script>
import odometer from "odometer";
import "odometer/themes/odometer-theme-default.css";

export default {
  data() {
    return {
      YTIframeVal: false,
      blogDataLoaded: false,
      teamDataLoaded: false,
      PortfolioDataLoaded: false,
    };
  },
  methods: {
    doneLoading() {
      const content = document.querySelector(".homePage");
      const imgload = this.$imagesLoaded(content);
      imgload.on("done", () => {
        this.$nextTick(() => {
          this.$store.dispatch("doneLoading", true);
          this.initSwipers();
        });
      });
    },
    initSwiperPort() {
      this.$nextTick(() => {
        // eslint-disable-next-line no-unused-vars
        const portSwiper = new this.$Swiper(this.$refs.portSwiper, {
          modules: [this.$Pagination],
          slidesPerView: 1,
          spaceBetween: 15,
          loop: true,
          centeredSlides: true,
          slidesPerGroup: 1,
          breakpoints: {
            1200: {
              slidesPerView: 2.2,
            },
            576: {
              slidesPerView: 1.4,
            },
          },
          pagination: {
            el: ".swiper-pagination",
            clickable: true,
          },
        });
        this.$ScrollTrigger.refresh();
      });
    },
    initSwiperTeam() {
      this.$nextTick(() => {
        // eslint-disable-next-line no-unused-vars
        const teamSwiper = new this.$Swiper(this.$refs.teamSwiper, {
          modules: [this.$Pagination],
          slidesPerView: 1,
          spaceBetween: 15,
          loop: true,
          slidesPerGroup: 1,
          grabCursor: true,
          allowTouchMove: true,
          breakpoints: {
            1200: {
              slidesPerView: 4,
              allowTouchMove: false,
              loop: false,
            },
            991: {
              slidesPerView: 3,
              loop: true,
              allowTouchMove: true,
              pagination: {
                enabled: false,
              },
            },
            767: {
              slidesPerView: 2,
              allowTouchMove: true,
              loop: true,
            },
          },
          pagination: {
            el: ".swiper-pagination",
            clickable: true,
            enabled: true,
          },
        });
        this.$ScrollTrigger.refresh();
      });
    },
    initSwipers() {
      this.$nextTick(() => {
        // comments-swiper-start
        // eslint-disable-next-line no-unused-vars
        const pplSwiper = new this.$Swiper(this.$refs.pplSwiper, {
          modules: [this.$Controller],
          slidesPerView: "auto",
          centeredSlides: true,
          grabCursor: true,
          slideToClickedSlide: true,
        });
        // eslint-disable-next-line no-unused-vars
        const commentsSwiper = new this.$Swiper(this.$refs.commentsSwiper, {
          modules: [this.$Controller],
          spaceBetween: 15,
          grabCursor: true,
        });
        commentsSwiper.controller.control = pplSwiper;
        pplSwiper.controller.control = commentsSwiper;
        this.$ScrollTrigger.refresh();
      });
    },
    gsapAnimation() {
      const scrollTriggerConfig = (trigger) => ({
        trigger,
        start: "+100 bottom",
        end: "center center",
        scrub: false,
        markers: false,
        toggleActions: "play none none reverse",
      });

      const fadeIn = (target, x = 0, y = 0, duration = 1) => {
        this.$gsap.from(target, {
          x,
          y,
          duration,
          opacity: 0,
          scrollTrigger: scrollTriggerConfig(target),
        });
      };

      this.$gsap.from(".hero .head", {
        x: 100,
        duration: 1,
      });

      fadeIn(".servicesbtn", 50);
      fadeIn(".portfolio .head h1", 0, 50, 0.5);
      fadeIn(".slidOurTeam", 50);

      this.$gsap
        .timeline({
          scrollTrigger: {
            trigger: ".comments",
            start: "top bottom",
            end: "bottom center",
            scrub: 1.5,
            markers: false,
          },
        })
        .to(".commentsSvg", {
          y: 50,
        });
    },
    nextSwiper(swiperRef) {
      const activeSwiperRefRef = this.$refs[swiperRef];
      activeSwiperRefRef.swiper.slideNext();
    },
    prevSwiper(carouselRef) {
      const activeCarouselRef = this.$refs[carouselRef];
      activeCarouselRef.swiper.slidePrev();
    },
    async teamLoadData() {
      const data = this.$store.getters["teamMembers/teamData"];
      if (data.length !== 4) {
        await this.$store.dispatch("teamMembers/fetchTeammembersData");
      }
      const content = document.querySelector(".ourTeam");
      const imgload = this.$imagesLoaded(content);
      imgload.on("done", () => {
        this.teamDataLoaded = true;
        this.initSwiperTeam();
      });
    },
    async getPortfolioData() {
      const data = this.$store.getters["portfolio/projectsData"];
      if (data.length === 0) {
        await this.$store.dispatch("portfolio/homePortfoliosData", "5");
      }
      const content = document.querySelector(".portfolio");
      const imgload = this.$imagesLoaded(content);
      imgload.on("done", () => {
        this.PortfolioDataLoaded = true;
        this.initSwiperPort();
      });
    },
    odometerInit() {
      const els = document.querySelectorAll(".odometer");
      els.forEach((ele) => {
        new odometer({
          el: ele,
          value: 0,
        });

        this.$ScrollTrigger.create({
          trigger: ele,
          start: "bottom 98%",
          onToggle: () => {
            ele.innerHTML = ele.dataset.numm;
          },
        });
      });
    },
    tiltInit() {
      const elements = document.querySelectorAll(".box-tilt");
      const baseQuery = "(min-width: 992px)";

      const bQMatch = window.matchMedia(baseQuery);

      if (bQMatch.matches) {
        elements.forEach((ele) => {
          this.$VanillaTilt.init(ele);
        });
      }
    },
  },
  computed: {
    getTeamMembersData() {
      return this.$store.getters["teamMembers/teamData"];
    },
    getProjectsData() {
      return this.$store.getters["portfolio/projectsData"];
    },
  },
  async mounted() {
    this.gsapAnimation();
    this.odometerInit();
    this.doneLoading();
    this.teamLoadData();
    this.getPortfolioData();
    this.tiltInit();
  },
  beforeRouteUpdate() {
    this.gsapAnimation();
  },
};
</script>

<style lang="scss" scoped>
/* ALL CSS REMAINS EXACTLY THE SAME - NOTHING CHANGED */
.homePage {
  position: relative;
  @media (max-width: 1540px) {
    .hero {
      padding-top: 220px !important;
      min-height: 960px !important;
    }
  }
  @media (max-width: 1150px) and (min-width: 758px) {
    .hero {
      height: initial !important;
    }
  }
  @media (max-width: 1400px) {
    .hero {
      padding-top: 200px !important;
      min-height: 880px !important;
    }
  }
  @media (max-width: 1200px) {
    .hero {
      padding-top: 200px !important;
      padding-bottom: 350px !important;
    }
  }
  @media (max-width: 767px) {
    .hero {
      padding-top: 60px !important;
      padding-bottom: 260px !important;
      min-height: 680px !important;
      display: flex;
      align-items: center;
    }
  }
  .hero {
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
    height: calc(100dvh + 180px);
    padding: 220px 0 170px;
    position: relative;
    overflow: hidden;
    color: white;
    h1,
    p,
    .goToBtn {
      color: white !important;
    }
    .goToBtn .hoveranim::before {
      background-color: #f4b400;
    }
    .content {
      @media (max-width: 1400px) {
        h1 {
          font-size: 100px !important;
        }
      }
      @media (max-width: 1199px) {
        h1 {
          font-size: 80px !important;
        }
      }
      @media (max-width: 991px) {
        h1 {
          font-size: 56px !important;
          margin-bottom: 20px !important;
        }
      }
      @media (max-width: 575px) {
        h1 {
          font-size: 42px !important;
        }
      }
      h1 {
        font-size: 60px;
        font-weight: 700;
        margin-bottom: 60px;
        position: relative;
        width: fit-content;
        height: auto;
        @media (max-width: 575px) {
          br {
            display: none;
          }
        }
      }
      @media (max-width: 991px) {
        .getaQuote {
          flex-direction: column-reverse;
          align-items: start !important;
          .getaq-btn {
            width: fit-content !important;
          }
          p {
            width: 100% !important;
            max-width: 500px !important;
          }
        }
      }
      .getaQuote {
        display: flex;
        align-items: center;
        .getaq-btn {
          .cont {
            width: fit-content;
            display: flex;
            align-items: center;
            @media (min-width: 992px) {
              &:hover {
                color: var(--prim-color);
                cursor: pointer;
                span {
                  &::before {
                    width: 100%;
                  }
                }
              }
            }
          }
          width: 50%;
          font-size: 17px;
          font-weight: 500;
          display: flex;
          align-items: center;
          transition: color 0.4s;
          svg {
            margin-left: 15px;
          }
          span {
            display: block;
          }
        }
        @media (max-width: 991px) {
          p {
            margin-bottom: 24px !important;
          }
        }
        p {
          width: 50%;
          font-size: 17px;
          font-weight: 500;
          line-height: 1.9rem;
          margin: 0;
        }
      }
      @media (max-width: 1199px) {
        .scrollDown {
          bottom: 220px !important;
        }
      }
      .scrollDown {
        content: "";
        position: absolute;
        height: 35px;
        width: 20px;
        border-radius: 10px;
        border: 2px solid white;
        left: 50%;
        transform: translate(-50%);
        bottom: 25%;
        &::before {
          content: "";
          position: absolute;
          height: 5px;
          width: 5px;
          border-radius: 50%;
          background-color: white;
          top: 50%;
          left: 50%;
          transform: translate(-50%, -50%);
          animation-name: scrolldown;
          animation-duration: 3s;
          animation-iteration-count: infinite;
          animation-timing-function: ease-in-out;
        }
      }
    }
    @media (max-width: 1200px) {
      .follow-us {
        display: none;
      }
    }
    .follow-us {
      position: absolute;
      top: 50%;
      right: 45px;
      transform: translateY(-85%) rotate(180deg);
      writing-mode: vertical-lr;
      span {
        color: #fefefe;
        display: inline;
        text-transform: capitalize;
        font-size: 17px;
        font-weight: 500;
        position: relative;
        &:not(:last-of-type) {
          padding-bottom: 35px;
        }
        &:nth-child(1) {
          &::after {
            content: "";
            position: absolute;
            right: 50%;
            transform: translate(-50%);
            bottom: 10px;
            height: 15px;
            width: 2px;
            background-color: #fefefe;
          }
        }
        &:nth-child(2) {
          cursor: pointer;
          transition: color 0.3s ease-in-out;
          @media (min-width: 992px) {
            &:hover {
              color: var(--prim-color);
            }
          }
          &::after {
            content: "";
            position: absolute;
            left: 0px;
            bottom: 10px;
            height: 2px;
            width: 15px;
            background-color: #fefefe;
          }
        }
        &:nth-child(3) {
          padding-top: 10px;
          cursor: pointer;
          transition: color 0.3s ease-in-out;
          @media (min-width: 992px) {
            &:hover {
              color: var(--prim-color);
            }
          }
        }
      }
    }
  }
  @media (max-width: 991px) {
    .ourFunFact {
      margin-bottom: 80px !important;
    }
  }
  .ourFunFact {
    margin-bottom: 150px;
    @media (max-width: 1399px) {
      .statusBorder {
        padding: 60px 50px !important;
      }
    }
    @media (max-width: 575px) {
      .statusBorder {
        padding: 40px 30px !important;
      }
    }
    .statusBorder {
      position: relative;
      padding: 60px 80px;
      background: #f4b400;
      border-radius: 15px;
      margin-top: -130px;
      z-index: 1;
      overflow: hidden;
      img {
        position: absolute;
        top: 0;
        right: -20%;
        width: 100%;
        height: 100%;
      }
      @media (max-width: 1199px) {
        .status {
          flex-direction: column;
          .info {
            width: 100% !important;
            margin-bottom: 50px !important;
          }
          .nums {
            width: 100% !important;
            padding-left: 0px !important;
          }
        }
      }
      .status {
        display: flex;
        position: relative;
        @media (max-width: 1400px) {
          .info {
            h1 {
              margin-bottom: 10px !important;
              font-size: 42px !important;
            }
          }
        }
        @media (max-width: 991px) {
          .info {
            margin-bottom: 30px !important;
          }
        }
        .info {
          width: 40%;
          h1 {
            font-size: 50px;
            margin-bottom: 20px;
            font-weight: bold;
            color: #111827;
          }
          p {
            margin: 0;
            color: #374151;
            line-height: 1.75em;
            font-size: 17px;
          }
        }
        @media (max-width: 1400px) {
          .nums {
            padding-left: 50px !important;
          }
        }
        @media (max-width: 1199px) {
          .nums {
            padding-left: 0px !important;
          }
        }
        .nums {
          width: 60%;
          padding-left: 80px;
          .num {
            display: flex;
            align-items: center;
            @media (max-width: 1400px) {
              .odometer,
              .kword {
                font-size: 42px !important;
              }
            }
            .odo {
              display: flex;
              align-items: center;
              .kword {
                font-size: 50px;
                font-weight: 700;
                color: #111827;
              }
            }
            .odometer {
              font-size: 50px;
              padding-top: 5px;
              font-weight: 700;
              color: #111827;
            }
            .title {
              display: flex;
              flex-direction: column;
              justify-content: center;
              align-items: start;
              margin-left: 13px;
              svg {
                color: #111827;
                font-size: 13px;
              }
              span {
                color: #374151;
                font-size: 17px;
              }
            }
          }
        }
      }
    }
  }
  .services {
    background-color: #ffffff;
    background-image: linear-gradient(
        rgba(244, 180, 0, 0.1) 1px,
        transparent 1px
      ),
      linear-gradient(90deg, rgba(244, 180, 0, 0.1) 1px, transparent 1px);
    background-size: 38px 38px;
    border: 1.5px solid rgba(244, 180, 0, 0.25);
    padding: 80px 0;
    border-radius: 20px;
    margin-top: 60px;
    .mainTitle {
      color: #1d4ed8 !important;
    }
    .homeheadsec {
      display: inline-block;
      background: #f4b400;
      color: #111827 !important;
      font-size: 13px !important;
      font-weight: 700 !important;
      letter-spacing: 1.2px;
      text-transform: uppercase;
      padding: 5px 14px;
      border-radius: 20px;
      margin-bottom: 14px;
    }
    .goToBtn {
      color: #1d4ed8 !important;
    }
    .goToBtn .hoveranim::before {
      background-color: #1d4ed8;
    }
    .content {
      @media (max-width: 1199px) {
        .info {
          margin-bottom: 90px !important;
        }
      }
      @media (max-width: 991px) {
        .info {
          margin-bottom: 45px !important;
        }
      }
      .projects {
        margin: 0;
        @media (max-width: 991px) {
          .box {
            margin-bottom: 30px !important;
          }
        }
        .box {
          .box-container {
            position: relative;
            display: block;
            overflow: hidden;
            border-radius: 12px;
            text-decoration: none;
            color: white;
            font-size: 24px;
            font-weight: 500;
            transition: all 0.4s ease;
            border: 2px solid rgba(29, 78, 216, 0.3);
            box-shadow: 0 10px 32px rgba(29, 78, 216, 0.45);
            @media (min-width: 992px) {
              &:hover {
                box-shadow: 0 18px 48px rgba(244, 180, 0, 0.6);
                border-color: #f4b400;
                transform: translateY(-6px);
              }
            }
            &::before {
              content: "";
              position: absolute;
              top: 0;
              left: 0;
              width: 100%;
              height: 100%;
              background: linear-gradient(
                160deg,
                rgba(10, 22, 40, 0.78) 0%,
                rgba(29, 78, 216, 0.52) 100%
              );
              transition: background 0.4s ease;
            }
            @media (min-width: 992px) {
              &:hover::before {
                background: linear-gradient(
                  160deg,
                  rgba(10, 22, 40, 0.6) 0%,
                  rgba(244, 180, 0, 0.3) 100%
                );
              }
            }
            span {
              position: absolute;
              top: 50%;
              left: 50%;
              transform: translate(-50%, -50%);
              text-align: center;
              width: 90%;
              text-shadow: 0 2px 8px rgba(0, 0, 0, 0.6);
              letter-spacing: 0.3px;
            }
            img {
              width: 100%;
              height: 100%;
              max-width: 100%;
              max-height: 100%;
              transition: transform 0.5s ease;
            }
            @media (min-width: 992px) {
              &:hover img {
                transform: scale(1.07);
              }
            }
          }
        }
      }
    }
  }
  @media (max-width: 991px) {
    .portfolio {
      margin-top: 50px !important;
    }
  }
  .portfolio {
    margin-top: 150px;
    @media (max-width: 991px) {
      .head {
        margin-bottom: 45px !important;
      }
    }
    .content {
      .head {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        margin-bottom: 90px;
        @media (max-width: 1380px) {
          h1 {
            font-size: 42px !important;
          }
        }
        @media (max-width: 991px) {
          h1 {
            font-size: 36px !important;
          }
        }
        h1 {
          font-size: 50px;
          margin: 0;
        }
      }
      @media (max-width: 991px) {
        .slide {
          height: 380px !important;
        }
      }
      .swiper-container {
        .swiper-wrapper {
          .swiper-slide {
            &:not(.swiper-slide-active) {
              .slide {
                .artWork {
                  animation: leaveportSlidesAnimation 0.6s forwards;
                  span:nth-child(1) {
                    animation: leavespanPortSlidesAnimation 0.5s 0.1s forwards;
                  }
                  span:nth-child(2) {
                    animation: leavespanPortSlidesAnimation 0.5s 0.2s forwards;
                  }
                }
              }
            }
            &.swiper-slide-active {
              .slide {
                .artWork {
                  animation: enterportSlidesAnimation 0.6s forwards;
                  span:nth-child(1) {
                    animation: enterspanPortSlidesAnimation 0.5s 0.1s forwards;
                  }
                  span:nth-child(2) {
                    animation: enterspanPortSlidesAnimation 0.5s 0.2s forwards;
                  }
                }
                @media (min-width: 992px) {
                  .img {
                    height: 100% !important;
                  }
                }
              }
            }
            .slide {
              height: 450px;
              width: 100%;
              display: flex;
              align-items: center;
              justify-content: center;
              @media (min-width: 992px) {
                .img {
                  height: 80% !important;
                  transition: height 0.5s ease;
                }
              }
              .img {
                position: relative;
                overflow: hidden;
                border-radius: 20px;
                width: 100%;
                max-width: 100%;
                height: 100%;
                transition: height 0.5s ease;
                object-fit: cover;
                cursor: pointer;
                margin: 0 10px;
                a {
                  color: white;
                  position: relative;
                  display: block;
                  z-index: 2;
                  width: 100%;
                  height: 100%;
                  @media (min-width: 992px) {
                    &:hover {
                      &:after {
                        background-color: rgba(22, 22, 22, 0.4) !important;
                      }
                    }
                  }
                  &::after {
                    content: "";
                    position: absolute;
                    width: 100%;
                    height: 100%;
                    left: 0;
                    top: 0;
                    z-index: 2;
                    background-color: transparent;
                    transition-duration: 0.4s;
                  }
                  img {
                    max-width: 100%;
                    width: 100%;
                    height: 100%;
                    object-fit: cover;
                    z-index: 1;
                  }
                  .artWork {
                    position: absolute;
                    width: 300px;
                    height: 300px;
                    padding: 105px 20px 80px 65px;
                    border-radius: 50%;
                    background-color: var(--prim-color);
                    z-index: 3;
                    display: flex;
                    flex-direction: column;
                    @media (max-width: 1380px) {
                      span:nth-child(1) {
                        font-size: 20px !important;
                      }
                    }
                    span {
                      position: relative;
                      display: block;
                      text-align: start;
                      &:nth-child(1) {
                        font-size: 22px;
                        margin-bottom: 5px;
                        font-weight: 700;
                      }
                      &:nth-child(2) {
                        color: #fefefeb3;
                        font-weight: 500;
                        width: fit-content;
                        &::after {
                          content: "";
                          position: absolute;
                          bottom: 8px;
                          right: -30px;
                          width: 20px;
                          height: 1px;
                          background-color: #fefefeb3;
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }
      }
    }
  }
  @media (max-width: 991px) {
    .ourTeam {
      margin-bottom: 80px !important;
    }
  }
  .ourTeam {
    margin-bottom: 150px;
    a {
      color: #fefefe;
    }
    @media (max-width: 991px) {
      .controls {
        margin-bottom: 45px !important;
        align-items: start !important;
        flex-direction: column;
        .myCustomNav {
          margin-top: 15px !important;
        }
      }
    }
    .controls {
      margin-bottom: 85px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      .myCustomNav {
        .prevbtn {
          margin-left: 0 !important;
        }
      }
      .mainTitle {
        margin-bottom: 0 !important;
      }
    }
    @media (max-width: 767px) {
      .memberCard {
        margin: 0 !important;
      }
    }
    .swiper-container {
      .swiper-wrapper {
        .swiper-slide {
          .memberCard {
            width: 100%;
            position: relative;
            cursor: pointer;
            @media (min-width: 992px) {
              &:hover {
                .img-container {
                  img {
                    transform: scale(1.1);
                  }
                }
                .social {
                  transform: rotate(0deg) scale(1) !important;
                }
              }
            }
            .img-container {
              border-radius: 15px;
              overflow: hidden;
              z-index: 1;
              img {
                width: 100%;
                max-width: 100%;
                transition-duration: 1s;
              }
            }
            .title {
              position: absolute;
              bottom: 30px;
              left: 25px;
              z-index: 2;
              text-align: start;
              @media (max-width: 1380px) {
                .name {
                  font-size: 20px !important;
                }
              }
              .name {
                font-size: 23px;
                font-weight: 700;
                text-transform: capitalize;
              }
              .rule {
                color: #fefefeb3;
              }
            }
            .socials {
              position: absolute;
              left: 25px;
              top: 15px;
              z-index: 2;
              .social {
                margin: 20px 20px 20px 0;
                font-size: 18px;
                transition-duration: 0.5s;
                transform: rotate(45deg) scale(0);
                @media (min-width: 992px) {
                  &:hover {
                    color: var(--prim-color);
                  }
                }
              }
            }
          }
        }
      }
    }
  }
  @media (max-width: 991px) {
    .comments {
      padding: 80px 0 !important;
    }
  }
  .comments {
    padding: 130px 0;
    background: linear-gradient(135deg, #1d4ed8, #1e3a8a);
    position: relative;
    color: white;
    .ppcol {
      display: flex;
      align-items: center;
      @media (max-width: 576px) {
        .swiper-container {
          padding: 40px 0 !important;
        }
      }
      @media (max-width: 991px) and (min-width: 577px) {
        .swiper-container {
          padding: 55px 0 !important;
        }
      }
      .swiper-container {
        padding: 80px 0;
        .swiper-wrapper {
          position: relative;
          .swiper-slide {
            width: calc(100% / 3);
            height: 100%;
            opacity: 0.5;
            transition-duration: 0.7s;
            .img-container {
              cursor: pointer;
              position: relative;
              width: 100%;
              height: 100%;
              z-index: 3;
              img {
                aspect-ratio: 1 / 1;
                max-width: 100%;
                width: 100%;
                clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);
              }
            }
            @media (max-width: 991px) {
              &.swiper-slide-active {
                transform: scale(1.4) !important;
              }
            }
            &.swiper-slide-active {
              z-index: 2;
              transform: scale(1.8);
              opacity: 1;
            }
          }
        }
      }
    }
    .cmmtcol {
      position: relative;
      .swiper-container {
        .swiper-wrapper {
          .swiper-slide {
            @media (max-width: 991px) {
              .commentContainer {
                padding: 60px 0 0 20px !important;
              }
            }
            .commentContainer {
              padding: 70px 0 0 70px;
              position: relative;
              text-align: start;
              & > svg {
                position: absolute;
                top: 0;
                left: 0;
                font-size: 50px;
              }
              @media (max-width: 1380px) {
                p {
                  font-size: 20px !important;
                }
              }
              p {
                font-size: 22px;
                font-weight: 600;
                line-height: 1.5em;
                color: #fefefe;
              }
              .stars {
                margin-top: 24px;
                svg {
                  color: var(--prim-color);
                  margin: 0 2px;
                  font-size: 19px;
                  &.deactive {
                    color: #ff491727;
                  }
                }
              }
              @media (max-width: 991px) {
                .pplInfo {
                  margin-top: 30px !important;
                }
              }
              .pplInfo {
                margin-top: 70px;
                @media (max-width: 991px) {
                  .name {
                    font-size: 20px !important;
                  }
                }
                .name {
                  font-size: 22px;
                  font-weight: 700;
                  line-height: 1.3em;
                }
                .rule {
                  margin-top: 10px;
                  text-transform: uppercase;
                  color: #fefefeb3;
                  margin-left: 40px;
                  position: relative;
                  &::before {
                    content: "";
                    position: absolute;
                    top: 50%;
                    left: -40px;
                    transform: translateY(-50%);
                    height: 2px;
                    width: 20px;
                    background-color: #fefefeb3;
                  }
                }
              }
            }
          }
        }
      }
      .myCustomNav {
        position: absolute;
        bottom: 0;
        right: 0;
        z-index: 2;
      }
    }
    & > img {
      position: absolute;
      top: -50px;
      right: 0;
      margin-right: 20px;
    }
  }
  .partners {
    @media (max-width: 1380px) {
      .scroller {
        font-size: 100px !important;
      }
    }
    @media (max-width: 1199px) {
      .scroller {
        font-size: 80px !important;
      }
    }
    @media (max-width: 575px) {
      .scroller {
        font-size: 56px !important;
      }
    }
    .scroller {
      font-size: 120px;
      font-weight: 700;
      -webkit-text-fill-color: transparent;
      -webkit-text-stroke-color: var(--prim-color);
      -webkit-text-stroke-width: 2px;
      white-space: nowrap;
      overflow-x: hidden;
      display: flex;
      flex-wrap: nowrap;
      align-items: center;
      mask: linear-gradient(
        90deg,
        transparent,
        white 10%,
        white 90%,
        transparent
      );
      .scroller_inner {
        animation: scrollerAnimation 20s linear infinite;
      }
    }
    @media (max-width: 991px) {
      .content {
        margin: 70px 0 0 0 !important;
      }
    }
    .content {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin: 100px 0 0 0;
      @media (max-width: 575px) {
        .brand-logo {
          padding: 10px !important;
        }
      }
      .brand-logo {
        &:nth-of-type(1) {
          padding-left: 0;
        }
        &:nth-of-type(5) {
          padding-right: 0;
        }
        transition-duration: 0.5s;
        cursor: pointer;
        @media (min-width: 992px) {
          &:hover {
            transform: scale(1.1);
          }
        }
        padding: 20px;
        img {
          max-width: 100%;
          width: 100%;
          height: auto;
          filter: brightness(0) invert(0.45);
          transition: filter 0.3s ease;
        }
        @media (min-width: 992px) {
          &:hover img {
            filter: brightness(0) invert(0.15);
          }
        }
      }
    }
  }
  .howWeWork {
    padding: 100px 0;
    background-color: #f9fafb;
    .section-head {
      margin-bottom: 70px;
      .mainTitle {
        color: #1d4ed8 !important;
      }
    }
    .steps {
      @media (max-width: 767px) {
        .step {
          margin-bottom: 40px;
        }
      }
      .step {
        padding: 40px 30px;
        background: white;
        border-radius: 16px;
        box-shadow: 0 4px 20px rgba(29, 78, 216, 0.08);
        height: 100%;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        @media (min-width: 992px) {
          &:hover {
            transform: translateY(-6px);
            box-shadow: 0 12px 30px rgba(29, 78, 216, 0.15);
          }
        }
        .step-num {
          font-size: 48px;
          font-weight: 800;
          color: #f4b400;
          line-height: 1;
          margin-bottom: 18px;
        }
        h4 {
          font-size: 20px;
          font-weight: 700;
          color: #111827;
          margin-bottom: 14px;
        }
        p {
          font-size: 15px;
          color: #6b7280;
          line-height: 1.75;
          margin: 0;
        }
      }
    }
  }
  .techStack {
    padding: 100px 0;
    background: linear-gradient(
      135deg,
      #0a1628 0%,
      #0f2460 30%,
      #1d4ed8 65%,
      #1e3a8a 100%
    );
    .section-head {
      margin-bottom: 60px;
      .homeheadsec {
        color: rgba(255, 255, 255, 0.6) !important;
      }
      .mainTitle {
        color: white !important;
      }
    }
    .tech-grid {
      row-gap: 24px;
      .tech-card {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 12px;
        padding: 28px 16px;
        background: rgba(255, 255, 255, 0.06);
        border: 1px solid rgba(255, 255, 255, 0.1);
        border-radius: 14px;
        transition: all 0.3s ease;
        cursor: default;
        @media (min-width: 992px) {
          &:hover {
            background: rgba(244, 180, 0, 0.15);
            border-color: #f4b400;
            transform: translateY(-4px);
            svg {
              color: #f4b400;
            }
          }
        }
        svg {
          font-size: 36px;
          color: rgba(255, 255, 255, 0.8);
          transition: color 0.3s ease;
        }
        span {
          font-size: 13px;
          font-weight: 600;
          color: rgba(255, 255, 255, 0.75);
          text-align: center;
        }
      }
    }
  }
  .meeting {
    @media (max-width: 991px) {
      .content {
        padding: 70px 30px !important;
      }
    }
    @media (max-width: 575px) {
      .content {
        padding: 70px 20px !important;
      }
    }
    .content {
      position: relative;
      background: #f4b400;
      padding: 90px 30px;
      border-radius: 15px;
      text-align: center;
      overflow: hidden;
      .shape {
        z-index: 2 !important;
        border-left-color: #1d4ed8 !important;
      }
      .mainTitle {
        position: relative;
        z-index: 3;
        color: #111827 !important;
      }
      .goToBtn {
        color: #111827 !important;
      }
      .mainBtn {
        background-color: #1d4ed8 !important;
        color: white !important;
      }
      .statusSvg {
        position: absolute;
        top: 0;
        right: 0;
        width: 100%;
        height: 100%;
        z-index: 1;
      }
      @media (max-width: 575px) {
        .mainTitle {
          font-size: 28px !important;
        }
      }
      @media (max-width: 991px) {
        .meetingBtn {
          margin: 30px auto 0 !important;
        }
      }
      .meetingBtn {
        position: relative;
        margin: 70px auto 0;
        z-index: 3;
      }
    }
  }
}

@keyframes scrolldown {
  0% {
    top: 30%;
    opacity: 1;
    width: 5px;
    height: 5px;
  }
  50% {
    top: 70%;
    opacity: 0.5;
    width: 4px;
    height: 4px;
  }
  100% {
    top: 30%;
    opacity: 1;
    width: 5px;
    height: 5px;
  }
}
@keyframes arrowShapeAnimation {
  0% {
    transform: translate(0, -50%) rotate(45deg);
  }
  50% {
    transform: translate(60px, -50%) rotate(45deg);
  }
  100% {
    transform: translate(0, -50%) rotate(45deg);
  }
}
@keyframes playBtnAnimation {
  0% {
  }
  100% {
    transform: scale(1.5);
    opacity: 0;
  }
}
@keyframes scrollerAnimation {
  to {
    transform: translate(calc(-50% - 12px));
  }
}
@keyframes enterportSlidesAnimation {
  from {
    bottom: -200px;
    left: -100px;
    opacity: 0;
  }
  to {
    bottom: -60px;
    left: -40px;
    opacity: 1;
  }
}
@keyframes enterspanPortSlidesAnimation {
  from {
    left: 50px;
    opacity: 0;
  }
  to {
    left: 0;
    opacity: 1;
  }
}
@keyframes leaveportSlidesAnimation {
  from {
    bottom: -60px;
    left: -40px;
    opacity: 1;
  }
  to {
    bottom: -200px;
    left: -100px;
    opacity: 0;
  }
}
@keyframes leavespanPortSlidesAnimation {
  from {
    left: 0;
    opacity: 1;
  }
  to {
    left: 50px;
    opacity: 0;
  }
}
.YTIframe-enter-active,
.YTIframe-leave-active {
  transition-duration: 0.5s;
}

.YTIframe-enter-from,
.YTIframe-leave-to {
  opacity: 0;
  transform: translateY(-50px);
}
.YTIframe-enter-to {
  opacity: 1;
  transform: translateY(0);
}
.dataFadein-enter-active,
.dataFadein-leave-active {
  transition-duration: 1s;
}

.dataFadein-enter-from,
.dataFadein-leave-to {
  opacity: 0;
}
.dataFadein-enter-to {
  opacity: 1;
}
</style>
