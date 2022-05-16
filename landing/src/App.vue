<template>
  <div id="body" class="container-fluid">
    <div id="capa" class="d-flex center-center h8 bg-white">
      <div id="title" class="d-flex flex-column align-items-center">
        <h2>Lorem Ipsum Sit Amet</h2>
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit ad voluptatibus nostrum.</span>
      </div>
    </div>
    <div class="container">
      <div  class="row h6">
        <div id="teste" class="col d-flex center-center">
          <h2>Lorem Ipsum</h2>
        </div>
        <div class="col d-flex center-center text-center">
          <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro eveniet harum culpa inventore rem blanditiis excepturi autem. Aliquid ducimus, numquam molestias dolores officia nihil incidunt tempore iusto consectetur rem temporibus.</span>
        </div>
      </div>
      <div class="row h6">
        <div class="col d-flex center-center text-center">
          <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro eveniet harum culpa inventore rem blanditiis excepturi autem. Aliquid ducimus, numquam molestias dolores officia nihil incidunt tempore iusto consectetur rem temporibus.</span>
        </div>
        <div class="col d-flex center-center">
          <h2>Lorem Ipsum</h2>
        </div>
      </div>
      <div class="row h6">
        <div class="col d-flex center-center">
          <h2>Lorem Ipsum</h2>
        </div>
        <div class="col d-flex center-center text-center">
          <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro eveniet harum culpa inventore rem blanditiis excepturi autem. Aliquid ducimus, numquam molestias dolores officia nihil incidunt tempore iusto consectetur rem temporibus.</span>
        </div>
      </div>
      <div class="row row-cols-3 h6">
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
        <div class="col-5 border"></div>
        <div class="col d-flex flex-column justify-content-center">
          <div>
            <h3 class="text-white">
              Lorem
            </h3>
            <span>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur ea cupiditate nam. Commodi corrupti necessitatibus vel aliquam officiis animi quas, accusamus expedita eos sit magnam nobis fugit ea, itaque blanditiis.
            </span>
          </div>
          <div>
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
// import { gsap } from "gsap";

export default {

  data: function () {
    return {
      fromUp: {duration: 2, opacity: 0, y: -100},
      fromLeft: {duration: 2, opacity: 0, x: -100},
      fromRight: {duration: 2, opacity: 0, x: 100}
    }
  },
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
