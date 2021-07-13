<template>
  <div>
    <header>
      <div class="container">
          <nav class="z-depth-0 transparent">
            <div class="nav-wrapper">
              <a href="#!" class="brand-logo left">
                <img src="./assets/images/logo.svg" alt="" class="logo_img">
              </a>
              <a href="#" data-target="mobile-demo" class="sidenav_trigger right">
                <img src="./assets/images/icon-hamburger.svg" class="open_menu" alt="">
                <img src="./assets/images/icon-close-menu.svg" class="close_menu hidden" alt="">
              </a>
              <ul class="right main-nav">
                <li><a href="#">About</a></li>
                <li><a href="#">Discover</a></li>
                <li><a href="#">Get Started</a></li>
              </ul>
            </div>
          </nav>

          <ul class="sidenav hidden z-depth-0" id="mobile-demo">
            <li><a href="#">About</a></li>
            <li><a href="#">Discover</a></li>
            <li><a href="#">Get Started</a></li>
          </ul>
        </div>
    </header>

    <div class="main">

      <div class="main_col">
        <div class="sections white section-1">
          <div class="container">
            <div class="mastercraft">
              <img src="./assets/images/logo-mastercraft.svg" alt="" class="circle">
            </div>
            <div class="content center-align">
              <h1 class="black-text">Mastercraft Bamboo Monitor Riser</h1>
              <p>A beautiful & handcrafted monitor stand to reduce neck and eye strain.</p>
              <div class="modal_section">
                <div class="row valign-wrapper">
                  <div class="col s6 m6 left-align">
                    <FirstModal></FirstModal>
                    <button data-target="modal1" class="btn-large custom-btn modal-trigger" id="back-it">Back this project</button>
                  </div>
                  <div class="col s6 m6 valign-wrapper" id="bookmarked">
                    <svg width="56" height="56" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><circle fill="#2F2F2F" cx="28" cy="28" r="28"/><path fill="#B1B1B1" d="M23 19v18l5-5.058L33 37V19z"/></g></svg>
                    <button class="btn-large custom-btn disabled">
                      <span id="bookmarked-text">Bookmark</span> 
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="sections white section-2">
          <div class="container">
            <div class="row">
              <div class="col s12 m4">
                <h2 class="black-text">$89,914</h2>
                <p>of $100,000 backed</p>
              </div>
              <div class="col s12 m4">
                <h2 class="black-text">5,007</h2>
                <p>total backers</p>
              </div>
              <div class="col s12 m4">
                <h2 class="black-text">56</h2>
                <p>days left</p>
              </div>
            </div>
            <div class="progress-bar grey lighten-3">
              <div class="progress-inner-bar"></div>
            </div>
          </div>
        </div>

        <div class="sections white section-3">
          <div class="container">
            <div>
              <h3 class="title_section3 black-text">About this project</h3>
              <p class="text">The Mastercraft Bamboo Monitor Riser is a sturdy and stylish platform that elevates your screen to a more comfortable viewing height. Placing your monitor at eye level has the potential to improve 
                your posture and make you more comfortable while at work, helping you stay focused on the task at hand.</p>
              <p class="text">Featuring artisan craftsmanship, the simplicity of design creates extra desk space below your computer to allow notepads, pens, and USB sticks to be stored under the stand.</p>
            </div>

            <div class="sub-section">
              <div class="container">
                <div class="row">
                  <div class="col s12 m6">
                    <h4 class="black-text">Bamboo Stand</h4>
                  </div>
                  <div class="col s12 m6">
                    <p class="pledge right">Pledge $25 or more</p>
                  </div>
                </div>
                <p class="text">You get an ergonomic stand made of natural bamboo. You've helped us launch our promotional campaign, and you’ll be added to a special Backer member list.</p>
                <div class="row">
                  <div class="col s12 m6">
                    <p class="valign-wrapper"><span class="left">101</span> left</p>
                  </div>
                  <div class="col s12 m6">
                    <button class="btn-small right">Select Reward</button>
                  </div>
                </div>
              </div>
            </div>

            <div class="sub-section">
              <div class="container">
                <div class="row">
                  <div class="col s12 m6">
                    <h4 class="black-text">Black Edition Stand</h4>
                  </div>
                  <div class="col s12 m6">
                    <p class="pledge right">Pledge $75 or more</p>
                  </div>
                </div>
                <p class="text">You get a Black Special Edition computer stand and a personal thank you. You’ll be added to our Backer member list. Shipping is included.</p>
                <div class="row">
                  <div class="col s12 m6">
                    <p class="valign-wrapper"><span class="left">64</span> left</p>
                  </div>
                  <div class="col s12 m6">
                    <button class="btn-small right">Select Reward</button>
                  </div>
                </div>
              </div>
            </div>

            <div class="sub-section out">
              <div class="container">
                <div class="row">
                  <div class="col s12 m6">
                    <h4 class="black-text">Mahogany Special Edition</h4>
                  </div>
                  <div class="col s12 m6">
                    <p class="pledge right">Pledge $200 or more</p>
                  </div>
                </div>
                <p class="text">You get two Special Edition Mahogany stands, a Backer T-Shirt, and a personal thank you. You’ll be added to our Backer member list. Shipping is included.</p>
                <div class="row">
                  <div class="col s12 m6">
                    <p class="valign-wrapper"><span class="left">0</span> left</p>
                  </div>
                  <div class="col s12 m6">
                    <button class="btn-small right disabled">Out of Stock</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<style>
  @import './assets/css/style.css';
</style>

<script>
import FirstModal from './components/Modal1.vue'
/* eslint-env jquery */
export default {
  name: 'App',
  components: {
    FirstModal
  },
  mounted() {
    $(document).ready(function(){
      $('.open_menu').click(function() {
        $(this).hide();
        $('.close_menu').show();
        $('.sidenav').slideToggle('slow')
      })
      
      $('.close_menu').click(function() {
        $(this).hide();
        $('.open_menu').show();
        $('.sidenav').slideToggle('slow')
      })
    }); 
  }
}
</script>
