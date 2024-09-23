<template>
    <div> <!--service-->
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
        <div class="service-header">
            <div class="service-line"></div>
            <h2 class="service-title">OUR SERVICES</h2>
            <div class="service-line"></div>
        </div>
        <div class="sec1">
            <img
                src="https://cdn.builder.io/api/v1/image/assets%2Faf0c4f4a34884a7c857808257a84dbe0%2F7ffb2b5d70dd4f39a27765f401b3446b">
        </div>
        <div class="sec2">
            <img
                src="https://cdn.builder.io/api/v1/image/assets%2Faf0c4f4a34884a7c857808257a84dbe0%2F5674fcd44c9d4c8495c2e25dd0ba3a00">
        </div>
        <div class="sec3">
            <img
                src="https://cdn.builder.io/api/v1/image/assets%2Faf0c4f4a34884a7c857808257a84dbe0%2Fb83ba3684db04e1f8c980b3445a2d913">
        </div>
        <div class="sec4">
            <img
                src="https://cdn.builder.io/api/v1/image/assets%2Faf0c4f4a34884a7c857808257a84dbe0%2F3fb2734da7e94ef09d6e8501094c119e">
        </div>
        <div class="sec5">
            <img src="https://cdn.builder.io/api/v1/image/assets%2Faf0c4f4a34884a7c857808257a84dbe0%2Fa0a74457f7ce4e42a3484787a10b81f3"
                class="responsive-image">
        </div>
        <div class="sec6">
            <img
                src="https://cdn.builder.io/api/v1/image/assets%2Faf0c4f4a34884a7c857808257a84dbe0%2F34e2bf7b808948cc9e101807c0d35e9e">
        </div>
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
    margin-top: 5em;
}

.sec1 img {
    width: 100%;
}

.sec2 {
    margin-top: 5em;
}

.sec2 img {
    width: 100%;
}

.sec3 {
    margin-top: 5em;
}

.sec3 img {
    width: 100%;
}

.sec4 {
    margin-top: 5em;
}

.sec4 img {
    width: 100%;
}

.sec5 {
    margin-top: 5em;
}

.sec5 img {
    width: 100%;
}

.sec6 {
    margin-top: 5em;
}

.sec6 img {
    width: 100%;
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
.cont {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 2em;
}

.flag {
    margin-top: 1em;
    margin-left: 3em;
}

.service-header {
    display: flex;
    align-items: center;
    gap: 40px 44px;
    color: #e07040;
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 2px;
    font: 600 40px/1 Magra, sans-serif;
    margin-top: 0.5em;
    margin-bottom: 2em;
}

.service-line {
    background-color: rgba(224, 112, 64, 0.4);
    align-self: stretch;
    width: 447px;
    max-width: 100%;
    height: 12px;
    margin: auto 0;
}

.service-title {
    align-self: stretch;
    flex-basis: auto;
}
</style>