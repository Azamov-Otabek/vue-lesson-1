<script setup>
import Examples1 from "../assets/images/examples1.png";
import Examples2 from "../assets/images/examples2.png";
</script>

<template>
  <section id="examples">
    <div class="container">
      <div class="examples">
        <h3>
          Real-world examples of how we have helped companies achieve their marketing
          objectives.
        </h3>
        <div class="btns">
          <button>All Work [20]</button>
          <button>UI/UX Design[10]</button>
          <button>Digital Marketing [5]</button>
          <button>Branding</button>
        </div>

        <div class="images">
          <img :src="Examples1" alt="Examples1 photo" />
          <img :src="Examples2" alt="Examples2 photo" />
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
#examples {
  margin-top: 100px;
  padding: 80px 0;
  background: #020609;
}

.examples {
  color: white;

  h3 {
    font-size: 48px;
    font-weight: 600;
    line-height: 62px;
    text-align: center;
    margin-bottom: 53px;
  }

  .btns {
    display: flex;
    justify-content: center;
    gap: 24px;
    margin-bottom: 80px;

    button {
      padding: 13px 70px;
      background: black;
      color: white;
      border: 1px solid white;
      border-radius: 50px;
      transition: all 0.1s linear;
      cursor: pointer;

      &:hover {
        background: #99cf63;
        color: black;
        border: 1px solid #99cf63;
        transition: all 0.1s linear;
      }
    }
  }

  .images {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 50px;
  }
}
</style>
