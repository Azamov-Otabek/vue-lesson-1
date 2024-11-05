<script setup></script>

<template>
  <footer>
    <div class="container">
      <div class="footer">
        <div class="footer-logos">
          <h2>LOGO</h2>
          <p>
            We offers a comprehensive suite of digital marketing services that cover all
            aspects of our online presence. From SEO and social media marketing to content
            creation and PPC advertising, they have the expertise and resources to handle
            our diverse marketing needs.
          </p>
          <div class="icons">
            <p><i class='bx bxl-telegram' ></i></p>
            <p><i class='bx bxl-instagram' ></i></p>
            <p><i class='bx bxl-twitter' ></i></p>
          </div>
        </div>
        <ul>
            <h5>Navigation</h5>
            <li>Service</li>
            <li>Agency</li>
            <li>Case Study</li>
            <li>Resource</li>
            <li>Contact</li>
        </ul>
        
        <ul>
            <h5>Licence</h5>
            <li>Privacy Policy</li>
            <li>Email Address</li>
            <li>Copyright Study</li>
        </ul>

        <ul>
            <h5>Contact</h5>
            <li>(406) 555-0120</li>
            <li>Hey@boostim.com</li>
            <li>2972 Westheimer Rd. Santa Ana, Illinois 85486 </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>

    .footer{
        margin-top: 130px;
        display: flex;
        justify-content: space-between;
        
        .footer-logos{
            width: 100%;
            max-width: 534px;
            h2{
                font-size: 32px;
                margin-bottom: 30px;
            }

            p{
                font-size: 14px;
                line-height: 28px;
                color: #9B9B9C;
            }

            .icons{
                margin-top: 30px;
                display: flex;
                gap: 30px;
                p{
                    font-size: 30px;
                    cursor: pointer;
                }
            }
        }

        ul{
            width: 100%;
            max-width: 180px;
            h5{
                font-weight: 600;
                font-size: 18px;
                margin-bottom: 40px;
            }

            li{
                color: #9B9B9C;
                margin-bottom: 20px;
                font-size: 14px;
                cursor: pointer;
            }
        }
    }
</style>
