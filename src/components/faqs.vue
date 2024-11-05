<script setup></script>

<template>
  <section id="faqs">
    <div class="container">
      <div class="faqs">
        <div class="faqs-left">
          <h3>Digital Marketing FAQs</h3>
          <p>
            As a leading digital marketing agency, we are dedicated to providing
            comprehensive educational resources and answering frequently asked questions
            to help our clients.
          </p>
          <div class="btns">
            <button>More Questions</button>
            <a href="#">Contanct Us</a>
          </div>
        </div>
        <div class="faqs-right">
          <ul>
            <h4>Why is digital marketing important for my business?</h4>
            <li>
              Digital marketing allows businesses to reach and engage with a wider
              audience, generate leads, drive website traffic, and increase brand
              visibility. It provides measurable results, allows for targeted marketing
              efforts, and enables businesses to adapt and optimize their strategies based
              on data and insights.
            </li>
          </ul>
          <ul>
            <h4>How can digital marketing help improve my website's visibility?</h4>
          </ul>
          <ul>
            <h4>How long does it take to see results from digital marketing efforts?</h4>
          </ul>
          <ul>
            <h4>How do you measure the success of digital marketing campaigns?</h4>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
    #faqs{
        margin-top: 130px;
    }

    .faqs{
        display: flex;
        align-items: start;
        justify-content: space-between;

        .faqs-left{
            width: 100%;
            max-width: 531px;
            h3{
                font-size: 48px;
                line-height: 62px;
                font-weight: 600;
                margin-bottom: 38px;
                width: 100%;
            }

            p{
                font-weight: 500;
                font-size: 16px;
                line-height: 28px;
                color: #878C91;
                width: 100%;
                margin-bottom: 48px;
            }
            
            .btns{
                display: flex;
                gap: 30px;
                align-items: center;
                
                button{
                    padding: 13px 60px;
                    border: 1px solid black;
                    border-radius: 50px;
                    font-weight: 600;
                    cursor: pointer;
                }

                a{
                    font-size: 14px;
                    color: black;
                    text-decoration: underline;
                }
            }

        }

        .faqs-right{
            width: 100%;
            max-width: 627px;
            padding: 0 24px;

            ul:first-child{
                border-top: 2px solid black;
            }

            ul{
                padding: 26px 0;
                border-bottom: 2px solid black;
                h4{
                    font-size: 24px;
                    line-height: 32px;
                }

                li{
                    margin-top: 48px;
                    font-size: 16px;
                    line-height: 28px;
                }
            }
        }
    }

</style>
