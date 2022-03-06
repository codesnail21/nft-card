<template>
  <div class="container">
    <div class="p-4 hero bgcol">
      <div class="image">
        <img
          class="img-fluid"
          src="@/static/image-equilibrium.png"
          alt="equilibrium"
        />
      </div>
      <div class="text-left text-white my-4">
        <div>
          <span class="title" style="font-size: 32px; font-weight: 600">
            Equilibrium #3429
          </span>
        </div>
        <div class="my-3 desc" style="font-size: 16px; font-weight: 200">
          <span> Our Equilibrium collection promotes balance and calm. </span>
        </div>
      </div>
      <div
        style="
          border-bottom: 1px solid rgb(116, 116, 116);
          padding-bottom: 16px;
        "
      >
        <div class="d-flex flex-row justify-content-between">
          <div>
            <span
              class="d-flex flex-row align-items-center"
              style="color: hsl(178, 100%, 50%)"
            >
              <img class="mx-2" src="/assets/icon-ethereum.svg" alt="" />
              0.041 ETH
            </span>
          </div>
          <div>
            <span class="d-flex flex-row align-items-center text-muted">
              <img class="mx-2" src="/assets/icon-clock.svg" alt="" />
              3 days left
            </span>
          </div>
        </div>
      </div>
      <div class="d-flex flex-row align-items-center my-3">
        <div class="col-2 p-0">
          <b-img
            rounded="circle"
            alt="Circle image"
            height="35"
            class="border"
            src="assets/image-avatar.png"
          ></b-img>
        </div>
        <div class="col-10" style="font-size: 15px">
          <span class="" style="font-weight: 200; color: hsl(215, 51%, 70%, 1)">
            Creation of
          </span>
          <span class="text-white"> Vatsal Chauhan </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: #17273f;
}
.hero {
  border-radius: 15px;
  max-width: 24rem;
  box-shadow: 10px 6px 26px -6px rgba(0, 0, 0, 0.6);
}
.container {
  padding-top: 8rem;
  margin: 0 auto;
  padding: 0 auto;
  display: flex;
  justify-content: center;
}
.desc {
  color: hsl(215, 51%, 70%, 1);
}
.bgcol {
  background-color: hsl(214, 47%, 12%);
}
</style>
