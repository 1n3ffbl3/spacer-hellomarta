<template>
  <div class="wrapper">
    <h1 class="claim">SPACER</h1>
    <p class="subclaim">Begin your journey...
    </p>
    <p class="subclaim">Type anything space-related to start.
    </p>
  </div>

</template>

<script>
export default {
  name: "Claim"
};
</script>

<style lang="scss" scoped>
.wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  aling-items: center;
  color: white;
}

.claim {
  font-size: 50px;
  margin: 0;

  @media (min-width: 768px) {
    font-size: 80px;
  }
}

.subclaim {
  margin: 20px 0 0 0;
  font-size: 13px;
  font-weight: 400;

  @media (min-width: 768px) {
    font-size: 17px;
    width: 500px;
    line-height: 1;
    letter-spacing: 1px;
  }
}
</style>
