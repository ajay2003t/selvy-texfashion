<template>
    <div>
        <header>
            <nav class="navbar">
                <div class="logo">
                    <a href="#"><img src="../assets/Group 247.png" alt="SELVY TEX Logo"></a>
                </div>
                <ul class="nav-links">
                    <li><router-link to="/">Home</router-link></li>
                    <li><router-link to="company">Our Company</router-link></li>
                    <li><router-link to="services">Our Services</router-link></li>
                    <li><router-link to="product">Our Product</router-link></li>
                    <li><a href="#">How To Order</a></li>
                    <li class="cont"><router-link to="contact">Contact us</router-link>
                        <div class="flag">
                            <img loading="lazy"
                                srcset="https://cdn.builder.io/api/v1/image/assets%2Fb4f70d42747f4784a7941910e7311e3c%2F53e717eb79cc432db4d5dd09319488b6"
                                class="nav-flag" />
                        </div>
                    </li>
                </ul>
            </nav>
        </header>
        <section class="sec1"></section>
        <div class="box">
            <div class="group">
                <div class="service-header1">
                    <div class="service-line1"></div>
                    <h2 class="service-title1">OUR COMPANY</h2>
                    <div class="service-line1"></div>
                </div>
                <p class="section">
                    Our profound love for fashion, got us venture into clothing production and manufacturing.
                    Located<br> in Tirupur, South India's textile hub, we ensure uncompromised quality, contributing to
                    90% of the<br> country's cotton knitwear exports.
                </p>
            </div>
        </div>
        <img src="../assets/back21.png" class="rect-img">
        <comp></comp>
        <section class="sec2">
            <vision></vision>
        </section>
        <section class="sec3">
            <div class="service-header2">
                <div class="service-line2"></div>
                <h2 class="service-title2">OUR EXPERTISE</h2>
                <div class="service-line2"></div>
            </div>
            <img src="https://cdn.builder.io/api/v1/image/assets%2F5acb37f697474270ad553272da64e56a%2F45c1dddd347e4ac5a0adfd211bdef830" class="sec3-1">
        </section>
        <section class="sec4">
            <div class="sec4-boxt">
                <div class="order-instructions">
                    <h2 class="order-title">HOW TO ORDER</h2>
                </div>
                <div class="sec4-box">
                    <div class="minimum-quantity-info">
                        <h2 class="quantity-title">MINIMUM QUANTITY</h2>
                        <p class="quantity-description">
                            Colors and fabrics stocks from
                            <span class="highlight">50 pcs</span><br>
                            Pantone colors from
                            <span class="highlight">100 pcs</span>
                        </p>
                    </div>
                    <div class="lead-time-info">
                        <h2 class="lead-time-title">LEAD TIME</h2>
                        <p class="lead-time-details">
                           <p><strong>Prototypes : </strong>10 to 15 days</p> 
                           <p><strong>Production : </strong>45 to 60 days</p>
                            
                            <P><strong>Transport : </strong>
                            3 to 7 days by
                            <span class="highlight1">plane</span>
                            ; 20 to 35 days by
                            <span class="highlight1">ship</span>
                            .</P>
                        </p>
                    </div>
                    <button class="sec4-btn">
                        Make enquiry
                    </button>
                </div>
            </div>
        </section>
        <footer>
            <div class="footer">
                <div class="footer-column">
                    <img src="https://cdn.builder.io/api/v1/image/assets%2Faf0c4f4a34884a7c857808257a84dbe0%2Fa5682d076d5c4a38903293c828d70d7f"
                        class="footer-logo" />
                </div>
                <div class="footer-column">
                    <div class="footer-title">Contact</div>
                    <div class="footer-address">
                        8/962, PN Rd, Karupparayan Nagar,
                        <br />
                        Tiruppur, India. 641603
                    </div>
                    <div class="footer-email">
                        Email:
                        <span style="font-weight: 400">contact@selvytex.com</span>
                    </div>
                </div>
                <div class="footer-column">
                    <div class="footer-title1">Quick links</div>
                    <a class="footer-link">Home</a>
                    <a class="footer-link">About</a>
                    <a class="footer-link">How to Order</a>
                    <a class="footer-link">Products</a>
                    <a class="footer-link">Fabrics</a>
                    <a class="footer-link">Services</a>
                    <a class="footer-link">Contact</a>
                </div>
                <div class="footer-column">
                    <div class="footer-title2">Follow</div>
                    <section class="image-gallery">
                        <a href="#" class="gallery-link">
                            <img loading="lazy"
                                src="https://cdn.builder.io/api/v1/image/assets/TEMP/0481bd4103d83f84067408ac49ec9c52abe39b16c65fe5ce0e16a1b335d2ed65?placeholderIfAbsent=true&apiKey=af0c4f4a34884a7c857808257a84dbe0"
                                class="gallery-image small-image" alt="Small decorative image" />
                        </a>
                        <a href="#" class="gallery-link">
                            <img loading="lazy"
                                src="https://cdn.builder.io/api/v1/image/assets/TEMP/a68768c3ee61fd50d8efdd212b2e765c1d11b1fe467eb7acd8fa88056dd3c33e?placeholderIfAbsent=true&apiKey=af0c4f4a34884a7c857808257a84dbe0"
                                class="gallery-image medium-image" alt="Medium decorative image" />
                        </a>
                        <a href="#" class="gallery-link">
                            <img loading="lazy"
                                src="https://cdn.builder.io/api/v1/image/assets/TEMP/13bc1bef45155b9ac6b15c2600e03f0ba004ca57084898a8ae8f23c11c2e1b7b?placeholderIfAbsent=true&apiKey=af0c4f4a34884a7c857808257a84dbe0"
                                class="gallery-image large-image" alt="Large decorative image" />
                        </a>
                    </section>
                </div>
            </div>
            <div class="footer-rect">

            </div>
        </footer>
    </div>
