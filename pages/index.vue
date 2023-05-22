<template>
  <div class="home-container">
    <section class="home-hero">
      <div class="home-menu">
        <div id="mobile-menu" class="home-mobile-navigation">
          <img
            alt="pastedImage"
            src="/playground_assets/pastedimage-no9b-1500h.png"
            class="home-logo"
          />
          <div class="home-links">
            <span class="Link">Solutions</span>
            <span class="Link">How it works</span>
            <span class="Link">Prices</span>
          </div>
          <div id="close-mobile-menu" class="home-close-mobile-menu">
            <svg viewBox="0 0 804.5714285714286 1024" class="home-icon">
              <path
                d="M741.714 755.429c0 14.286-5.714 28.571-16 38.857l-77.714 77.714c-10.286 10.286-24.571 16-38.857 16s-28.571-5.714-38.857-16l-168-168-168 168c-10.286 10.286-24.571 16-38.857 16s-28.571-5.714-38.857-16l-77.714-77.714c-10.286-10.286-16-24.571-16-38.857s5.714-28.571 16-38.857l168-168-168-168c-10.286-10.286-16-24.571-16-38.857s5.714-28.571 16-38.857l77.714-77.714c10.286-10.286 24.571-16 38.857-16s28.571 5.714 38.857 16l168 168 168-168c10.286-10.286 24.571-16 38.857-16s28.571 5.714 38.857 16l77.714 77.714c10.286 10.286 16 24.571 16 38.857s-5.714 28.571-16 38.857l-168 168 168 168c10.286 10.286 16 24.571 16 38.857z"
              ></path>
            </svg>
          </div>
        </div>
        <div class="home-desktop-navigation">
          <nav class="home-centered">
            <div class="home-left">
              <img
                alt="pastedImage"
                src="/playground_assets/screenshot%202023-05-22%20at%207.45.23%20pm_adobe_express.svg"
                class="home-logo1"
              />
              <div class="home-links1">
                <span class="Link">Solutions</span>
                <span class="Link">How it works</span>
                <span class="Link">Prices</span>
              </div>
            </div>
            <div class="home-right">
              <span class="home-sign-in Link">Sign in</span>
              <div class="home-get-started">
                <span class="home-text006">Get started</span>
              </div>
              <div id="open-mobile-menu" class="home-burger-menu">
                <img
                  alt="pastedImage"
                  src="/playground_assets/pastedimage-yxbd.svg"
                  class="home-mobile-menu-button"
                />
              </div>
            </div>
          </nav>
        </div>
        <div>
          <DangerousHTML
            html="<script>
  /*
  Mobile menu - Code Embed
  */
  
  // Mobile menu
  const mobileMenu = document.querySelector('#mobile-menu')
  
  // Buttons
  const closeButton = document.querySelector('#close-mobile-menu')
  const openButton = document.querySelector('#open-mobile-menu')
  
  // On openButton click, set the mobileMenu position left to -100vw
  openButton.addEventListener('click', function() {
      mobileMenu.style.transform = 'translateX(0%)'
  })
  
  // On closeButton click, set the mobileMenu position to 0vw
  closeButton.addEventListener('click', function() {
      mobileMenu.style.transform = 'translateX(100%)'
  })
  </script>"
          ></DangerousHTML>
        </div>
      </div>
      <header class="home-header">
        <h1 class="home-text007">Take Control of Web Content Creation</h1>
        <p class="home-text008">
          Produce high quality content for your websites effortlessly.
        </p>
        <div class="home-get-started1">
          <span class="home-text009">Get started</span>
        </div>
      </header>
      <div class="home-dashboard-preview">
        <div class="home-outline">
          <img
            alt="pastedImage"
            src="/playground_assets/pastedimage-cdo-1000h.png"
            loading="lazy"
            class="home-image"
          />
        </div>
      </div>
    </section>
    <section class="home-features">
      <div class="home-title">
        <span class="home-text010">
          Let&apos;s take the cons out of content creation
        </span>
        <span class="home-text011">
          <span>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            <span v-html="rawin6n"></span>
          </span>
          <span>eiusmod tempor incididunt.</span>
        </span>
      </div>
      <div class="home-cards">
        <div class="home-container1">
          <div class="card">
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-fii6m-200h.png"
              class="home-icon02"
            />
            <span class="home-text014">Create</span>
            <span class="home-text015">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor
            </span>
          </div>
          <div class="home-publish card">
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-mimg-200h.png"
              class="home-icon03"
            />
            <span class="home-text016">Optimize</span>
            <span class="home-text017">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sedr
            </span>
          </div>
        </div>
        <div class="home-container2">
          <div class="card home-analyze">
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-l6p-200h.png"
              class="home-icon04"
            />
            <span class="home-text018">Publish</span>
            <span class="home-text019">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor
            </span>
          </div>
          <div class="card">
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-vyi5-200h.png"
              class="home-icon05"
            />
            <span class="home-text020">Get Traffic</span>
            <span class="home-text021">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor
            </span>
          </div>
        </div>
      </div>
    </section>
    <section class="home-quote-container">
      <div class="home-quote">
        <span class="home-message">
          “Scale your content, grew lorem ipsum dolor sit amet, consectetur
          adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
          magna aliqua.”
        </span>
        <div class="home-author">
          <img
            alt="image"
            src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDV8fGdpcmx8ZW58MHx8fHwxNjY0ODA5MjE1&amp;ixlib=rb-1.2.1&amp;w=200"
            class="home-avatar"
          />
          <span class="home-quote1">
            <span class="home-text022">—  Peter McPau</span>
            <span>, Founder and CEO, Active</span>
          </span>
        </div>
      </div>
    </section>
    <section class="home-statistics">
      <div class="home-container3">
        <active-users Caption="— Active users" Statistic="3.5M"></active-users>
        <active-users Caption="— Brands" Statistic="50k"></active-users>
        <active-users
          Caption="— Accounts Managed"
          Statistic="250K"
        ></active-users>
        <active-users Caption="— Active leads" Statistic="30M"></active-users>
      </div>
    </section>
    <section class="home-banners">
      <div class="home-banner-manage">
        <div class="home-container4">
          <div class="home-left1">
            <span class="sub-title">Content Management</span>
            <span class="home-text025 title">
              Manage all your websites in just one place.
            </span>
            <span class="home-text026">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
            </span>
            <div class="home-get-started2 template-button">
              <span class="home-text027">Get started</span>
            </div>
          </div>
          <div class="home-image-container">
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-wvmq%201-1200w.png"
              class="home-cards-image"
            />
          </div>
        </div>
      </div>
      <div class="home-banner-advanced-analytics">
        <div class="home-centered-container">
          <div class="home-image-container1">
            <img
              alt="pastedImage"
              src="/playground_assets/test-1200w.png"
              class="home-cards-image1"
            />
          </div>
          <div class="home-right1">
            <span class="sub-title">
              Reporting Metrics
              <span v-html="rawxkkm"></span>
            </span>
            <h2 class="home-text029 title">
              Advanced optimizations, easy to understand.
            </h2>
            <div class="home-category">
              <span class="home-text030">Readability</span>
              <span class="home-text031">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
              </span>
              <span class="home-text032">Example -&gt;</span>
            </div>
            <div class="home-category1">
              <span class="home-text033">Sentiment analysis</span>
              <span class="home-text034">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
              </span>
              <span class="home-text035">Example -&gt;</span>
            </div>
          </div>
        </div>
      </div>
      <div class="home-banner">
        <div class="home-container5">
          <div class="home-left2">
            <span class="home-text036">Improve Scheduling</span>
            <h2 class="home-text037 title">
              Powerful scheduler that saves you time
            </h2>
            <span class="home-text038">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
            </span>
            <div class="home-get-started3 template-button">
              <span class="home-text039">Get started</span>
            </div>
          </div>
          <div class="home-image-container2">
            <img
              alt="pastedImage"
              src="/playground_assets/83d913a38a75e38d7cef4fea757ed7ed-1200w.png"
              class="home-cards-image2"
            />
          </div>
        </div>
      </div>
    </section>
    <section class="home-integrations">
      <div class="home-centered-container1">
        <div class="home-heading">
          <span class="sub-title">Integrations</span>
          <span class="title">Integrated with the tools you know and love</span>
          <span class="home-text042">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
          </span>
        </div>
        <div class="home-pills-container">
          <div class="home-pills">
            <div class="home-container6">
              <you-tube></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201012-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/layer1-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group-200h.png"
              ></you-tube>
            </div>
            <div class="home-container7">
              <you-tube
                pastedImage_src="/playground_assets/pinterest%20logo-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201014-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201015-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201017-200h.png"
              ></you-tube>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="home-how-it-works">
      <div class="home-centered-container2">
        <div class="home-heading1">
          <span class="home-text043">How it works</span>
          <span class="home-text044 title">
            Making a living out of content has never been easier.
          </span>
        </div>
        <div class="home-category2">
          <div class="home-headng">
            <span class="home-text045">
              1 — Sign up
              <span v-html="rawopp6"></span>
            </span>
            <span class="home-text046">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
            </span>
            <div class="home-get-started4 template-button">
              <span class="home-text047">Get started</span>
            </div>
          </div>
          <div class="home-container8">
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-k5xi%201-1200w.png"
              class="home-pasted-image"
            />
          </div>
        </div>
        <div class="home-row">
          <div class="home-category3">
            <div class="home-headng1">
              <span class="home-text048">2 — Act</span>
              <span class="home-text049">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
              </span>
            </div>
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-ibg-1200w.png"
              class="home-pasted-image1"
            />
          </div>
          <div class="home-category4">
            <div class="home-headng2">
              <span class="home-text050">2 — Act</span>
              <span class="home-text051">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. vv
              </span>
            </div>
            <img
              alt="pastedImage"
              src="/playground_assets/pastedimage-3c4o-1200w.png"
              class="home-pasted-image2"
            />
          </div>
        </div>
      </div>
    </section>
    <section class="home-pricing">
      <div class="home-centered-container3">
        <div class="home-heading2">
          <span class="home-text052 title">Pricing that works for you</span>
          <span class="home-text053">
            Our next-generation solutions for small business customers and
            solopreneurs with pricing options that accommodate everyone.
          </span>
          <div class="home-selection">
            <span class="home-text054">Monthly</span>
            <span class="home-text055">Yearly</span>
          </div>
        </div>
        <div class="home-cards1">
          <div class="home-card">
            <span class="home-text056">Free</span>
            <span class="home-text057">
              Unlimited lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed doliqua.
            </span>
            <div class="home-get-started5 template-button">
              <span class="home-text058">Start for free</span>
            </div>
            <span class="home-text059">What&apos;s included</span>
            <div class="home-bullet-points">
              <div class="home-point">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon06">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text060">Sed ut pespiciatis unde omnis</span>
              </div>
              <div class="home-point01">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon08">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text061">Sed ut pespiciatis unde omnis</span>
              </div>
            </div>
          </div>
          <div class="home-card1">
            <span class="home-text062">Pay as you go</span>
            <span class="home-text063">
              <span>Launch your lorem for $49/mo</span>
              <br />
              <span>lorem ipsum dolor sit amet, consectetur adipiscing.</span>
            </span>
            <div class="home-get-started6 template-button">
              <span class="home-text067">
                <span>Upgrade now</span>
                <br />
              </span>
            </div>
            <span class="home-text070">What&apos;s included</span>
            <div class="home-bullet-points1">
              <div class="home-point02">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon10">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text071">Sed ut pespiciatis unde omnis</span>
              </div>
              <div class="home-point03">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon12">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text072">Sed ut pespiciatis unde omnis</span>
              </div>
              <div class="home-point04">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon14">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text073">Sed ut pespiciatis unde omnis</span>
              </div>
              <div class="home-point05">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon16">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text074">Sed ut pespiciatis unde omnis</span>
              </div>
            </div>
          </div>
          <div class="home-card2">
            <span class="home-text075">Enterprise</span>
            <span class="home-text076">
              <span>
                Custom-built lorem ipsum dolor sit amet, consectetur adipiscing
                elit, sed doliqua.
              </span>
              <br />
            </span>
            <div class="home-get-started7 template-button">
              <span class="home-text079">
                <span>Contact us</span>
                <br />
              </span>
            </div>
            <span class="home-text082">What&apos;s included</span>
            <div class="home-bullet-points2">
              <div class="home-point06">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon18">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text083">Sed ut pespiciatis unde omnis</span>
              </div>
              <div class="home-point07">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon20">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text084">Sed ut pespiciatis unde omnis</span>
              </div>
              <div class="home-point08">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon22">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text085">Sed ut pespiciatis unde omnis</span>
              </div>
              <div class="home-point09">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon24">
                  <path
                    d="M877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
                <span class="home-text086">Sed ut pespiciatis unde omnis</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="home-testimonals">
      <div class="home-left3">
        <span class="home-text087">Testimonals</span>
        <span class="home-text088 title">What people say about Active</span>
      </div>
      <div class="home-right2">
        <div class="home-column">
          <app-testimonal
            Quote='"Pellentesque sodales libero nulla, ac imperdiet ante tincidunt vel. Fusce auctor augue sed massa finibus, et dictum sem mollis. In luctus.”'
            Avatar_src="/playground_assets/image552912-e3yq-200h.png"
          ></app-testimonal>
          <app-testimonal
            From="Social Club"
            name="Jessica Smith"
            Quote="“Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo.  Inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.”"
            Avatar_src="/playground_assets/image312912-mvsg-200h.png"
          ></app-testimonal>
          <app-testimonal
            From="BeMe"
            name="Logan Boy"
            Quote="“Totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo..”"
            Avatar_src="/playground_assets/image502912-6wy-200h.png"
          ></app-testimonal>
          <app-testimonal
            From="Hello W."
            name="Laraine Summers"
            Quote="“Rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae.”"
            Avatar_src="/playground_assets/image202912-zekh-200h.png"
          ></app-testimonal>
        </div>
        <div class="home-column1">
          <app-testimonal
            From="Handsly"
            name="William McPau"
            Quote='"Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.”'
            Avatar_src="/playground_assets/image572912-0d3-200h.png"
          ></app-testimonal>
          <app-testimonal
            From="Share"
            name="Mariah Mae"
            Quote="“Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.”"
            Avatar_src="/playground_assets/image632913-swij-200h.png"
          ></app-testimonal>
          <app-testimonal
            From="Gather"
            name="John Finati"
            Quote='"Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.”'
            Avatar_src="/playground_assets/image102913-x4z8-200h.png"
          ></app-testimonal>
          <app-testimonal
            From="Zigo"
            name="Mary Pau"
            Quote='"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. ”'
            Avatar_src="/playground_assets/image562913-ycff-200h.png"
          ></app-testimonal>
        </div>
      </div>
      <span class="home-text089">
        <span>Show more</span>
        <br />
      </span>
    </section>
    <section class="home-action-bar">
      <div class="home-action">
        <div class="home-heading3">
          <span class="home-text092 title">
            <span>Get traffic now </span>
            <br />
            <span>with AI Lekhi!</span>
          </span>
          <span class="home-text096">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          </span>
          <div class="home-get-started8 template-button">
            <span class="home-text097">
              <span>Start free</span>
              <br />
            </span>
          </div>
        </div>
        <div class="home-images">
          <img
            alt="image"
            src="/playground_assets/e564eaa3c4fab71792794d666a281742-1200w.png"
            class="home-image1"
          />
        </div>
      </div>
    </section>
    <section class="home-faq">
      <div class="home-heading4">
        <span class="home-text100 title">Frequently asked questions</span>
        <span class="home-text101">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. vv
        </span>
      </div>
      <div class="home-accordion">
        <div data-faq="closed" class="accordionContainer">
          <div class="home-header1">
            <span class="home-text102">
              — What is sit amet, consectetur adipiscing elit, sed do?
              <span v-html="rawrylq"></span>
            </span>
            <svg viewBox="0 0 1024 1024" class="accordionIcon">
              <path d="M316 366l196 196 196-196 60 60-256 256-256-256z"></path>
            </svg>
          </div>
          <div class="accordionContent">
            <span class="home-text103">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
              officia deserunt mollit anim id est laborum.
              <span v-html="rawfza4"></span>
            </span>
          </div>
        </div>
        <div class="accordionContainer">
          <div class="home-header2">
            <span class="home-text104">
              — Why is dolore magna aliqua excepteur sint
            </span>
            <svg viewBox="0 0 1024 1024" class="accordionIcon">
              <path d="M316 366l196 196 196-196 60 60-256 256-256-256z"></path>
            </svg>
          </div>
          <div class="accordionContent">
            <span class="home-text105">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
              officia deserunt mollit anim id est laborum.
              <span v-html="rawpei5"></span>
            </span>
          </div>
        </div>
        <div data-faq="closed" class="accordionContainer">
          <div class="home-header3">
            <span class="home-text106">
              — Is excepteur sint occaecat cupidatat non proident, sunt in culpa
              qui officia deserunt mollit anim id est laborum?
              <span v-html="rawm9c7"></span>
            </span>
            <svg viewBox="0 0 1024 1024" class="accordionIcon">
              <path d="M316 366l196 196 196-196 60 60-256 256-256-256z"></path>
            </svg>
          </div>
          <div class="accordionContent">
            <span class="home-text107">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
              officia deserunt mollit anim id est laborum.
              <span v-html="rawyfti"></span>
            </span>
          </div>
        </div>
        <div data-faq="closed" class="accordionContainer">
          <div class="home-header4">
            <span class="home-text108">
              — Who quasi architecto beatae vitae dicta sunt explicabo. Nemo enim
              ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit,
              sed quia consequuntur magni
              <span v-html="rawv0tv"></span>
            </span>
            <svg viewBox="0 0 1024 1024" class="accordionIcon">
              <path d="M316 366l196 196 196-196 60 60-256 256-256-256z"></path>
            </svg>
          </div>
          <div class="accordionContent">
            <span class="home-text109">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
              officia deserunt mollit anim id est laborum.
              <span v-html="rawconb"></span>
            </span>
          </div>
        </div>
        <div data-faq="closed" class="accordionContainer">
          <div class="home-header5">
            <span class="home-text110">
              — Is minim veniam quis nostrud exercitation ullamco laboris nisi ut
              aliquip ex ea commodo consequat.
            </span>
            <svg viewBox="0 0 1024 1024" class="accordionIcon">
              <path d="M316 366l196 196 196-196 60 60-256 256-256-256z"></path>
            </svg>
          </div>
          <div class="accordionContent">
            <span class="home-text111">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
              officia deserunt mollit anim id est laborum.
              <span v-html="rawqs5m"></span>
            </span>
          </div>
        </div>
      </div>
      <div>
        <DangerousHTML
          html="<script>
  // Accordion - Code Embed
  
  const accordionContainers = document.querySelectorAll('.accordionContainer'); // All accordion containers
  const accordionContents = document.querySelectorAll('.accordionContent'); // All accordion content
  const accordionIcons = document.querySelectorAll('.accordionIcon'); // All accordion icons
  
  accordionContents.forEach((accordionContent) => {
      accordionContent.style.display = 'none'; //Hides all accordion contents
  });
  
  accordionContainers.forEach((accordionContainer, index) => {
      accordionContainer.addEventListener('click', () => {
          accordionContents.forEach((accordionContent) => {
              accordionContent.style.display = 'none'; //Hides all accordion contents
          });
  
          accordionIcons.forEach((accordionIcon) => {
              accordionIcon.style.transform = 'rotate(0deg)'; // Resets all icon transforms to 0deg (default)
          });
  
          if (accordionContainer.classList.contains('accordion-open')) { // Checks if this container has class 'accordion-open'
              accordionContainer.classList.remove('accordion-open'); // Removes class 'accordion-open'
          } else {
              accordionContainers.forEach((accordionContainer) => {
                  accordionContainer.classList.remove('accordion-open'); // Removes class 'accordion-open' from all containers
              });
  
              accordionContainer.classList.add('accordion-open'); // Adds class 'accordion-open' to this container
              accordionContents[index].style.display = 'flex'; // Shows accordion content
              accordionIcons[index].style.transform = 'rotate(180deg)'; // Rotates accordion icon 180deg
          }
      });
  });
  
  /*
  Here's what the above is doing:
      1. Selects all accordion containers, contents, and icons
      2. Hides all accordion contents
      3. Adds an event listener to each accordion container
      4. When an accordion container is clicked, it:
          - Hides all accordion contents
          - Resets all icon transforms to 0deg (default)
          - Checks if this container has class 'accordion-open'
              - If it does, it removes class 'accordion-open'
              - If it doesn't, it:
                  - Removes class 'accordion-open' from all containers
                  - Adds class 'accordion-open' to this container
                  - Shows accordion content
                  - Rotates accordion icon 180deg
  */
  </script>"
        ></DangerousHTML>
      </div>
    </section>
    <footer class="home-footer">
      <div class="home-top">
        <div class="home-left4">
          <span class="home-text112">Subscribe to our newsletter</span>
          <div class="home-subscription">
            <input
              type="email"
              placeholder="Enter your email"
              class="home-textinput input"
            />
            <div class="home-subscribe">
              <span class="home-text113">Subscribe</span>
            </div>
          </div>
          <span class="home-text114">
            By subscribing to our newsletter you agree with our Terms and
            Conditions.
          </span>
          <div class="home-contact">
            <span class="home-text115">Contact</span>
            <a href="mailto:use@active-app.com?subject=Support" class="home-link">
              use@active-app.com
            </a>
          </div>
        </div>
        <div class="home-right3">
          <div class="home-category5">
            <span class="home-text116">Solutions</span>
            <div class="home-links2">
              <span class="home-text117">Responsive Web Design</span>
              <span class="home-text118">Responsive Prototypesv</span>
              <span class="home-text119">Design to Code</span>
              <span class="home-text120">Static Website Builder</span>
              <span class="home-text121">Static Website Generator</span>
            </div>
          </div>
          <div class="home-category6">
            <span class="home-text122">Company</span>
            <div class="home-links3">
              <span class="home-text123">About</span>
              <span class="home-text124">Team</span>
              <span class="home-text125">News</span>
              <span class="home-text126">Partners</span>
              <span class="home-text127">Careers</span>
              <span class="home-text128">Press &amp; Media</span>
            </div>
          </div>
          <div class="home-category7">
            <span class="home-text129">Solutions</span>
            <div class="home-links4">
              <span class="home-text130">Twitter</span>
              <span class="home-text131">Linkedin</span>
              <span class="home-text132">Crunchbase</span>
              <span class="home-text133">Instagram</span>
              <span class="home-text134">Facebook</span>
            </div>
          </div>
        </div>
      </div>
      <div class="home-bottom">
        <img
          alt="pastedImage"
          src="/playground_assets/pastedimage-no9b-1500h.png"
          class="home-branding"
        />
        <span class="home-text135">Copyright © Active - 2022</span>
      </div>
    </footer>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.mjs'

