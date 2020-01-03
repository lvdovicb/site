<template>
  <div class="container">
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
export default {};
</script>

<style lang="scss" scoped>
.container {
  max-width: 100vw;
  --auto-grid-min-size: 8rem;
  display: grid;
  grid-template-columns: repeat(
    auto-fill,
    minmax(var(--auto-grid-min-size), 1fr)
  );
  grid-gap: 1rem;
  background-color: #232946;
}
.card {
  border-radius: 10px;
  padding: 10px;
  // opacity: 0;
  font-size: 1rem;
  z-index: 0;
  transition: transform scale z-index 150ms ease-in-out;
}
//hover et focus ont un style different, le scale ne marche pas au focus
.card:hover,
.card:focus {
  z-index: 1;
  outline: none;
  transform: scale(1.1);
  box-shadow: 0 0 0 8px #232946, 0 0 0 12px #acb2cf;
}
.div0 {
  grid-area: 1 / 4 / 13 / 10;
  background-color: #e9e9e9;
  z-index: 1;
}
.div1 {
  grid-area: 2 / 2 / 4 / 7;
  background-color: #e89dbe;
}

.div2 {
  background-color: #eb649e;
  grid-area: 2 / 6 / 4 / 9;
}

.div3 {
  background-color: #eebbc3;
  grid-area: 2 / 3 / 9 / 5;
}

.div4 {
  background-color: #996b7f;
  grid-area: 3 / 7 / 6 / 10;
}
.div5 {
  background-color: #eee;
  grid-area: 5 / 2 / 8 / 5;
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
  grid-area: 8 / 3 / 12 / 9;
  background-color: #e3a8c2;
}
.div10 {
  grid-area: 10 / 6 / 12 / 9;
  background-color: #ec3b88;
}
</style>