</template>

<script>
import { RouterLink } from "vue-router"
import Vision from "./vision.vue";
export default {

}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
}
header {
    background-color: white;
}

.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 2em;
}

.logo img {
    width: 96%;
}

.nav-links {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
}

.nav-links li {
    font: 400 20px Monda, sans-serif;
}

.nav-links a {
    text-decoration: none;
    color: #D25D38;
    font-weight: bold;
    font-size: 1.1rem;
    margin-left: 3em;
}

/* Responsive Design for Tablets and Smaller Screens */
@media screen and (max-width: 1024px) {
    .navbar {
        padding: 0 30px;
    }

    .nav-links a {
        font-size: 1rem;
        margin-left: 2em;
    }

    .logo img {
        height: 80px;
        width: 150px;
    }
}

@media screen and (max-width: 768px) {
    .navbar {
        padding: 0 20px;
    }

    .nav-links a {
        font-size: 0.9rem;
        margin-left: 1.5em;
    }

    .logo img {
        height: 70px;
        width: 130px;
    }
}

@media screen and (max-width: 480px) {
    .navbar {
        flex-direction: column;
        align-items: flex-start;
        padding: 0 10px;
    }

    .logo img {
        height: 60px;
        width: 110px;
    }

    .nav-links {
        flex-direction: column;
        width: 100%;
    }

    .nav-links li {
        margin-left: 0;
        margin-bottom: 10px;
    }

    .nav-links a {
        font-size: 1rem;
        margin-left: 0;
    }
}

