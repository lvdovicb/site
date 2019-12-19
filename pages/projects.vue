<template>
  <div class="container">
    <div class="div0"></div>
    <div class="card div1" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div2" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div3" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div4" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div5" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div6" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div7" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div8" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div9" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div10" tabindex="0">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
  </div>
</template>

<script>
import { gsap } from "gsap";

export default {
  mounted() {
    this.anim();
  },
  methods: {
    anim() {
      gsap.fromTo(
        ".card",
        { opacity: 0, x: -500 },
        { opacity: 1, duration: 2, x: 100, ease: "Elastic.easeInout" }
      );
    }
  }
};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css?family=Alatsi&display=swap");

.container {
  margin: 0;
  padding: 0;
  font-family: "Alatsi", sans-serif;
  min-height: 100vh;
  display: grid;
  grid-template-columns: repeat(auto-fit, 2fr);
  grid-template-rows: repeat(12, 100px);
  grid-column-gap: 2px;
  grid-row-gap: 10px;
  background-color: #232946;
}
.card {
  border-radius: 10px;
  padding: 10px;
  opacity: 0;
  font-size: 1rem;
  z-index: 0;
}
//hover et focus ont un style different, le scale ne marche pas au focus
.card:hover {
  z-index: 1;
  transition: z-index 200ms ease-in-out;
}
.card:focus {
  z-index: 1;
  outline: none;
  transform: scale(2.1);
}
.div0 {
  grid-area: 1 / 4 / 13 / 10;
  background-color: #e9e9e9;
  z-index: 1;
}
.div1 {
  grid-area: 1 / 1 / 4 / 7;
  background-color: #e89dbe;
}

.div2 {
  background-color: #eb649e;
  grid-area: 2 / 6 / 4 / 9;
}

.div3 {
  background-color: #eebbc3;
  grid-area: 1 / 3 / 9 / 5;
}

.div4 {
  background-color: #996b7f;
  grid-area: 3 / 7 / 6 / 10;
}
.div5 {
  background-color: #eee;
  grid-area: 5 / 1 / 8 / 5;
}
.div6 {
  grid-area: 5 / 6 / 8 / 9;
  background-color: #f880b4;
}
.div7 {
  grid-area: 6 / 3 / 10 / 6;
  background-color: #dd508d;
}
.div8 {
  grid-area: 7 / 7 / 10 / 10;
  background-color: #ca81e4;
}
.div9 {
  grid-area: 8 / 2 / 12 / 9;
  background-color: #e3a8c2;
}
.div10 {
  grid-area: 10 / 6 / 12 / 9;
  background-color: #ec3b88;
}
</style>
