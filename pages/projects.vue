<template>
  <div class="container">
    <div class="card div1">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div2">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div3">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div4">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div5">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div6">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div7">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div8">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div9">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
        possimus quod odio provident quidem blanditiis aliquid tenetur accusamus
        sequi totam earum similique nulla, veniam, omnis nam labore doloribus
        consequuntur adipisci?
      </p>
    </div>
    <div class="card div10">
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
@import url("https://fonts.googleapis.com/css?family=Alatsi&display=swap");

.container {
  margin: 0;
  padding: 0;
  font-family: "Alatsi", sans-serif;
  min-height: 100vh;
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  grid-template-rows: repeat(12, 1fr);
  grid-column-gap: 2px;
  grid-row-gap: 20px;
}
.card {
  border-radius: 10px;
}
.div1 {
  grid-area: 2 / 2 / 4 / 5;
  background-color: #e89dbe;
}
.div2 {
  background-color: #eb649e;
  grid-area: 2 / 6 / 4 / 9;
}
.div3 {
  background-color: #8d516b;
  grid-area: 4 / 3 / 6 / 6;
}
.div4 {
  background-color: #996b7f;
  grid-area: 4 / 7 / 6 / 10;
}
.div5 {
  background-color: #dd508d;
  grid-area: 6 / 2 / 8 / 5;
}
.div6 {
  grid-area: 6 / 6 / 8 / 9;
  background-color: #ac225e;
}
.div7 {
  grid-area: 8 / 3 / 10 / 6;
  background-color: #dd508d;
}
.div8 {
  grid-area: 8 / 7 / 10 / 10;
  background-color: #c4105e;
}
.div9 {
  grid-area: 10 / 2 / 12 / 5;
  background-color: #a11652;
}
.div10 {
  grid-area: 10 / 6 / 12 / 9;
  background-color: #c20b5a;
}
</style>