.sec1 {
    height: 87vh;
    background-image: url(../assets/back2.png);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

.box {
    width: 100%;
    padding-top: 3em;
}

.overlap-group {
    display: flex;
    align-items: center;
    justify-content: flex-end;
}

.box .section-heading {
    color: #e07040;
    font-family: "Magra-Bold", Helvetica;
    font-size: 40px;
    font-weight: 700;
    left: 0;
    letter-spacing: 2px;
    text-align: center;
    top: 0;
    white-space: nowrap;
}

.box .rectangle {
    background-color: #e0704066;
    height: 12px;
    left: 669px;
    top: 20px;
    width: 543px;
}

.box .section {
    color: #585858;
    font-family: "Outfit-Regular", Helvetica;
    font-size: 17px;
    font-weight: 400;
    letter-spacing: 0;
    line-height: 25.5px;
    text-align: center;
    margin-top: 3em;
}

.rect-img {
    margin-top: 3em;
    height: 13vh;
    width: 100%;
}

.rect-img2 {
    margin-top: 4em;
    width: 100%;
}

.sec2-img {
    width: 100%;
    margin-top: 7em;
}

.sec3 {
    margin-top: 5em
}

.overlap-group1 {
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

.section-heading1 {
    color: #e07040;
    font-family: "Magra-Bold", Helvetica;
    font-size: 40px;
    font-weight: 700;
    left: 0;
    letter-spacing: 2px;
    line-height: 50px;
    text-align: center;
    top: 0;
    white-space: nowrap;
}

.rectangle1 {
    background-color: #e0704066;
    height: 12px;
    left: 669px;
    top: 20px;
    width: 37%;
    margin-right: 2em;
}

.sec3-1 {
    padding: 2em 12.5em;
}
.sec3-2 {
    padding: 2em 20.9em;
}
.sec4 {
    height: 100vh;
    width: 100%;
    background-image: url(../assets/back3.png);
    margin-top: 4em;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

.sec4-boxt {
    padding: 3em 30em;
}

.sec4-box {
    margin-top: 3em;
    height: 67vh;
    width: 33vw;
    border-radius: 109px 0px 127px / 8.5em 13em;
    background-color: white;
}

.minimum-quantity-info {
    border-radius: 0;
    display: flex;
    flex-direction: column;
    text-align: center;
    padding-top: 4em;
}

.quantity-title {
    color: #F4B194;
    align-self: center;
    font: 600 24px/1 Magra, sans-serif;
}

.quantity-description {
    color: #000;
    margin-top: 21px;
    width: 100%;
    font: 400 15px/29px Outfit, sans-serif;
}

.highlight {
    font-weight: 700;
    color: #E07040;
}
.lead-time-info {
    border-radius: 0;
    display: flex;
    flex-direction: column;
    text-align: center;
    padding-top: 2em;
}

.lead-time-title {
    color: #f4b194;
    align-self: center;
    font: 600 24px/1 Magra, sans-serif;
}

.lead-time-details {
    color: #000;
    margin-top: 25px;
    width: 100%;
    font: 400 15px / 29px Outfit, sans-serif;
}

.lead-time-details strong {
    font-family: Outfit, sans-serif;
    font-weight: 800;
}

.lead-time-details span {
    font-family: Outfit, sans-serif;
    font-weight: 700;
    color: #E07040;
}

.sec4-btn{
    background-color: #e07040;
    padding: 1em 4em;
    border: transparent;
    color: white;
    border-radius: 109px 0px 127px / 8.5em 13em;
    margin: 3em 11em;
}
.order-instructions {
    display: flex;
    max-width: 496px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.order-title {
    background-color: #F5F1EA;
    width: 100%;
    padding: 19px 18px;
    color: #E07040;
    text-align: center;
    letter-spacing: 2px;
    font: 600 40px/1 Magra, sans-serif;
}

@media (max-width: 991px) {
    .order-title {
        max-width: 100%;
        padding: 0 20px;
    }
}
.footer {
    align-items: start;
    display: flex;
    gap: 20px;
    font-weight: 400;
    justify-content: space-between;
    margin-top: 3em;
    padding: 2em 7em 0em 7em;
}

@media (max-width: 991px) {
    .footer {
        flex-wrap: wrap;
    }
}

.footer-column {
    display: flex;
    flex-direction: column;
    font-size: 12px;
    color: #333;
    padding: 0 20px 12px;
}

.footer-logo {
    aspect-ratio: 2.5;
    object-fit: auto;
    object-position: center;
    align-self: center;
}

.footer-message {
    font-family: Lora, sans-serif;
    margin-top: 36px;
}

.footer-title {
    color: #e07040;
    letter-spacing: 1px;
    text-transform: uppercase;
    font: 20px/150% Lora, sans-serif;
    font-weight: 900;
}

.footer-title1 {
    color: #e07040;
    letter-spacing: 1px;
    text-transform: uppercase;
    font: 20px/150% Lora, sans-serif;
    font-weight: 900;
    margin-bottom: 1em;
}

.footer-title2 {
    color: #e07040;
    letter-spacing: 1px;
    text-transform: uppercase;
    font: 20px/150% Lora, sans-serif;
    font-weight: 900;
    margin-bottom: 1em;
}

.footer-address {
    font-family: "Outfit-Regular", Helvetica;
    font-size: 16px;
    font-weight: 400;
    line-height: 32px;
    align-self: stretch;
    margin-top: 30px;
}

.footer-email {
    font-family: "Outfit-Regular", Helvetica;
    font-size: 16px;
    font-weight: 400;
    font-weight: 700;
    line-height: 32px;
}

.footer-language {
    color: #333;
    margin-top: 13px;
    font: 18px/156% Open Sans, sans-serif;
}

.footer-language-option {
    margin-top: 33px;
    gap: 6px;
    white-space: nowrap;
    line-height: 173%;
}

@media (max-width: 991px) {
    .footer-language-option {
        white-space: initial;
    }
}

.footer-language-flag {
    aspect-ratio: 1.45;
    object-fit: auto;
    object-position: center;
    width: 16px;
    align-self: start;
}

.footer-language-name {
    font-family: Open Sans, sans-serif;
}

.footer-link {
    margin-top: 13px;
    font-family: "Outfit-Regular", Helvetica;
    font-size: 17px;
    font-weight: 400;
}

.footer-social {
    color: #959595;
    margin-top: 32px;
    font: 15px/213% Open Sans, sans-serif;
}

.footer-rect {
    width: 100%;
    height: 5vh;
    background-color: #e07040;
}
.image-gallery {
    display: flex;
    gap: 19px;
  }
  
  .gallery-link {
    display: inline-block;
    text-decoration: none;
  }
  
  .gallery-image {
    object-fit: contain;
    object-position: center;
  }
  
  .small-image {
    width: 20px;
    aspect-ratio: 1;
  }
  .medium-image {
    width: 28px;
    aspect-ratio: 1.4;
  }
  
  .large-image {
    width: 22px;
    aspect-ratio: 1.16;
    align-self: start;
  }
.cont{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 3em;
}
.flag{
    margin-top: 1em;
    margin-left: 3em;
}
.service-header1 {
    display: flex;
    align-items: center;
    gap: 40px 44px;
    color: #e07040;
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 2px;
    font: 600 40px/1 Magra, sans-serif;
    margin-top: 0.5em;
}

.service-line1 {
    background-color: rgba(224, 112, 64, 0.4);
    align-self: stretch;
    width: 448px;
    max-width: 100%;
    height: 12px;
    margin: auto 0;
}

.service-title1 {
    align-self: stretch;
    flex-basis: auto;
}

.service-header2 {
    display: flex;
    align-items: center;
    gap: 40px 44px;
    color: #e07040;
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 2px;
    font: 600 40px/1 Magra, sans-serif;
    margin-top: 0.5em;
}

.service-line2 {
    background-color: rgba(224, 112, 64, 0.4);
    align-self: stretch;
    width: 428px;
    max-width: 100%;
    height: 12px;
    margin: auto 0;
}

.service-title2 {
    align-self: stretch;
    flex-basis: auto;
}
</style>