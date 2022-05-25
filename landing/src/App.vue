<template>
  <div id="body" class="container-fluid">
    <div id="capa" class="d-flex center-center h8 bg-white">
      <div id="title" class="d-flex flex-column align-items-center">
        <h2>Lorem Ipsum Sit Amet</h2>
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit ad voluptatibus nostrum.</span>
      </div>
    </div>
    <div class="container">
      <div id="picNexp-1" class="row h6">
        <div class="col d-flex center-center">
          <h2>Lorem Ipsum</h2>
        </div>
        <div class="col d-flex center-center text-center">
          <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro eveniet harum culpa inventore rem blanditiis excepturi autem. Aliquid ducimus, numquam molestias dolores officia nihil incidunt tempore iusto consectetur rem temporibus.</span>
        </div>
      </div>
      <div id="picNexp-2" class="row h6">
        <div class="col d-flex center-center text-center">
          <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro eveniet harum culpa inventore rem blanditiis excepturi autem. Aliquid ducimus, numquam molestias dolores officia nihil incidunt tempore iusto consectetur rem temporibus.</span>
        </div>
        <div class="col d-flex center-center">
          <h2>Lorem Ipsum</h2>
        </div>
      </div>
      <div id="picNexp-3" class="row h6">
        <div class="col d-flex center-center">
          <h2>Lorem Ipsum</h2>
        </div>
        <div class="col d-flex center-center text-center">
          <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro eveniet harum culpa inventore rem blanditiis excepturi autem. Aliquid ducimus, numquam molestias dolores officia nihil incidunt tempore iusto consectetur rem temporibus.</span>
        </div>
      </div>
      <div id="picsNtitles" class="row row-cols-3 h6">
        <div class="col d-flex flex-column">
          <div class="col d-flex center-center">
            <h3>Lorem Ipsum</h3>
          </div>
          <div class="col d-flex center-center text-center">
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.!</span>
          </div>
        </div>
        <div class="col d-flex flex-column">
          <div class="col d-flex center-center">
            <h3>Lorem Ipsum</h3>
          </div>
          <div class="col d-flex center-center text-center">
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.!</span>
          </div>
        </div>
        <div class="col d-flex flex-column">
          <div class="col d-flex center-center">
            <h3>Lorem Ipsum</h3>
          </div>
          <div class="col d-flex center-center text-center">
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.!</span>
          </div>
        </div>

        <div class="col d-flex flex-column">
          <div class="col d-flex center-center">
            <h3>Lorem Ipsum</h3>
          </div>
          <div class="col d-flex center-center text-center">
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.!</span>
          </div>
        </div>
        <div class="col d-flex flex-column">
          <div class="col d-flex center-center">
            <h3>Lorem Ipsum</h3>
          </div>
          <div class="col d-flex center-center text-center">
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.!</span>
          </div>
        </div>
        <div class="col d-flex flex-column">
          <div class="col d-flex center-center">
            <h3>Lorem Ipsum</h3>
          </div>
          <div class="col d-flex center-center text-center">
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.!</span>
          </div>
        </div>
      </div>
    </div>

    <div class="d-flex flex-column justify-content-center h8">
      <div id="cell" class="row d-flex h6 mb-0">
        <div id="cellPic" class="col-5 border"></div>
        <div class="col d-flex flex-column justify-content-center">
          <div id="cellExp-1">
            <h3 class="text-white">
              Lorem
            </h3>
            <span>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur ea cupiditate nam. Commodi corrupti necessitatibus vel aliquam officiis animi quas, accusamus expedita eos sit magnam nobis fugit ea, itaque blanditiis.
            </span>
          </div>
          <div id="cellExp-2">
            <h3 class="text-white">
              Lorem
            </h3>
            <span>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur ea cupiditate nam. Commodi corrupti necessitatibus vel aliquam officiis animi quas, accusamus expedita eos sit magnam nobis fugit ea, itaque blanditiis.
            </span>
          </div>
        </div>
      </div>
    </div>

    <div id="bottom" class="container-fluid d-flex center-center h6">
      <div class="container">
        <div class="row">
          <div class="col">
            <h3>Lorem Ipsum</h3>
            <ul>
              <li>
                Lorem
              </li>
              <li>
                Lorem
              </li>
              <li>
                Lorem
              </li>
            </ul>
          </div>
          <div class="col">
            <h3>Lorem Ipsum</h3>
            <ul>
              <li>
                Lorem
              </li>
              <li>
                Lorem
              </li>
              <li>
                Lorem
              </li>
            </ul>
          </div>
          <div class="col">
            <h3>Lorem Ipsum</h3>
            <ul>
              <li>
                Lorem
              </li>
              <li>
                Lorem
              </li>
              <li>
                Lorem
              </li>
            </ul>
          </div>
        </div>
        
      </div>

    </div>
  </div>
</template>

<script>
import { gsap } from "gsap";

let animations = {
  zero: {opacity: 1, y: 0, x: 0},
  fromUp: {duration: 2, opacity: 0, y: -100},
  fromDown: {duration: 2, opacity: 0, y: 100},
  fromLeft: {duration: 2, opacity: 0, x: -100},
  fromRight: {duration: 2, opacity: 0, x: 100},
}

export default {
  data: function () {
    return {
      scrollPoint: 0,
      checkpoints: [
        {check: false, point: 0, id:'#title', animation: animations.fromUp},
        {check: false, point: 300, id:'#picNexp-1', animation: animations.fromRight},
        {check: false, point: 500, id:'#picNexp-2', animation: animations.fromLeft},
        {check: false, point: 800, id:'#picNexp-3', animation: animations.fromRight},
        {check: false, point: 1400, id:'#picsNtitles', animation: animations.fromDown},
        {check: false, point: 1800, id:'#cellPic', animation: animations.fromLeft},
        {check: false, point: 1800, id:'#cellExp-1', animation: animations.fromRight},
        {check: false, point: 1800, id:'#cellExp-2', animation: animations.fromRight},
    ]
    }
  },
  mounted(){
    window.addEventListener('scroll', this.handleScroll)
    this.checkpoints.forEach(function (point) {
      gsap.set(point.id, point.animation)
    })
  },
  methods: {
    handleScroll(){
      this.checkpoints.forEach( function (element) {
        if (!element.check && window.scrollY > element.point) {
          gsap.to(element.id, animations.zero)
          element.check = true;
        }
      })
    }
  }
}
</script>

<style>
:root {
  --red: rgba(255, 32, 32, 0.856);
}

h1, h2, h3 {
  color: var(--red);
}

#body{
  color: white;
  background-color: #292929;
}

#capa{
  color: gray;
  border-bottom: solid 1px;
}

#bottom{
  background-color: black;
  margin-bottom: 0px;
}

#cell{
  background-color: var(--red);
}

.center-center{
  justify-content: center;
  align-items: center;
}

.h4, .h6, .h8, .h10{
  margin-bottom: 5vh;
}

.container-fluid{
  padding: 0px;
}

.h4{
  height: 40vh;
}

.h6{
  height: 60vh;
}

.h8{
  height: 80vh;
}

.h10{
  height: 100vh;
}

</style>
