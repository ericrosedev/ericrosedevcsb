<template>
  <div class="erd">
    <div class="intro">
      <h1>Hi, I'm Eric 💁🏻‍♂️</h1>

      <p class="leader">I’m a web designer and developer.</p>

      <p>I like building things for the internet that people can enjoy.</p>

      <p>
        I’ve been doing this and project management full time since 2013, before that I was an
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
            <img src="https://twxuu.csb.app/lightbulb_animated.svg" alt="lightbulb" />
            Ideation
          </li>
          <li>
            <img src="https://twxuu.csb.app/wireframe_animated.svg" alt="wireframe" />
            Wireframing
          </li>
          <li>
            <img src="https://twxuu.csb.app/mock_animated.svg" alt="mockup" /> Mocking
          </li>
          <li>
            <div>
              <img src="https://twxuu.csb.app/vector.svg" alt="vector" />
              <img src="https://twxuu.csb.app/raster.png" alt="raster" />
            </div>
            Vector &amp; Raster <br />
            Design
          </li>
          <li>
            <div class="dflex-row">
              <img
                src="https://twxuu.csb.app/vector_anim_animated.svg"
                alt="animated vector"
              />
              <img
                src="https://twxuu.csb.app/raster_anim_animated.gif"
                alt="animated raster"
                class="animated-gif"
              />
            </div>
            Vector &amp; Raster <br />
            Animation
          </li>
          <li>
            <img src="https://twxuu.csb.app/logo.svg" alt="logo design" /> Logo Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/emaildesign_animated.svg" alt="email design" />
            Email Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/videodesign_animated.svg" alt="video design" />
            Video Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/generalui_animated.svg" alt="gnereal user experience" />
            General UX UI IXD Stuff
          </li>
        </ul>
      </section>

      <section class="development">
        <h3>Development</h3>

        <ul>
          <li><img src="https://twxuu.csb.app/html5.svg" alt="html5" /> HTML5</li>
          <li>
            <img src="https://twxuu.csb.app/htmls.svg" alt="semantic markup" /> Semantic Markup
          </li>
          <li>
            <img src="https://twxuu.csb.app/htmli.svg" alt="templating and interpolation" /> Templating
            &amp; Interpolation
          </li>
          <li><img src="https://twxuu.csb.app/css3.svg" alt="css3" /> CSS3</li>
          <li>
            <div class="dflex-row">
              <img src="https://twxuu.csb.app/cssf.svg" alt="css flexbox" />
              <img src="https://twxuu.csb.app/cssg.svg" alt="css grid" />
            </div>
            Flexbox &amp; Grid <br />
            Based design
          </li>
          <li>
            <div class="spinme">
              <img src="https://twxuu.csb.app/csstt_animated.svg" alt="css transforms, transitions, animations, and perspectives" />
            </div>
            Animation
          </li>
          <li><img src="https://twxuu.csb.app/js.svg" alt="ecmascript 6" /> JS</li>
          <li>
            <div>
              <img src="https://twxuu.csb.app/angular.svg" alt="google angular" style="transform: scale(0.8) translateX(1rem);" />
              <img src="https://twxuu.csb.app/vue.svg" alt="vue" style="transform: scale(1.2);" />
              <img src="https://twxuu.csb.app/react.svg" alt="facebook react" style="transform: scale(0.8) translateX(-1rem);;" />
            </div>
            Modern Frontend Frameworks
          </li>
          <li><img src="https://twxuu.csb.app/node.svg" alt="node" /> Node</li>
          <li>
            <img
              src="https://twxuu.csb.app/responsivedesign_animated.svg"
              alt="responsive design"
            />
            Responsive Layouts
          </li>
          <li>
            <img src="https://twxuu.csb.app/rapidproto_animated.svg" alt="rapid prototyping" />
            Rapid Prototyping
          </li>
          <li>
            <img
              src="https://twxuu.csb.app/versioncontrol_animated.svg"
              alt="version control"
            />
            Version Control
          </li>
          <li>
            <img src="https://twxuu.csb.app/cicd_animated.svg" alt="continuous integration and continuous deployment" /> CI/CD
          </li>
          <li>
            <img src="https://twxuu.csb.app/emaildev_animated.svg" alt="email development" />
            Email Development
          </li>
          <li>
            <img src="https://twxuu.csb.app/videodev_animated.svg" alt="video development" />
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
            <img src="https://twxuu.csb.app/windows.svg" alt="windows" /> Windows
          </li>
          <li><img src="https://twxuu.csb.app/apple.svg" alt="apple" /> Mac</li>
        </ul>
      </section>

      <section>
        <h3>Browsers</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/chrome.svg" alt="google chrome" /> Chrome</li>
          <li>
            <img src="https://twxuu.csb.app/firefox.svg" alt="firefox" /> FireFox
          </li>
          <li><img src="https://twxuu.csb.app/safari.svg" alt="safari" /> Safari</li>
          <li><img src="https://twxuu.csb.app/edge.svg" alt="microsoft edge" /> Edge</li>
        </ul>
      </section>

      <section>
        <h3>Graphic Design</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/photoshop.svg" alt="adobe photoshop" /> Photoshop
          </li>
          <li>
            <img src="https://twxuu.csb.app/illustrator.svg" alt="adobe illustrator" />
            Illustrator
          </li>
        </ul>
      </section>

      <section>
        <h3>Animation</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/svgator.svg" alt="svgator" /> SVGator
          </li>
        </ul>
      </section>

      <section>
        <h3>Prototyping</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/xd.svg" alt="adobe experience design" /> Experience Design
          </li>
          <li>
            <img src="https://twxuu.csb.app/codepen.svg" alt="codepen" /> CodePen
          </li>
          <li>
            <img src="https://twxuu.csb.app/codesandbox.svg" alt="codesandbox" />
            CodeSandbox
          </li>
        </ul>
      </section>

      <section>
        <h3>CSS Frameworks</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/bootstrap.svg" alt="bootstrap" /> Bootstrap
          </li>
        </ul>
      </section>

      <section>
        <h3>CSS Preprocessors</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/sass.svg" alt="sass and scss" /> SASS / SCSS
          </li>
        </ul>
      </section>

      <section>
        <h3>JS Frameworks</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/vue.svg" alt="vue" /> Vue</li>
        </ul>
      </section>

      <section>
        <h3>3D Frameworks</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/three.svg" alt="three js" /> ThreeJS</li>
        </ul>
      </section>

      <section>
        <h3>Old School</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/jquery.svg" alt="jquery" /> jQuery</li>
        </ul>
      </section>

      <section>
        <h3>Server Frameworks</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/node.svg" alt="node and express" /> Node / Express
          </li>
        </ul>
      </section>

      <section>
        <h3>IDEs</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/vscode.svg" alt="microsoft vs code" /> VS Code</li>
          <li>
            <img src="https://twxuu.csb.app/brackets.svg" alt="adobe brackets" /> Brackets
          </li>
        </ul>
      </section>

      <section>
        <h3>Email Development</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/mjml.svg" alt="mailjet markup language" /> MJML</li>
        </ul>
      </section>

      <section>
        <h3>Video Creation</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/aftereffects.svg" alt="adobe after effects" /> After
            Effects
          </li>
          <li>
            <img src="https://twxuu.csb.app/premiere.svg" alt="adobe premiere" /> Premiere
          </li>
        </ul>
      </section>

      <section>
        <h3>3D Modeling</h3>
        <ul>
          <li><img src="https://twxuu.csb.app/maya.svg" alt="autodesk maya" /> Maya</li>
        </ul>
      </section>

      <section>
        <h3>Compression</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/tinypng.svg" alt="tinypng" /> TinyPNG
          </li>
          <li><img src="https://twxuu.csb.app/svgomg.svg" alt="svgomg" /> SVGOMG</li>
        </ul>
      </section>

      <section>
        <h3>Misc</h3>
        <ul>
          <li>
            <img src="https://twxuu.csb.app/fontawesome.svg" alt="font awesome" />
            FontAwesome
          </li>
          <li>
            <img src="https://twxuu.csb.app/responsively.svg" alt="responsively" />
            Responsively
          </li>
          <li>
            <img src="https://twxuu.csb.app/wlb.svg" alt="work life balance" /> Work / Life
            Balance
          </li>
        </ul>
      </section>
    </div>

    <transition name="fade">
      <div v-show="showBoat" class="modal">
        <div class="modal-body">
          <img class="modal-close" v-on:click="showBoatModal" src="https://twxuu.csb.app/close.svg" alt="close" />
          <img class="modal-img" src="https://twxuu.csb.app/boat.jpg" alt="I should buy a boat" />
        </div>
      </div>
    </transition>

    <transition name="fade">
      <div v-show="showDog" class="modal">
        <div class="modal-body">
          <img class="modal-close" v-on:click="showDogModal"  src="https://twxuu.csb.app/close.svg" alt="close" />
          <img class="modal-img" src="https://twxuu.csb.app/dog.png" alt="my dog dakota" />
        </div>
      </div>
    </transition>

    <footer>
      Copyright ©{{ new Date().getFullYear() }} Eric Rose <br />
      <a href="mailto:eric@ericrose.dev">eric@ericrose.dev</a> <br />
      <a href="https://codepen.io/ericrosedev/" target="_blank">CodePen</a> |
      <a href="https://github.com/ericrosedev/" target="_blank">Github</a> |
      <a href="https://ericrosedev.github.io" target="_blank">Blog</a> <br />
      portfolio available upon request
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