import ActiveUsers from '../components/active-users'
import YouTube from '../components/you-tube'
import AppTestimonal from '../components/testimonal'

export default {
  name: 'Home',
  components: {
    DangerousHTML,
    ActiveUsers,
    YouTube,
    AppTestimonal,
  },
  data() {
    return {
      rawin6n: ' ',
      rawxkkm: ' ',
      rawopp6: ' ',
      rawrylq: ' ',
      rawfza4: ' ',
      rawpei5: ' ',
      rawm9c7: ' ',
      rawyfti: ' ',
      rawv0tv: ' ',
      rawconb: ' ',
      rawqs5m: ' ',
    }
  },
  head: {
    title: 'AI Lekhi',
    meta: [
      {
        property: 'og:title',
        content: 'AI Lekhi',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  overflow-x: hidden;
  flex-direction: column;
}
.home-hero {
  width: 100%;
  height: 1000px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  background-color: #5228F5;
}
.home-menu {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-mobile-navigation {
  top: 0px;
  flex: 0 0 auto;
  left: 0px;
  width: 100vw;
  height: 100vh;
  display: flex;
  z-index: 150;
  position: fixed;
  transform: translateX(100%);
  transition: transform 0.3s;
  align-items: flex-start;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  background-color: var(--dl-color-gray-white);
}
.home-logo {
  width: 64px;
}
.home-links {
  gap: var(--dl-space-space-twounits);
  display: flex;
  margin-top: var(--dl-space-space-twounits);
  align-items: flex-start;
  flex-direction: column;
}
.home-close-mobile-menu {
  top: var(--dl-space-space-oneandhalfunits);
  right: var(--dl-space-space-oneandhalfunits);
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-icon {
  width: 24px;
  height: 24px;
  display: flex;
}
.home-desktop-navigation {
  width: 100%;
  display: flex;
  margin-top: var(--dl-space-space-oneandhalfunits);
  align-items: center;
  flex-direction: column;
}
.home-centered {
  width: 100%;
  display: flex;
  max-width: 1200px;
  box-sizing: initial;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 50px;
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: row;
  justify-content: space-between;
  background-color: #ffffff;
}
.home-left {
  height: 100%;
  display: flex;
  align-items: center;
  padding-top: 38px;
  flex-direction: row;
  padding-bottom: 38px;
}
.home-logo1 {
  width: 219px;
  height: 28px;
  margin-left: var(--dl-space-space-halfunit);
}
.home-links1 {
  display: flex;
  align-items: center;
  margin-left: 33px;
  flex-direction: row;
}
.home-right {
  height: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-sign-in {
  margin-right: 20px;
}
.home-get-started {
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 56px;
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: #000000;
}
.home-get-started:hover {
  background-color: #5228F5;
}
.home-text006 {
  color: #ffffff;
  font-style: normal;
  font-weight: 600;
}
.home-burger-menu {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-mobile-menu-button {
  width: 40px;
  height: 40px;
  display: none;
}
.home-header {
  display: flex;
  margin-top: 140px;
  align-items: center;
  flex-direction: column;
}
.home-text007 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  text-align: center;
  font-weight: 700;
  line-height: 80px;
}
.home-text008 {
  color: rgb(238, 233, 254);
  font-size: 20px;
  max-width: 600px;
  margin-top: 16px;
  text-align: center;
  line-height: 30px;
}
.home-get-started1 {
  color: white;
  cursor: pointer;
  display: flex;
  margin-top: 40px;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  border-radius: 56px;
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: #000000;
}
.home-get-started1:hover {
  color: black;
  background-color: #ffffff;
}
.home-text009 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-dashboard-preview {
  top: 650px;
  display: flex;
  position: absolute;
  align-items: center;
  border-color: #633df6;
  border-width: 30px;
  border-radius: 100px;
  flex-direction: column;
  background-color: #633df6;
}
.home-outline {
  display: flex;
  align-items: center;
  border-color: #7350f7;
  border-width: 20px;
  border-radius: 70px;
  flex-direction: column;
  background-color: #7350f7;
}
.home-image {
  width: 900px;
  z-index: 10;
  user-select: none;
}
.home-features {
  width: 100%;
  display: flex;
  z-index: 1;
  align-items: center;
  padding-top: 400px;
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  background-color: EFF0F2;
}
.home-title {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text010 {
  font-size: 56px;
  font-style: normal;
  text-align: center;
  font-weight: 700;
  line-height: 72px;
}
.home-text011 {
  font-size: 20px;
  margin-top: 16px;
  text-align: center;
  line-height: 30px;
}
.home-cards {
  width: 100%;
  display: flex;
  max-width: 1200px;
  margin-top: 80px;
  align-items: center;
  flex-direction: column;
}
.home-container1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-icon02 {
  width: 32px;
  height: 30px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text014 {
  font-size: 28px;
  font-style: normal;
  font-weight: 700;
  line-height: 33px;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text015 {
  line-height: 24px;
}
.home-publish {
  height: initial;
}
.home-icon03 {
  width: 30px;
  height: 30px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text016 {
  font-size: 28px;
  font-style: normal;
  font-weight: 700;
  line-height: 33px;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text017 {
  line-height: 24px;
}
.home-container2 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-sixunits);
  flex-direction: row;
}
.home-icon04 {
  width: 35px;
  height: 30px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text018 {
  font-size: 28px;
  font-style: normal;
  font-weight: 700;
  line-height: 33px;
  margin-bottom: 16px;
}
.home-text019 {
  line-height: 24px;
}
.home-icon05 {
  width: 30px;
  height: 30px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text020 {
  font-size: 28px;
  font-style: normal;
  font-weight: 700;
  line-height: 33px;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text021 {
  line-height: 24px;
}
.home-quote-container {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 160px;
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: 160px;
  justify-content: center;
  background-color: #000000;
}
.home-quote {
  width: 100%;
  display: flex;
  max-width: 1200px;
  flex-direction: column;
  justify-content: center;
}
.home-message {
  color: rgb(255, 255, 255);
  font-size: 40px;
  max-width: 800px;
  line-height: 52px;
}
.home-author {
  width: 800px;
  display: flex;
  margin-top: var(--dl-space-space-oneandhalfunits);
  align-items: center;
  flex-direction: row;
}
.home-avatar {
  width: 64px;
  height: 64px;
  object-fit: cover;
  border-radius: 50%;
}
.home-quote1 {
  color: rgb(151, 126, 249);
  width: 100%;
  max-width: 800px;
  margin-left: var(--dl-space-space-unit);
}
.home-text022 {
  font-style: normal;
  font-weight: 600;
}
.home-statistics {
  width: 100%;
  height: 264px;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: row;
  justify-content: center;
  background-color: #5228F5;
}
.home-container3 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-banners {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-banner-manage {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: center;
}
.home-container4 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-left1 {
  flex: 1;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text025 {
  text-align: left;
}
.home-text026 {
  color: rgb(0, 0, 0);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-get-started2 {
  transition: 0.3s;
  margin-bottom: 0;
}
.home-get-started2:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-template-blue-bg);
}
.home-text027 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-image-container {
  flex: 1;
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-cards-image {
  width: 100%;
  height: 100%;
  object-fit: contain;
  user-select: none;
}
.home-banner-advanced-analytics {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: center;
  background-color: #EFF0F2;
}
.home-centered-container {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  justify-content: center;
}
.home-image-container1 {
  flex: 1;
  display: flex;
}
.home-cards-image1 {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.home-right1 {
  flex: 1;
  display: flex;
  margin-left: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text029 {
  text-align: left;
}
.home-category {
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: column;
}
.home-text030 {
  color: rgb(0, 0, 0);
  font-size: 24px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text031 {
  color: rgb(0, 0, 0);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text032 {
  color: #5228F5;
  cursor: pointer;
  font-style: normal;
  transition: 0.3s;
  font-weight: 600;
}
.home-text032:hover {
  color: #000000;
}
.home-category1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text033 {
  color: rgb(0, 0, 0);
  font-size: 24px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text034 {
  color: rgb(0, 0, 0);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text035 {
  color: #5228F5;
  cursor: pointer;
  font-style: normal;
  transition: 0.3s;
  font-weight: 600;
}
.home-text035:hover {
  color: #000000;
}
.home-banner {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: center;
}
.home-container5 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-left2 {
  flex: 1;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text036 {
  color: rgb(82, 40, 245);
  font-style: normal;
  font-weight: 600;
  margin-bottom: 24px;
}
.home-text037 {
  text-align: left;
}
.home-text038 {
  color: rgb(0, 0, 0);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-get-started3 {
  transition: 0.3s;
  margin-bottom: 0;
}
.home-get-started3:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-template-blue-bg);
}
.home-text039 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-image-container2 {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-cards-image2 {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.home-integrations {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-sevenunits);
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #EFF0F2;
}
.home-centered-container1 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-heading {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text042 {
  color: rgb(0, 0, 0);
  text-align: center;
  margin-bottom: var(--dl-space-space-fiveunits);
}
.home-pills-container {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-pills {
  width: 100%;
  display: flex;
  grid-gap: var(--dl-space-space-twounits);
  flex-wrap: wrap;
  margin-bottom: var(--dl-space-space-threeunits);
  flex-direction: row;
  justify-content: center;
}
.home-container6 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: center;
}
.home-container7 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  flex-wrap: wrap;
  margin-left: var(--dl-space-space-fiveunits);
  flex-direction: row;
  justify-content: center;
}
.home-how-it-works {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
  background-color: #211062;
}
.home-centered-container2 {
  width: 100%;
  height: 100%;
  display: flex;
  max-width: 1200px;
  align-items: flex-end;
  flex-direction: column;
  justify-content: space-between;
}
.home-heading1 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-fiveunits);
  flex-direction: column;
}
.home-text043 {
  color: rgb(220, 212, 253);
  font-style: normal;
  font-weight: 600;
  margin-bottom: 24px;
}
.home-text044 {
  color: var(--dl-color-gray-white);
}
.home-category2 {
  color: white;
  width: 100%;
  display: flex;
  overflow: hidden;
  padding-left: var(--dl-space-space-fourunits);
  border-radius: 50px;
  margin-bottom: var(--dl-space-space-threeunits);
  flex-direction: row;
  background-color: #5228F5;
}
.home-headng {
  flex: 1;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-threeunits);
  margin-right: var(--dl-space-space-fourunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-threeunits);
  justify-content: center;
}
.home-text045 {
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: 16px;
}
.home-text046 {
  color: #EEE9FE;
  line-height: 24px;
  margin-bottom: 40px;
}
.home-get-started4 {
  margin-bottom: 0px;
}
.home-get-started4:hover {
  color: black;
  background-color: #ffffff;
}
.home-text047 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-container8 {
  flex: 1;
  height: 100%;
  display: flex;
  align-self: flex-end;
  flex-direction: row;
}
.home-pasted-image {
  flex: 0 0 auto;
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.home-row {
  display: flex;
  grid-gap: var(--dl-space-space-threeunits);
  align-items: center;
  flex-direction: row;
}
.home-category3 {
  flex: 1;
  color: white;
  height: 555px;
  display: flex;
  overflow: hidden;
  align-items: flex-end;
  border-radius: 50px;
  flex-direction: column;
  justify-content: space-between;
  background-color: #ffffff;
}
.home-headng1 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-fourunits);
  flex-direction: column;
  padding-bottom: 0px;
}
.home-text048 {
  color: rgb(0, 0, 0);
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: 16px;
}
.home-text049 {
  color: #1E1E1E;
  line-height: 24px;
}
.home-pasted-image1 {
  width: 100%;
}
.home-category4 {
  flex: 1;
  color: white;
  height: 555px;
  display: flex;
  overflow: hidden;
  align-items: flex-end;
  border-radius: 50px;
  flex-direction: column;
  justify-content: space-between;
  background-color: #000000;
}
.home-headng2 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-fourunits);
  flex-direction: column;
  padding-bottom: 0px;
}
.home-text050 {
  color: #ffffff;
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: 16px;
}
.home-text051 {
  color: rgb(238, 233, 254);
  line-height: 24px;
}
.home-pasted-image2 {
  width: 100%;
  object-fit: contain;
}
.home-pricing {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: center;
  background-color: #5228F5;
}
.home-centered-container3 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-heading2 {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text052 {
  color: var(--dl-color-gray-white);
  text-align: center;
}
.home-text053 {
  color: rgb(238, 233, 254);
  width: 600px;
  text-align: center;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-selection {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-text054 {
  color: #EEE9FE;
  width: 128px;
  font-style: normal;
  text-align: center;
  font-weight: 600;
  padding-top: var(--dl-space-space-oneandhalfunits);
  border-color: rgba(255, 255, 255, 0.3);
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  border-bottom-width: 2px;
}
.home-text055 {
  color: #ffffff;
  width: 128px;
  font-style: normal;
  text-align: center;
  font-weight: 600;
  padding-top: var(--dl-space-space-oneandhalfunits);
  border-color: #ffffff;
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  border-bottom-width: 2px;
}
.home-cards1 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  margin-top: var(--dl-space-space-fiveunits);
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
  grid-template-columns: 1fr 1fr 1fr;
}
.home-card {
  flex: 1;
  height: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: var(--dl-space-space-threeunits);
  border-radius: 50px;
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: flex-start;
  background-color: #ffffff;
}
.home-text056 {
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text057 {
  color: rgb(0, 0, 0);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-fourunits);
}
.home-get-started5 {
  transition: 0.3s;
}
.home-get-started5:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-template-blue-bg);
}
.home-text058 {
  font-size: 18px;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
.home-text059 {
  font-size: 15px;
  font-style: normal;
  font-weight: 600;
  line-height: 27px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-bullet-points {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-point {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon06 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text060 {
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-point01 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon08 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text061 {
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-card1 {
  flex: 1;
  height: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: 40px;
  border-radius: 50px;
  padding-right: 40px;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: flex-start;
  background-color: #ffffff;
}
.home-text062 {
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text063 {
  color: rgb(0, 0, 0);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-fourunits);
}
.home-get-started6 {
  transition: 0.3s;
}
.home-get-started6:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-template-blue-bg);
}
.home-text067 {
  font-size: 18px;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
.home-text070 {
  font-size: 15px;
  font-style: normal;
  font-weight: 600;
  line-height: 27px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-bullet-points1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-point02 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon10 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text071 {
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-point03 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon12 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text072 {
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-point04 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon14 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text073 {
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-point05 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon16 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text074 {
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-card2 {
  flex: 1;
  height: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: 40px;
  border-radius: 50px;
  padding-right: 40px;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: flex-start;
  background-color: #000000;
}
.home-text075 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text076 {
  color: rgb(255, 255, 255);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-fourunits);
}
.home-get-started7 {
  color: var(--dl-color-gray-black);
  transition: 0.3s;
  background-color: #ffffff;
}
.home-get-started7:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-template-blue-bg);
}
.home-text079 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-text082 {
  color: #ffffff;
  font-size: 15px;
  font-style: normal;
  font-weight: 600;
  line-height: 27px;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-bullet-points2 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-point06 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon18 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text083 {
  color: #ffffff;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-point07 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon20 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text084 {
  color: #ffffff;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-point08 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon22 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text085 {
  color: #ffffff;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-point09 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
}
.home-icon24 {
  fill: #5228F5;
  width: 8px;
  height: 8px;
}
.home-text086 {
  color: #ffffff;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  margin-left: var(--dl-space-space-halfunit);
}
.home-testimonals {
  width: 100%;
  display: flex;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: center;
}
.home-left3 {
  width: 375px;
  display: flex;
  margin-top: 375px;
  align-items: flex-start;
  margin-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-text087 {
  color: rgb(82, 40, 245);
  font-style: normal;
  font-weight: 600;
  margin-bottom: 24px;
}
.home-text088 {
  text-align: left;
}
.home-right2 {
  gap: 40px;
  display: flex;
  flex-direction: row;
}
.home-column {
  gap: 40px;
  display: flex;
  flex-direction: column;
}
.home-column1 {
  gap: 40px;
  display: flex;
  flex-direction: column;
}
.home-text089 {
  cursor: pointer;
  display: none;
}
.home-action-bar {
  width: 100%;
  display: flex;
  padding: 120px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-action {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: flex-end;
  border-radius: 50px;
  flex-direction: row;
  justify-content: space-between;
  background-color: #5228F5;
}
.home-heading3 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-sevenunits);
  padding-left: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sevenunits);
}
.home-text092 {
  color: var(--dl-color-gray-white);
  text-align: left;
}
.home-text096 {
  color: #EEE9FE;
  line-height: 24px;
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-get-started8 {
  margin-bottom: 0px;
}
.home-text097 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-images {
  display: flex;
  align-items: flex-end;
  flex-direction: row;
  justify-content: space-between;
}
.home-image1 {
  width: 100%;
  object-fit: cover;
  user-select: none;
}
.home-faq {
  width: 100%;
  display: flex;
  padding: 120px;
  align-items: center;
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
  background-color: #EFF0F2;
}
.home-heading4 {
  width: 100%;
  display: flex;
  align-items: center;
  user-select: none;
  flex-direction: column;
}
.home-text100 {
  text-align: center;
}
.home-text101 {
  color: rgb(0, 0, 0);
  width: 100%;
  max-width: 600px;
  text-align: center;
  margin-bottom: var(--dl-space-space-fiveunits);
}
.home-accordion {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-header1 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.home-text102 {
  width: 100%;
  font-size: 20px;
  max-width: 760px;
  font-style: normal;
  font-weight: 500;
}
.home-text103 {
  width: 100%;
  max-width: 760px;
  line-height: 24px;
}
.home-header2 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.home-text104 {
  width: 100%;
  font-size: 20px;
  max-width: 760px;
  font-style: normal;
  font-weight: 500;
}
.home-text105 {
  width: 100%;
  max-width: 760px;
  line-height: 24px;
}
.home-header3 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.home-text106 {
  width: 100%;
  font-size: 20px;
  max-width: 760px;
  font-style: normal;
  font-weight: 500;
}
.home-text107 {
  width: 100%;
  max-width: 760px;
  line-height: 24px;
}
.home-header4 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.home-text108 {
  width: 100%;
  font-size: 20px;
  max-width: 760px;
  font-style: normal;
  font-weight: 500;
}
.home-text109 {
  width: 100%;
  max-width: 760px;
  line-height: 24px;
}
.home-header5 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.home-text110 {
  width: 100%;
  font-size: 20px;
  max-width: 760px;
  font-style: normal;
  font-weight: 500;
}
.home-text111 {
  width: 100%;
  max-width: 760px;
  line-height: 24px;
}
.home-footer {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sevenunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sevenunits);
  background-color: #000000;
}
.home-top {
  width: 100%;
  display: flex;
  max-width: 1200px;
  border-color: #3B3B3B;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: space-between;
  border-bottom-width: 1px;
}
.home-left4 {
  width: 33%;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-twounits);
  flex-direction: column;
}
.home-text112 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-subscription {
  width: 100%;
  height: 66px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 50px;
  margin-bottom: var(--dl-space-space-unit);
  padding-right: var(--dl-space-space-halfunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: space-between;
  background-color: #ffffff;
}
.home-textinput {
  width: 60%;
  outline: none;
  font-size: 14px;
  border-width: 0px;
}
.home-subscribe {
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  padding-top: 16px;
  padding-left: 32px;
  border-radius: 56px;
  padding-right: 32px;
  flex-direction: row;
  padding-bottom: 16px;
  justify-content: flex-start;
  background-color: #5228F5;
}
.home-subscribe:hover {
  background-color: #000;
}
.home-text113 {
  color: #ffffff;
  font-size: 14px;
  font-style: normal;
  font-weight: 600;
}
.home-text114 {
  color: #686868;
  font-size: 14px;
}
.home-contact {
  display: flex;
  margin-top: 52px;
  align-items: flex-start;
  flex-direction: column;
}
.home-text115 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-unit);
}
.home-link {
  color: #C4C4C4;
  font-size: 14px;
  text-decoration: underline;
}
.home-right3 {
  gap: var(--dl-space-space-fiveunits);
  display: flex;
  flex-wrap: wrap;
  margin-top: var(--dl-space-space-threeunits);
  flex-direction: row;
  justify-content: flex-start;
}
.home-category5 {
  width: 240px;
  display: flex;
  align-items: stretch;
  flex-direction: column;
}
.home-text116 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-unit);
}
.home-links2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text117 {
  color: rgb(196, 196, 196);
  cursor: pointer;
  font-size: 14px;
}
.home-text118 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text119 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text120 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text121 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-category6 {
  width: 240px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text122 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-unit);
}
.home-links3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text123 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text124 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text125 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text126 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text127 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text128 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-category7 {
  width: 240px;
  display: flex;
  flex-direction: column;
}
.home-text129 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-unit);
}
.home-links4 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text130 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text131 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text132 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text133 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-text134 {
  color: rgb(196, 196, 196);
  font-size: 14px;
}
.home-bottom {
  width: 100%;
  display: flex;
  max-width: 1200px;
  margin-top: var(--dl-space-space-threeunits);
  align-items: flex-start;
  user-select: none;
  flex-direction: column;
}
.home-branding {
  width: var(--dl-size-size-large);
  filter: invert(100%) sepia(0%) saturate(0%) hue-rotate(93deg) brightness(103%) contrast(103%);;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text135 {
  color: #686868;
  font-size: 14px;
  line-height: 30px;
}
@media(max-width: 991px) {
  .home-hero {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-close-mobile-menu {
    align-items: center;
    justify-content: center;
  }
  .home-desktop-navigation {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-centered {
    height: 60px;
    padding-left: 10px;
    padding-right: 10px;
  }
  .home-left {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-logo1 {
    width: 64px;
  }
  .home-links1 {
    display: none;
  }
  .home-sign-in {
    display: none;
  }
  .home-get-started {
    display: none;
  }
  .home-mobile-menu-button {
    display: flex;
  }
  .home-header {
    width: 100%;
    max-width: 1200px;
  }
  .home-image {
    width: 100%;
  }
  .home-features {
    padding-top: 260px;
  }
  .home-title {
    width: 100%;
    max-width: 1200px;
  }
  .home-text010 {
    font-size: 36px;
    line-height: 40px;
  }
  .home-text011 {
    font-size: 20px;
    margin-top: var(--dl-space-space-unit);
    line-height: 30px;
  }
  .home-cards {
    margin-top: var(--dl-space-space-fiveunits);
  }
  .home-text015 {
    line-height: 21px;
  }
  .home-text017 {
    line-height: 21px;
  }
  .home-text019 {
    line-height: 21px;
  }
  .home-text020 {
    font-size: 24px;
  }
  .home-text021 {
    line-height: 21px;
  }
  .home-quote-container {
    padding-top: var(--dl-space-space-sevenunits);
    padding-bottom: var(--dl-space-space-sevenunits);
  }
  .home-message {
    width: 100%;
    max-width: 800px;
  }
  .home-author {
    width: 100%;
    max-width: 800px;
  }
  .home-statistics {
    height: 800px;
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-container3 {
    height: 100%;
    flex-direction: column;
  }
  .home-banner-manage {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-left1 {
    margin-right: var(--dl-space-space-threeunits);
  }
  .home-cards-image {
    width: 360px;
  }
  .home-banner-advanced-analytics {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-container7 {
    margin-left: 0px;
  }
  .home-category2 {
    padding-left: 0px;
    margin-bottom: var(--dl-space-space-threeunits);
    flex-direction: column;
  }
  .home-headng {
    margin-left: var(--dl-space-space-fourunits);
  }
  .home-container8 {
    width: 100%;
  }
  .home-pasted-image {
    height: auto;
  }
  .home-headng1 {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-fourunits);
    padding-right: var(--dl-space-space-fourunits);
  }
  .home-headng2 {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-fourunits);
    padding-right: var(--dl-space-space-fourunits);
  }
  .home-text053 {
    width: 100%;
    max-width: 600px;
  }
  .home-cards1 {
    display: flex;
    flex-direction: column;
  }
  .home-card {
    width: 100%;
    align-items: flex-start;
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-text057 {
    font-size: 16px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-text059 {
    font-size: 16px;
  }
  .home-card1 {
    width: 100%;
    align-items: flex-start;
  }
  .home-card2 {
    width: 100%;
    align-items: flex-start;
  }
  .home-testimonals {
    align-items: center;
    flex-direction: column;
  }
  .home-left3 {
    margin-top: 0px;
    align-items: center;
    margin-bottom: ThreeUnits;
  }
  .home-text088 {
    font-size: 36px;
    text-align: center;
    line-height: 40px;
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-right2 {
    gap: var(--dl-space-space-oneandhalfunits);
    flex-direction: row;
  }
  .home-column {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-column1 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-action {
    flex-direction: column;
  }
  .home-heading3 {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-text092 {
    font-size: 36px;
    line-height: 36px;
  }
  .home-accordion {
    width: 100%;
    max-width: 1200px;
  }
  .home-footer {
    padding: var(--dl-space-space-sixunits);
  }
  .home-top {
    flex-direction: column;
  }
  .home-left4 {
    width: 100%;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-text114 {
    color: rgb(104, 104, 104);
    font-size: 14px;
  }
  .home-text115 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-link {
    text-decoration: underline none;
  }
  .home-right3 {
    gap: var(--dl-space-space-twounits);
    flex-direction: column;
  }
  .home-links2 {
    gap: var(--dl-space-space-unit);
  }
  .home-links3 {
    gap: var(--dl-space-space-unit);
  }
  .home-links4 {
    gap: var(--dl-space-space-unit);
  }
  .home-branding {
    width: var(--dl-size-size-medium);
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .home-text135 {
    font-size: 12px;
    line-height: 25px;
    margin-bottom: 0px;
  }
}
@media(max-width: 767px) {
  .home-hero {
    height: 620px;
    position: relative;
    padding-bottom: 180px;
    background-color: var(--dl-color-template-blue-bg);
  }
  .home-desktop-navigation {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-centered {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-left {
    margin-left: var(--dl-space-space-unit);
  }
  .home-right {
    margin-right: var(--dl-space-space-unit);
  }
  .home-sign-in {
    display: none;
  }
  .home-get-started {
    display: none;
  }
  .home-header {
    height: 100%;
    margin-top: var(--dl-space-space-fourunits);
    justify-content: center;
  }
  .home-text007 {
    color: rgb(255, 255, 255);
    font-size: 32px;
    font-style: normal;
    font-weight: 700;
    line-height: 36px;
  }
  .home-text008 {
    color: rgb(238, 233, 254);
    font-size: 16px;
    margin-top: var(--dl-space-space-unit);
    line-height: 24px;
  }
  .home-get-started1 {
    margin-top: var(--dl-space-space-twounits);
  }
  .home-dashboard-preview {
    top: 520px;
    width: 90%;
    border-width: 10px;
    border-radius: 45px;
  }
  .home-outline {
    border-width: 10px;
    border-radius: 35px;
  }
  .home-image {
    width: 100%;
  }
  .home-features {
    padding-top: 350px;
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-text010 {
    font-size: 36px;
    font-style: normal;
    font-weight: 700;
    line-height: 40px;
  }
  .home-container1 {
    gap: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
    flex-direction: column;
  }
  .home-text014 {
    font-size: 24px;
  }
  .home-text015 {
    font-size: 14px;
  }
  .home-publish {
    margin-left: 0px;
  }
  .home-text016 {
    font-size: 24px;
  }
  .home-text017 {
    font-size: 14px;
  }
  .home-container2 {
    gap: var(--dl-space-space-oneandhalfunits);
    flex-direction: column;
  }
  .home-analyze {
    margin-right: 0px;
  }
  .home-text018 {
    font-size: 24px;
  }
  .home-text019 {
    font-size: 14px;
  }
  .home-text021 {
    font-size: 14px;
  }
  .home-quote-container {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-message {
    font-size: 24px;
    line-height: 31px;
  }
  .home-author {
    width: 100%;
  }
  .home-avatar {
    width: 40px;
    height: 40px;
  }
  .home-quote1 {
    font-size: 14px;
    max-width: 800px;
  }
  .home-statistics {
    height: 100%;
  }
  .home-container3 {
    gap: var(--dl-space-space-fourunits);
    justify-content: center;
  }
  .home-banner-manage {
    padding-top: var(--dl-space-space-fourunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-container4 {
    flex-direction: column;
  }
  .home-left1 {
    margin-right: 0px;
  }
  .home-text025 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text026 {
    line-height: 24px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-text027 {
    font-size: 16px;
  }
  .home-image-container {
    justify-content: center;
  }
  .home-cards-image {
    margin-top: var(--dl-space-space-threeunits);
  }
  .home-banner-advanced-analytics {
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-centered-container {
    flex-direction: column-reverse;
  }
  .home-right1 {
    margin-left: 0px;
  }
  .home-text029 {
    font-size: 28px;
    text-align: left;
    line-height: 26px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-text030 {
    font-size: 20px;
  }
  .home-text031 {
    line-height: 24px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text033 {
    font-size: 20px;
  }
  .home-text034 {
    line-height: 24px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-banner {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-container5 {
    flex-direction: column;
  }
  .home-left2 {
    margin-right: 0px;
  }
  .home-integrations {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-text042 {
    line-height: 24px;
  }
  .home-pills {
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-how-it-works {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-heading1 {
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-text044 {
    margin-bottom: 0px;
  }
  .home-headng {
    padding-bottom: 0px;
  }
  .home-get-started4 {
    display: none;
  }
  .home-container8 {
    width: 100%;
  }
  .home-row {
    height: auto;
    flex-direction: column;
  }
  .home-pricing {
    width: 100%;
    padding-left: var(--dl-space-space-fourunits);
    padding-right: var(--dl-space-space-fourunits);
  }
  .home-card {
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-text056 {
    font-size: 28px;
  }
  .home-card1 {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-text062 {
    font-size: 28px;
  }
  .home-card2 {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-text075 {
    font-size: 28px;
  }
  .home-testimonals {
    padding-left: var(--dl-space-space-fourunits);
    padding-right: var(--dl-space-space-fourunits);
    padding-bottom: 0px;
  }
  .home-right2 {
    width: 100%;
    flex-direction: column;
  }
  .home-column1 {
    display: none;
  }
  .home-text089 {
    display: flex;
    font-style: normal;
    margin-top: var(--dl-space-space-oneandhalfunits);
    font-weight: 600;
  }
  .home-action-bar {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-fourunits);
    padding-right: var(--dl-space-space-fourunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-action {
    align-items: center;
  }
  .home-heading3 {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-text092 {
    font-size: 28px;
    text-align: left;
  }
  .home-text097 {
    color: var(--dl-color-gray-white);
    font-size: 18px;
    font-style: normal;
    font-weight: 600;
  }
  .home-images {
    justify-content: center;
  }
  .home-image1 {
    width: 100%;
  }
  .home-faq {
    padding: var(--dl-space-space-fourunits);
  }
  .home-heading4 {
    width: 100%;
  }
  .home-text100 {
    font-size: 36px;
    line-height: 36px;
  }
  .home-text101 {
    width: 100%;
    max-width: 600p;
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-footer {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
}
@media(max-width: 479px) {
  .home-hero {
    padding-bottom: 160px;
  }
  .home-logo {
    margin-left: 0px;
  }
  .home-icon {
    align-items: center;
    justify-content: center;
  }
  .home-text008 {
    color: #EEE9FE;
  }
  .home-get-started1 {
    width: 100%;
  }
  .home-dashboard-preview {
    top: 500px;
  }
  .home-features {
    padding-top: 200px;
  }
  .home-cards {
    margin-top: var(--dl-space-space-threeunits);
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-container1 {
    gap: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-container2 {
    gap: var(--dl-space-space-oneandhalfunits);
    margin-bottom: 0px;
  }
  .home-analyze {
    margin-bottom: 0px;
  }
  .home-statistics {
    height: 500px;
  }
  .home-text026 {
    line-height: 24px;
  }
  .home-cards-image {
    width: 100%;
    margin-top: var(--dl-space-space-twounits);
  }
  .home-category2 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
    flex-direction: column;
  }
  .home-pricing {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-get-started7 {
    background-color: var(--dl-color-gray-white);
  }
  .home-testimonals {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-action-bar {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-footer {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-subscription {
    padding-top: var(--dl-space-space-halfunit);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-halfunit);
    padding-bottom: var(--dl-space-space-halfunit);
  }
}
</style>
