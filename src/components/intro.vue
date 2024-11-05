<script setup>
import Intro from "../assets/images/intro.png";
import Brand1 from "../assets/images/brand1.png";
import Brand2 from "../assets/images/brand2.png";
import Brand3 from "../assets/images/brand3.png";
</script>

<template>
  <section id="intro">
    <div class="container">
      <div class="intro">
        <div class="intro-left">
          <h2>Stay ahead of the curve with our forward-thinking</h2>
          <p class="intro-description">
            An award-winning SEO agency with disciplines in digital marketing, design, and
            website development. focused on understanding you.
          </p>
          <div class="actions">
            <button>Schedule Call</button>
            <a href="#">View Case Study</a>
          </div>
          <div class="brands">
            <p>Trusted by the world's biggest brands</p>
            <img :src="Brand1" alt="Brand 1" />
            <img :src="Brand2" alt="Brand 2" />
            <img :src="Brand3" alt="Brand 3" />
          </div>
        </div>

        <div class="intro-right">
          <img :src="Intro" alt="Intro photo" />
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.intro {
  display: flex;
  align-items: start;
  justify-content: space-between;

  .intro-left {
    width: 100%;
    max-width: 700px;

    h2 {
      font-size: 72px;
      font-weight: 600;
      line-height: 79px;
      margin-bottom: 48px;
    }

    .intro-description {
      color: #878c91;
      font-size: 16px;
      font-weight: 500;
      max-width: 557px;
      margin-bottom: 48px;
    }

    .actions {
      display: flex;
      align-items: center;
      gap: 56px;
      margin-bottom: 96px;

      button {
        padding: 15px 52px;
        border-radius: 50px;
        color: white;
        background: black;
        cursor: pointer;

      }

      a{
        color: black;
        font-family: 600;
        text-decoration: underline;
      }
    }

    .brands{
        display: flex;
        align-items: center;
        gap: 20px;

        p{
            max-width: 150px;
            font-weight: 500;
            font-size: 14px;
        }
    }
  }
}
</style>
