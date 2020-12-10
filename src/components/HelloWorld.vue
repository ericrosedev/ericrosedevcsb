<template>
  <div class="erd">
    <div class="intro">
      <h1>Hi, I'm Eric 💁🏻‍♂️</h1>

      <p class="leader">I’m a web designer and developer.</p>

      <p>I like building things for the internet that people can enjoy.</p>

      <p>
        I’ve been doing this full time since 2013, before that I was an
        intelligence analyst in the military and an intelligence instructor for
        the department of defense.
      </p>

      <p>
        I love science fiction novels
        <a href="http://www.thehugoawards.org/" target="_blank">📚</a> and short
        stories <a href="https://www.asimovs.com/" target="_blank">📘</a>
        <a href="https://www.analogsf.com/" target="_blank">📕</a> , running
        <a href="https://www.nike.com/nrc-app" target="_blank">🏃‍♂️</a>, 
        maps <a href="https://www.reddit.com/r/MapPorn/" target="_blank">🗺️</a>,
        boats <a v-on:click="showBoatModal" href="#">🛥️</a>, 
        coffee <a href="https://www.traderjoes.com/digin/tag/Coffee/" target="_blank">☕</a>, 
        and taking miss Dakota <a v-on:click="showDogModal" href="#">🐕</a> to the dog park.
      </p>
    </div>

    <h2>Stuff I do</h2>
    <div class="area stuff">
      <section class="design">
        <h3>Design</h3>

        <ul>
          <li style="position: relative">
            <img src="https://twxuu.csb.app/lightbulb_animated.svg" alt="" />
            Ideation
          </li>
          <li>
            <img src="https://twxuu.csb.app/wireframe_animated.svg" alt="" />
            Wireframing
          </li>
          <li>
            <img src="https://twxuu.csb.app/mock_animated.svg" alt="" /> Mocking
          </li>
          <li>
            <div>
              <img src="https://twxuu.csb.app/vector.svg" alt="" />
              <img src="https://twxuu.csb.app/raster.png" alt="" />
            </div>
            Vector &amp; Raster <br />
            Design
          </li>
          <li>
            <div class="dflex-row">
              <img
                src="https://twxuu.csb.app/vector_anim_animated.svg"
                alt=""
              />
              <img
                src="https://twxuu.csb.app/raster_anim_animated.gif"
                alt=""
                class="animated-gif"
              />
            </div>
            Vector &amp; Raster <br />
            Animation
          </li>
          <li>
            <img src="https://twxuu.csb.app/logo.svg" alt="" /> Logo Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/emaildesign_animated.svg" alt="" />
            Email Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/videodesign_animated.svg" alt="" />
            Video Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/generalui_animated.svg" alt="" />
            General UX UI IXD
          </li>
        </ul>
      </section>

      <section class="development">
        <h3>Development</h3>

        <ul>
          <li><img src="https://twxuu.csb.app/html5.svg" alt="" /> HTML5</li>
          <li>
            <img src="https://twxuu.csb.app/htmls.svg" alt="" /> Semantic Markup
          </li>
          <li>
            <img src="https://twxuu.csb.app/htmli.svg" alt="" /> Templating
            &amp; Interpolation
          </li>
          <li><img src="https://twxuu.csb.app/css3.svg" alt="" /> CSS3</li>
          <li>
            <div class="dflex-row">
              <img src="https://twxuu.csb.app/cssf.svg" alt="" />
              <img src="https://twxuu.csb.app/cssg.svg" alt="" />
            </div>
            Flexbox &amp; Grid <br />
            Based design
            <!-- <pre><code>function Panel(element, canClose, closeHandler) {
                this.element = element;
                this.canClose = canClose;
                this.closeHandler = function () { if (closeHandler) closeHandler() };
              }</code></pre> -->
          </li>
          <li>
            <div class="spinme">
              <img src="https://twxuu.csb.app/csstt_animated.svg" alt="" />
            </div>
            Transforms, Transitions, <br />Animations, &amp; Perspectives
          </li>
          <li><img src="https://twxuu.csb.app/es6.svg" alt="" /> ES6</li>
          <li>
            <div>
              <img src="https://twxuu.csb.app/angular.svg" alt="" />
              <img src="https://twxuu.csb.app/vue.svg" alt="" />
              <img src="https://twxuu.csb.app/react.svg" alt="" />
            </div>
            Modern Frontend Frameworks
          </li>
          <li><img src="https://twxuu.csb.app/node.svg" alt="" /> Node</li>
          <li>
            <img
              src="https://twxuu.csb.app/responsivedesign_animated.svg"
              alt=""
            />
            Responsive Layouts
          </li>
          <li>
            <img src="https://twxuu.csb.app/rapidproto_animated.svg" alt="" />
            Rapid Prototyping
          </li>
          <li>
            <img
              src="https://twxuu.csb.app/versioncontrol_animated.svg"
              alt=""
            />
            Version Control
          </li>
          <li>
            <img src="https://twxuu.csb.app/cicd_animated.svg" alt="" /> CI/CD
          </li>
          <li>
            <img src="https://twxuu.csb.app/emaildev_animated.svg" alt="" />
            Email Development
          </li>
          <li>
            <img src="https://twxuu.csb.app/videodev_animated.svg" alt="" />
            Video Development
          </li>
        </ul>
      </section>
    </div>

    <h2>Tools I use</h2>
    <div class="area tools">
      <section>
        <h3>Operating Systems</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/windows.svg" alt="" /> Windows
          </li>
          <li><img src="https://twxuu.csb.app/apple.svg" alt="" /> Mac</li>
        </ul>
      </section>

      <section>
        <h3>Browsers</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/chrome.svg" alt="" /> Chrome</li>
          <li>
            <img src="https://twxuu.csb.app/firefox.svg" alt="" /> FireFox
          </li>
          <li><img src="https://twxuu.csb.app/safari.svg" alt="" /> Safari</li>
          <li><img src="https://twxuu.csb.app/edge.svg" alt="" /> Edge</li>
        </ul>
      </section>

      <section>
        <h3>Graphic Design</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/photoshop.svg" alt="" /> Photoshop
          </li>
          <li>
            <img src="https://twxuu.csb.app/illustrator.svg" alt="" />
            Illustrator
          </li>
        </ul>
      </section>

      <section>
        <h3>Animation</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/svgator.svg" alt="" /> SVGator
          </li>
        </ul>
      </section>

      <section>
        <h3>Prototyping</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/xd.svg" alt="" /> Experience Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/codepen.svg" alt="" /> CodePen
          </li>
          <li>
            <img src="https://twxuu.csb.app/codesandbox.svg" alt="" />
            CodeSandbox
          </li>
        </ul>
      </section>

      <section>
        <h3>CSS Frameworks</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/bootstrap.svg" alt="" /> Bootstrap
          </li>
        </ul>
      </section>

      <section>
        <h3>CSS Preprocessors</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/sass.svg" alt="" /> SASS / SCSS
          </li>
        </ul>
      </section>

      <section>
        <h3>JS Frameworks</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/vue.svg" alt="" /> Vue</li>
        </ul>
      </section>

      <section>
        <h3>3D Frameworks</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/three.svg" alt="" /> ThreeJS</li>
        </ul>
      </section>

      <section>
        <h3>Old School</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/jquery.svg" alt="" /> jQuery</li>
        </ul>
      </section>

      <section>
        <h3>Server Frameworks</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/node.svg" alt="" /> Node / Express
          </li>
        </ul>
      </section>

      <section>
        <h3>IDEs</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/vscode.svg" alt="" /> VS Code</li>
          <li>
            <img src="https://twxuu.csb.app/brackets.svg" alt="" /> Brackets
          </li>
        </ul>
      </section>

      <section>
        <h3>Email Development</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/mjml.svg" alt="" /> MJML</li>
        </ul>
      </section>

      <section>
        <h3>Video Creation</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/aftereffects.svg" alt="" /> After
            Effects
          </li>
          <li>
            <img src="https://twxuu.csb.app/premiere.svg" alt="" /> Premiere
          </li>
        </ul>
      </section>

      <section>
        <h3>3D Modeling</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/maya.svg" alt="" /> Maya</li>
        </ul>
      </section>

      <section>
        <h3>Compression</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/tinypng.svg" alt="" /> TinyPNG
          </li>
          <li><img src="https://twxuu.csb.app/svgomg.svg" alt="" /> SVGOMG</li>
        </ul>
      </section>

      <section>
        <h3>Misc</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/fontawesome.svg" alt="" />
            FontAwesome
          </li>
          <li>
            <img src="https://twxuu.csb.app/responsively.svg" alt="" />
            Responsively
          </li>
        </ul>
      </section>
    </div>

    <h2>Methodologies I subscribe to</h2>
    <div class="area methods">
      <section>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/agile.svg" alt="" /> Agile
            Development
          </li>
          <li>
            <img src="https://twxuu.csb.app/mobile.svg" alt="" /> Mobile
            Conscious Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/usability.svg" alt="" /> Usability
            Testing
          </li>
          <li>
            <img src="https://twxuu.csb.app/udd.svg" alt="" /> User driven
            design
          </li>
          <li>
            <img src="https://twxuu.csb.app/wlb.svg" alt="" /> Work / Life
            Balance
          </li>
        </ul>
      </section>
    </div>

    <transition name="fade">
      <div v-show="showBoat" class="modal">
        <div class="modal-body">
          <img class="modal-close" v-on:click="showBoatModal" src="https://twxuu.csb.app/close.svg" alt="close" />
          <img class="modal-img" src="https://twxuu.csb.app/boat.jpg" alt="" />
        </div>
      </div>
    </transition>

    <transition name="fade">
      <div v-show="showDog" class="modal">
        <div class="modal-body">
          <img class="modal-close" v-on:click="showDogModal"  src="https://twxuu.csb.app/close.svg" alt="close" />
          <img class="modal-img" src="https://twxuu.csb.app/dog.png" alt="" />
        </div>
      </div>
    </transition>

    <footer>
      Copyright ©{{ new Date().getFullYear() }} Eric Rose <br />
      <a href="mailto:eric@ericrose.dev">eric@ericrose.dev</a> <br />
      <a href="https://github.com/ericrosedev/" target="_blank">Projects</a> |
      <a href="https://erictrose.github.io/" target="_blank">Student Projects</a> |
      <a href="https://ericrosedev.github.io" target="_blank">Blog</a>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data: function () {
    return {
      showBoat: false,
      showDog: false
    }
  },
  methods: {
    showBoatModal: function (event) {
      if (event) {
        this.showBoat = !this.showBoat;
      }
    },
    showDogModal: function (event) {
      if (event) {
        this.showDog = !this.showDog;
      }
    }
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

/* page style */
.erd {
  h1,
  h2,
  h3,
  h4,
  h5,
  h6 {
    font-family: "Quicksand", sans-serif;
    margin: 0;
    padding: 0;
  }
  h1 {
    padding: 1rem 0 0.75rem;

    /* tablet */
    @media (min-width: 768px) {
      padding: 0rem 0 1.75rem;
    }
  }
  h2 {
    padding: 2rem 3rem 2rem;
    text-align: center;

    /* tablet */
    @media (min-width: 768px) {
      padding: 2rem 0 2rem 3rem;
      text-align: left;
    }
  }
  h3 {
    text-align: center;
    font-size: 0.8rem;

    @media (min-width: 768px) {
      padding: 2rem 0 2rem 3rem;
      font-size: 1rem;
    }
  }
  p,
  span {
    font-family: "Raleway", sans-serif;
    font-size: 1rem;
    line-height: 1.5rem;

    /* tablet */
    @media (min-width: 768px) {
      font-size: 1.2rem;
      line-height: 1.75rem;
    }
  }
  a {
    text-decoration: none;
  }
  ul {
    list-style: none;
    margin: 0;
    padding: 0 1rem;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;

    /* tablet */
    @media (min-width: 768px) {
      justify-content: center;
    }

    /* desktop */
    @media (min-width: 1200px) {
    }
  }
  li {
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: "Raleway", sans-serif;
    font-size: 0.65rem;
    line-height: 1.5rem;
    padding: 1rem 0;
    display: flex;
    flex-direction: column;
    text-align: center;
    /* border: 1px solid lightgray; */
    min-width: 100px;
    min-height: 80px;
    transition: all 0.2s ease-in-out;

    &:hover {
      transform: scale(1.5);
    }

    > div {
      flex-direction: row;
    }

    img {
      padding: 0;
      width: 50px;
      height: 45px;

      /* tablet */
      @media (min-width: 768px) {
        width: 80px;
        height: 72px;
      }
    }

    .animated-gif {
      border-radius: 5px;
      width: 1.32rem;
      height: 1.32rem;
      padding: 0.7rem;

      /* tablet */
      @media (min-width: 768px) {
        width: 2.06rem;
        height: 2.06rem;
        padding: 1.2rem 1.425rem;
      }
    }

    /* tablet */
    @media (min-width: 768px) {
      min-width: 170px;
      min-height: 170px;
      font-size: 1rem;
      padding: 0 3rem;
    }

    /* desktop */
    @media (min-width: 1200px) {
    }
  }
  img {
    width: 80px;
    height: 72px;
  }
  section {
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    position: relative;

    h3 {
      /* position: absolute;
      top: 0;
      left: 0; */
      margin: 0;
      padding: 0;
    }
  }
  .intro {
    padding: 1rem 1rem 0 1rem;

    .leader {
      font-size: 1.25rem;
      margin: 0;
      padding-bottom: 1.5rem;

      /* tablet */
      @media (min-width: 768px) {
        font-size: 1.35rem;
        line-height: 2.25rem;
      }
    }

    p:nth-child(3) {
      margin-top: 0;
    }

    p:last-of-type {
      margin-bottom: 0;
    }

    /* tablet */
    @media (min-width: 768px) {
      padding: 3rem 3rem 0 3rem;
    }
  }
  .area {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
  }
  .stuff {
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;

    section {
      margin-bottom: 2rem;

      &:last-of-type {
        margin-bottom: 0;
      }
    }

    .design {
      max-width: 850px;
    }
    .development {
      max-width: 1050px;
    }
  }
  .tools {
    flex-direction: row;
    flex-wrap: wrap;

    section {
      margin-bottom: 3rem;
    }
  }
  .methods {
    margin-bottom: 1.5rem;

    ul {
      justify-content: center;
    }
    li {
      padding: 0 1rem 1rem;

      @media (min-width: 768px) {
        padding: 0 2rem 0;
      }
    }
  }
  .icon {
    width: 3rem;
  }
  .modal {
    position: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.5);
    &-body {
      position: relative;
    }
    &-close {
      position: absolute;
      width: 1.5rem;
      height: 1.5rem;
      top: -2rem;
      right: 1rem;
      opacity: 1;

      @media (min-width: 370px) {
        top: 1rem;
        opacity: 0.5;
      }
      @media (min-width: 640px) {
        width: 3rem;
        height: 3rem;
      }
    }
    &-img {
      width: 100%;
      height: 100%;
      max-width: 640px;
      max-height: 484px;
      border-radius: 1rem;
    }
  }
  footer {
    font-size: 0.8rem;
    background-color: #f7f7f7;
    padding: 2rem 0;
    text-align: center;
    font-family: "Quicksand", sans-serif;
    color: #bdbdbd;
    line-height: 1.5rem;

    a {
      color: #9e9e9e;
      font-size: 1rem;

      &:hover {
        color: #797979;
      }
    }
  }
}

/* util classes */
.dflex-row {
  display: flex;
  flex-direction: row;
}
.dflex-col {
  display: flex;
  flex-direction: column;
}

/* animations */
.spinme {
  transform: rotateY(0deg);
  animation: rotateAnimation 10s linear infinite;
}
@keyframes rotateAnimation {
  from {
    transform: rotateY(0deg);
  }
  to {
    transform: rotateY(360deg);
  }
}
.fade-enter-active, .fade-leave-active {
  transition: opacity .2s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>
