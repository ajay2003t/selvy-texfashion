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
    <section class="sec2">
      <div class="sec2-text">
        <h1>SELVYTEX</h1>
        <p>Selvy Tex exceptionally blends premium fabrics like Polyester, Viscose, and Modal <br> to create outstanding
          garments, offering clients more than just a product and <br>providing strong partnerships and guaranteed high
          quality. Our meticulous <br> production process, from cutting to packing, is overseen by a specialized
          Quality<br>Control Team, ensuring each stage meets the highest standards for export.</p>
      </div>
      <order></order>
    </section>
    <section class="image-section">
      <div class="image-container">
        <img loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/728827dc69be2012abcfd0b704bb8a1fcc2942be34e669a0e82cb6bd2b5bb7ad?placeholderIfAbsent=true&apiKey=5acb37f697474270ad553272da64e56a"
          alt="Decorative image" class="main-image" />
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
export default {
  name: 'ContactForm',
  data() {
    return {
      firstName: '',
      lastName: '',
      email: '',
      phone: '',
      message: ''
    }
  },
  methods: {
    submitForm() {
      console.log('Form submitted', this.$data);
    }
  }
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

.sec2 {
  height: 111vh;
  width: 100%;
  background-image: url(/src/assets/Ellipse.png);
  background-position: center;
  background-size: cover;
  margin-top: 4em;
}

.sec2-text h1 {
  color: #d25d38;
  font-family: "Magra-Bold", Helvetica;
  font-size: 40px;
  font-weight: 700;
  letter-spacing: 2px;
  line-height: 50px;
  text-align: center;
  padding-top: 4em;
}

.sec2-text p {
  font-family: "Open Sans-Regular", Helvetica;
  text-align: center;
  font-size: 20px;
  font-weight: 400;
  line-height: 27px;
  margin-top: 1em;
}

.contact-container {
  display: flex;
  justify-content: space-between;
  padding: 40px;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  border-radius: 20px;
  width: 80%;
  margin: 0 auto;
  margin-top: 4em;
  height: 85%;

}

.contact-info {
  margin-right: 40px;
  padding: 0em 4em;
}

.contact-info h2 {
  color: #e07040;
  font-family: "Magra-Bold", Helvetica;
  font-size: 48px;
  font-weight: 700;
  height: 100px;
  left: 0;
  letter-spacing: 0;
  line-height: 100px;
  text-align: center;
  white-space: nowrap;
}

.info {
  margin-top: 2em;
}

.social-media {
  margin-top: 2em;
}

.social-img {
  margin-top: 1em;
}

.social-img img {
  margin-left: 1em;
}

.social-media h3 {
  color: #e07040;
  font-family: "Magra-Bold", Helvetica;
  font-size: 24px;
  font-weight: 700;
  letter-spacing: 0;
  white-space: nowrap;
}

.contact-form {
  font-family: Poppins, sans-serif;
  text-align: center;
  max-width: 698px;
  margin: 0 auto;
}

.form-container {
  background-color: rgba(224, 112, 64, 0.9);
  border-radius: 20px;
  padding: 1em 56px;
  height: 97%;

}

.form-title {
  color: #fff;
  font: 600 48px/100px Magra, sans-serif;
  margin-bottom: 0.40em;
}

.name-fields {
  display: flex;
  gap: 40px;
  margin-bottom: 3px;
}

.input-group {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 100%;
  margin-bottom: 18px;
}

.input-group label {
  color: #fff;
  font-size: 15px;
  font-weight: 400;
  margin-bottom: 11px;
}

.input-field {
  width: 100%;
  padding: 15px;
  border: none;
  border-radius: 15px;
  background-color: #fff;
  font-size: 14px;
  color: rgba(0, 0, 0, 0.8);
  font-weight: 275;
}

.phone-input {
  display: flex;
  align-items: center;
  background-color: #fff;
  border-radius: 15px;
  padding: 0 25px;
  width: 96%;
}

.country-code {
  color: #000;
  font-size: 15px;
  font-weight: 300;
  margin-right: 17px;
}

.message-area {
  height: 17vh;
  resize: vertical;
}

.submit-button {
  background-color: #fff;
  border: none;
  border-radius: 15px;
  color: rgba(0, 0, 0, 0.8);
  cursor: pointer;
  font-size: 20px;
  font-weight: 400;
  padding: 13px 70px;
  transition: background-color 0.3s ease;
}

.submit-button:hover {
  background-color: #f0f0f0;
}

@media (max-width: 991px) {
  .form-container {
    padding: 26px 20px;
  }

  .form-title {
    font-size: 40px;
    line-height: 93px;
  }

  .name-fields {
    flex-direction: column;
    gap: 20px;
  }

  .submit-button {
    width: 100%;
    padding: 13px 20px;
  }
}

.image-section {
  display: flex;
  padding-top: 123px;
  flex-direction: column;
  margin-top: 33em;
}

.image-container {
  background-color: rgba(224, 112, 64, 0.55);
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 80px 146px;
}

.main-image {
  aspect-ratio: 4.1;
  object-fit: contain;
  object-position: center;
  width: 100%;
  z-index: 10;
  max-width: 1110px;
  margin: -123px 0 -29px;
}

@media (max-width: 991px) {
  .image-section {
    padding-top: 100px;
  }

  .image-container {
    max-width: 100%;
    padding: 0 20px 100px;
  }

  .main-image {
    max-width: 100%;
    margin-bottom: 10px;
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
</style>
