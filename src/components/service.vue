<script setup>
    import Service1 from '../assets/images/service1.png';
    import Service2 from '../assets/images/service2.png';
</script>

<template>
  <section id="service">
    <div class="container">
      <div class="service">
        <div class="service-title">
          <h3>Provide the best service with out of the box ideas</h3>
          <p>
            we are a passionate team of digital marketing enthusiasts dedicated to helping
            businesses succeed in the digital world. With years of experience and a deep
            understanding of the ever-evolving online landscape, we stay at the forefront
            of industry trends and technologies.
          </p>
        </div>

        <div class="service-images">
            <img :src="Service1" alt="Service1 photo">
            <img :src="Service2" alt="Service2 photo">
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
    .service{
      margin-top: 120px;
      display: flex;
      flex-direction: column;
      gap: 72px;

      .service-title{
        display: flex;
        align-items: center;
        justify-content: space-between;
        h3{
          width: 100%;
          max-width: 684px;
          font-size: 48px;
          line-height: 62px;
          font-weight: 600;
        }

        p{
          width: 100%;
          max-width: 557px;
          color: #878C91;
          line-height: 28px;
        }
      }

      .service-images{
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
    }
</style>
