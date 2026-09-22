

[index.html](https://github.com/user-attachments/files/32533793/index.html)
[style.css](https://github.com/user-attachments/files/32533819/style.css)@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300..700;1,300..700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;[responsive.css](https://github.com/user-attachments/files/32533843/responsive.css)

  list-style: none;
  outline: none !important;
}

a {
  text-decoration: none !important;
  display: inline-block !important;
}
@media (max-width: 1199px) {
  .banner-title h1 {
    font-size: 60px;
    letter-spacing: 12px;
    line-height: 1.3;
  }
  .authentic-img img,
  .blushing-bride .authentic-img img,
  .capture-emotion .authentic-img img {
    width: 100%;
    height: auto;
  }
  .authentic-box-main.blushing-bride {
    width: 100%;
  }
  .love-shades .authentic-img img {
    height: auto;
  }
  .testi-content-main {
    padding: 60px 40px;
    width: 100%;
    left: 0;
  }
  .web-title h2 {
    font-size: 38px;
    letter-spacing: 6px;
    white-space: normal;
  }
}

@media (max-width: 991px) {
  .spacing {
    padding: 60px 0;
  }
  .header-logo img {
    width: 150px;
  }
  .row.align-item-center {
    position: relative;
  }
  .navbar-toggler-custom {
    display: flex;
  }
  .navigation {
    position: absolute;
    top: 100%;
    left: 0;
    width: 100%;
    background: var(--bg);
    border-bottom: 1px solid var(--c10);
    max-height: 0;
    overflow: hidden;
    transition: max-height .4s ease;
    z-index: 99;
  }
  .navigation.open {
    max-height: 400px;
  }
  .navigation nav ul {
    flex-direction: column;
    align-items: flex-start;
    gap: 0;
    padding: 10px 15px 20px;
  }
  .navigation nav ul li {
    width: 100%;
    padding: 10px 0;
    border-bottom: 1px solid rgba(0, 0, 0, 0.06);
  }
  .banner-img img {
    height: 550px;
  }
  .banner-title h1 {
    font-size: 42px;
    letter-spacing: 6px;
    line-height: 1.3;
    margin-bottom: 15px;
  }
  .banner-title p {
    font-size: 15px;
    margin-bottom: 20px;
  }
  .banner-title.web-title.web-btn a {
    padding: 12px 40px;
    font-size: 13px;
    border-radius: 5px;
  }
  .banner-dots {
    bottom: 20px;
  }
  .banner-dots .dot {
    width: 30px;
    height: 30px;
  }
  .capture-emotion,
  .love-shades {
    margin-top: 40px;
  }
  .col-lg-5 + .col-lg-5 {
    margin-top: 40px;
  }
  .love-shades-img {
    display: none;
  }
  .video-title p {
    font-size: 16px;
  }
  .video-button a {
    width: 150px;
    height: 150px;
    font-size: 13px;
  }
  .plant-img {
    display: none;
  }
  .counter-box {
    text-align: center;
    margin-bottom: 40px;
  }
  .counter-box h2 {
    position: static;
    font-size: 60px;
    line-height: 1;
    margin-bottom: 10px;
    color: var(--c21);
  }
  .counter-box h4 {
    margin-right: 0;
  }
  .testi-img {
    top: 0;
    margin-bottom: 30px;
  }
  .testi-content-main {
    padding: 40px 25px;
  }
  .footer-space {
    border-left: none;
    padding: 25px 15px;
  }
  .footer-logo.footer-space {
    padding: 25px 15px;
  }
  .footer-newsletter.footer-space {
    border-right: none;
  }
  .footer-top-row > div {
    margin-bottom: 10px;
  }
  .touch-plant-img-1,
  .touch-plant-img-2 {
    display: none;
  }
}

@media (max-width: 767px) {
  .spacing {
    padding: 45px 0;
  }
  .banner-img img {
    height: 420px;
  }
  .banner-title h1 {
    font-size: 30px;
    letter-spacing: 3px;
  }
  .banner-title p {
    font-size: 13px;
  }
  .web-title h2 {
    font-size: 28px;
    letter-spacing: 3px;
  }
  .web-title p {
    font-size: 16px;
  }
  .authentic-content h2 {
    font-size: 19px;
  }
  .video-title p {
    font-size: 14px;
    letter-spacing: 1px;
  }
  .video-button a {
    width: 110px;
    height: 110px;
    font-size: 11px;
  }
  .counter-sec {
    margin: 30px 0;
  }
  .counter-box h2 {
    font-size: 42px;
  }
  .counter-box h4 {
    font-size: 11px;
  }
  .testi-content p {
    font-size: 14px;
  }
  .blog-content a h2 {
    font-size: 20px;
  }
  .Touch {
    padding: 45px 0;
  }
  .row.touch-form-row {
    padding: 35px 15px;
  }
  .touch-btn-wrap.web-btn a {
    padding: 14px 40px;
    font-size: 12px;
    border-radius: 5px;
  }
  .footer-logo h3 {
    font-size: 28px;
    letter-spacing: 3px;
  }
}

@media (max-width: 480px) {
  .header-logo img {
    width: 120px;
  }
  .banner-img img {
    height: 340px;
  }
  .banner-title h1 {
    font-size: 22px;
    letter-spacing: 1.5px;
    line-height: 1.4;
  }
  .banner-title p {
    font-size: 12px;
    margin-bottom: 15px;
  }
  .banner-title.web-title.web-btn a {
    padding: 10px 26px;
    font-size: 11px;
    border-radius: 5px;
  }
  .banner-dots .dot {
    width: 22px;
    height: 22px;
    margin: 0 4px;
  }
  .web-title h2 {
    font-size: 22px;
  }
  .web-title p {
    font-size: 13px;
  }
  .video-button a {
    width: 90px;
    height: 90px;
    font-size: 10px;
  }
  .counter-box h2 {
    font-size: 32px;
  }
  .testi-content-main {
    padding: 30px 15px;
  }
  .testi-date h4 {
    font-size: 18px;
  }
  .footer-social {
    flex-wrap: wrap;
  }
}
img {
  width: 100%;
  display: block;
}

ul {
  padding: 0;
  margin: 0 !important;
}

h1, h2, h3, h4, h5, h6 {
  padding: 0;
  margin: 0;
}

:root {
  --c1: #000;
  --c2: #fff;
  --c3: #171717;
  --c4: #0b0b0b;
  --c5: #6b6b6b;
  --c6: #8e8e8e;
  --bg: #e8e5e0;
  --c7: #1b2338;
  --c8: #72726C;
  --c9: #AFAFA5;
  --c10: #E5E4E0;
  --c11: #F4F0ED;
  --c12: #4D504A;
  --c13: #E1E1E1;
  --c14: #e0e0e0;
  --c15: #7a8b6f;
  --c16: #e5e5e5;
  --c17: #b0b0b0;
  --c18: #555555;
  --c19: #4a6b8a;
  --c20: #f2ede8;
  --c21: #ECECEA;
  --c22: #F5F0EB;
  --f1: 'Cormorant Garamond';
  --f2: 'Inter';
}

.row.align-item-center {
  align-items: center;
}
.navigation ul li a:hover
.authentic-photos:before
.video-sec:before
.touch-btn:hover
.footer-col:not(:last-child)::after


.spacing {
  padding: 100px 0;
}

body {
  font-family: var(--f2);
  background: var(--bg);
}

.header {
  background: var(--bg);
  border-bottom: 1px solid var(--c10);
  padding: 7px;
}

.header-logo {
  display: flex;
  align-items: center;
  gap: 14px;
}

.navigation nav ul {
  display: flex;
  align-items: center;
  gap: 42px;
  justify-content: end;
}

.navigation ul li a {
  color: var(--c1);
  font-weight: 500;
  font-size: 13px;
  text-transform: uppercase;
  font-family: var(--f2);
  letter-spacing: 3.3px;
  transition: all .5s;
}

.navigation nav ul li a:hover {
  color: var(--c6);
}

.header-logo img {
  width: 210px;
}

.banner-main {
  position: relative;
  width: 100%;
  overflow: hidden;
}

.banner-content {
  position: relative;
  width: 100%;
}

.banner-slide {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  visibility: hidden;
  z-index: 1;
  transition: opacity 0.7s ease;
}

.banner-slide.active {
  position: relative;
  opacity: 1;
  visibility: visible;
  z-index: 2;
}

.banner-img {
  width: 100%;
  height: 100%;
}
.banner-img::before {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: var(--c1);
    content: "";
    z-index: 2;
    opacity: 0.4;
}

.banner-img img {
  width: 100%;
  height: 800px;
  object-fit: cover;
  display: block;
  filter: grayscale(100%);
}

.banner-slide .container {
  position: absolute;
  top: 50%;
  left: 0;
  right: 0;
  transform: translateY(-50%);
  z-index: 2;
}

.banner-title {
  text-align: center;
  color: var(--c2);
}

.banner-title h1 {
  font-family: var(--f1);
  font-size: 80px;
  letter-spacing: 23px;
  text-transform: uppercase;
  font-weight: 400;
  line-height: 1.4;
  margin-bottom: 20px;
}

.banner-title p {
  font-family: 'Playfair Display', serif;
  font-style: italic;
  font-size: 18px;
  color: var(--c2);
  margin-bottom: 35px;
}

.banner-title.web-title.web-btn p {
  color: var(--c2);
}

.banner-title.web-title.web-btn a:hover {
  background: none;
}

.banner-title.web-title.web-btn a {
  transition: all .5s;
  text-align: center;
  margin: 0 auto;
  background: var(--c9);
  border: 0;
  color: var(--c2);
  font-size: 15px;
  font-weight: 500;
  letter-spacing: 3px;
  font-family: var(--f2);
  padding: 15px 60px;
  border: 1px solid var(--c9);
  border-radius: 5px;
}

.banner-main::before {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: var(--c1);
  content: "";
  z-index: 2;
  opacity: 0.4;
}

.banner-dots {
  position: absolute;
  bottom: 40px;
  left: 0;
  right: 0;
  text-align: center;
  z-index: 3;
}

.banner-dots .dot {
  display: inline-block;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  border: 1px solid var(--c2);
  margin: 0 6px;
  position: relative;
  cursor: pointer;
}

.banner-dots .dot::before {
  content: '';
  position: absolute;
  top: 50%;
  left: 50%;
  width: 5px;
  height: 5px;
  background: transparent;
  border-radius: 50%;
  transform: translate(-50%, -50%) rotate(45deg);
  transition: background 0.3s ease;
}

.banner-dots .dot.active::before {
  background: var(--c2);
}

.authentic-photos,
.video-sec {
  position: relative;
}
section.video-sec.spacing {
  padding: 100px 0;
}
section.authentic-photos.spacing {
    padding: 100px 0;
}
.authentic-photos:before,
.video-sec:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 50%;
  background-color: var(--c11);
  z-index: -1;
}

.web-title h2 {
  font-size: 48px;
  font-weight: 400;
  font-family: var(--f1);
  text-transform: uppercase;
  letter-spacing: 9.6px;
  margin-bottom: 5px;
  white-space: nowrap;
}

.web-title p {
  font-size: 22px;
  font-weight: 400;
  font-style: italic;
  font-family: var(--f1);
  color: var(--c8);
}

.authentic-title,
.web-title {
  margin-bottom: 60px;
}

.authentic-img img {
  width: 560px;
  height: 685px;
  transition: all .9s;
}

.authentic-content h4 {
  font-size: 13px;
  font-weight: 500;
  font-family: var(--f2);
  text-transform: uppercase;
  letter-spacing: 3.3px;
  color: var(--c12);
  margin-bottom: 4px;
}

.authentic-content h2 {
  font-size: 24px;
  font-weight: 400;
  font-family: var(--f1);
  text-transform: uppercase;
  letter-spacing: 3.3px;
}

.authentic-img {
  margin-bottom: 20px;
  overflow: hidden;
}

.blushing-bride .authentic-img img {
  width: 456px;
  height: 575px;
  transition: all .9s;
}
.authentic-img img:hover {
    transform: scale(1.2);
    overflow: hidden;
}
.authentic-box-main.blushing-bride {
  width: 456px;
  margin-left: auto;
}

.capture-emotion .authentic-img img {
  width: 100%;
  height: 583px;
  object-fit: cover;
}

.capture-emotion,
.love-shades {
  margin-top: 120px;
  overflow: hidden;
}

.love-shades {
  position: relative;
}

.love-shades-img {
  position: absolute;
  bottom: -180px;
  right: -70px;
  width: 228px;
}

.love-shades .authentic-img img {
  width: 100%;
  height: 674px;
}

.video-title p {
  font-size: 22px;
  font-weight: 400;
  text-transform: uppercase;
  letter-spacing: 3.3px;
  color: var(--c8);
  font-family: var(--f1);
  text-align: center;
}

.video-sec-main {
  position: relative;
}

.video-button {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.video-button a {
  color: var(--c2);
  font-size: 16px;
  font-weight: 500;
  font-family: var(--f2);
  text-transform: uppercase;
  letter-spacing: 2.4px;
  width: 260px;
  height: 260px;
  text-align: center;
  align-content: center;
  border: 1px solid var(--c2);
  border-radius: 50%;
}

.video-button a i {
  margin-right: 6px;
}

.video-title {
  margin-bottom: 70px;
}

.plant-img {
  position: absolute;
  left: -210px;
  bottom: 90px;
}

.blog-img img {
    object-fit: cover;
}

.counter-box {
  position: relative;
  text-align: right;
}

.counter-box h2 {
  position: absolute;
  top: -70px;
  font-size: 100px;
  font-weight: 400;
  font-family: var(--f1);
  color: var(--c21);
  line-height: 100px;
  right: 0;
}

.counter-box h4 {
  position: relative;
  z-index: 2;
  font-size: 12px;
  font-family: var(--f2);
  letter-spacing: 3.3px;
  text-transform: uppercase;
  margin-right: 45px;
}

.counter-sec {
  margin: 90px 0;
}
section.counter-sec.spacing {
  padding: 0 0 100px 0;
}

.testimonials {
  background-color: var(--c11);
  padding: 100px 0px 160px;
}

.testi-title h2,
.blog-title h2,
.contact-title h2,
.insta-content h2 {
  font-size: 35px;
}
section.blog.spacing {
    padding: 100px 0;
}

.testi-content-main {
  padding: 110px 80px 110px 150px;
  text-align: center;
  background-color: var(--c2);
  width: 110%;
  position: relative;
  left: -60px;
}

.testi-date h4 {
  color: var(--c8);
  font-size: 24px;
  font-weight: 400;
  font-style: italic;
  font-family: var(--f1);
  margin-bottom: 20px;
}

.testi-content p {
  font-weight: 300;
  font-size: 16px;
  font-family: var(--f2);
  line-height: 25px;
  margin-bottom: 20px;
  color: var(--c8);
}

.author-detail h2 {
  font-weight: 500;
  font-size: 14px;
  font-family: var(--f2);
  text-transform: uppercase;
  color: var(--c8);
  letter-spacing: 3.3px;
}

.testi-img {
  position: relative;
  top: 30px;
  z-index: 9;
}

.blog-img {
  margin-bottom: 20px;
}

.blog-content h3 {
  font-size: 22px;
  font-weight: 400;
  font-style: italic;
  font-family: var(--f1);
  color: var(--c8);
  margin-bottom: 5px;
}

.blog-content a h2 {
  font-size: 26px;
  font-weight: 400;
  font-family: var(--f1);
  text-transform: uppercase;
  letter-spacing: 3.3px;
  color: var(--c12);
  margin-bottom: 10px;
}

.blog-content p {
  font-size: 15px;
  font-weight: 300;
  font-family: var(--f2);
  color: var(--c8);
  margin-bottom: 25px;
}

.web-btn.blog a {
  padding: 15px 20px;
  transition: all .5s;
}

.web-btn.blog a:hover {
  color: var(--c2);
  background: var(--c9);
}

.blog-content a {
  font-size: 14px;
  font-weight: 500;
  font-family: var(--f2);
  text-transform: uppercase;
  color: var(--c12);
  letter-spacing: 3.3px;
}

.blog-content {
  text-align: left;
}

.Touch {
  position: relative;
  padding: 80px 0;
  overflow: hidden;
}

.touch-title {
  text-align: center;
  margin-bottom: 40px;
}

.touch-form-row {
  position: relative;
}

.touch-leaf {
  position: absolute;
  top: -220px;
  width: 220px;
  z-index: 1;
}

.touch-leaf img {
  width: 100%;
  height: auto;
}

.touch-form {
  position: relative;
  z-index: 2;
}

.form-group {
  margin-bottom: 45px;
}

.form-group label {
  display: block;
  font-size: 12px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--c8);
  margin-bottom: 10px;
  font-weight: 500;
  text-align: center;
  padding: 15px 0;
}

.form-group input,
.form-group textarea {
  width: 100%;
  border: none;
  border-bottom: 1px solid var(--c14);
  /* padding: 6px 0; */
  font-size: 15px;
  color: var(--c6);
  background: transparent;
  outline: none;
  font-family: inherit;
}

.form-group textarea {
  resize: none;
  height: 90px;
}

.touch-btn-wrap {
  text-align: center;
  margin-top: 10px;
}

.touch-btn-wrap.web-btn a {
  padding: 16px 80px;
  letter-spacing: 3px;
  font-size: 14px;
  text-transform: uppercase;
  transition: all 0.5s ease;
  color: var(--c2);
  background: var(--c9);
  border: 1px solid var(--c9);
  border-radius: 5px;
}

.touch-btn-wrap.web-btn a:hover {
  color: var(--c9);
  background: none;
  transform: translateY(-3px);
  border: 1px solid var(--c9);
}

.touch-btn {
  display: inline-block;
  padding: 15px 70px;
  letter-spacing: 3px;
  font-size: 14px;
  text-transform: uppercase;
  transition: all .5s;
}

.touch-btn:hover {
  background: var(--c2);
  color: var(--c5);
  border: 1px solid var(--c6);
}

.touch-plant-img-1 {
  position: absolute;
  top: 110px;
  right: 0;
}

.touch-plant-img-2 {
  position: absolute;
  top: 100px;
  transform: rotateY(-180deg);
}

.row.touch-form-row {
  border: 1px solid var(--c13);
  padding: 60px 0;
}

section.instagram.spacing {
  padding-top: 0;
}

.footer {
  width: 100%;
  border-top: 80px solid var(--c22);
}

.footer-top {
  padding: 70px 0;
  background: var(--c2);
  text-align: center;
}

.footer-top-row {
  position: relative;
  align-items: center;
}

.footer-col {
  position: relative;
  text-align: center;
  padding: 0 30px;
}

.footer-col:not(:last-child)::after {
  content: '';
  position: absolute;
  top: -50px;
  bottom: -50px;
  right: 0;
  width: 1px;
  background: var(--c16);
}

.footer-follow h4 {
  font-family: var(--f1);
  font-size: 24px;
  letter-spacing: 4px;
  text-transform: uppercase;
  font-weight: 400;
  margin-bottom: 20px;
}

.footer-social {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  margin-bottom: 20px;
}

.footer-social a {
  color: var(--c8);
  font-size: 15px;
  text-decoration: none;
}

.footer-social .dash {
  width: 16px;
  height: 1px;
  background: var(--c17);
  display: inline-block;
}

.footer-email {
  font-family: var(--f1);
  font-style: italic;
  font-size: 21px;
  color: var(--c8);
}

.footer-logo h3 {
  font-family: var(--f1);
  font-size: 40px;
  letter-spacing: 6px;
  text-transform: uppercase;
  font-weight: 400;
  color: var(--c8);
  padding-bottom: 20px;
}

.footer-newsletter {
  text-align: center;
}

.footer-newsletter h4 {
  font-family: var(--f1);
  font-size: 23px;
  letter-spacing: 4px;
  text-transform: uppercase;
  font-weight: 400;
  margin-bottom: 8px;
  color: var(--c8);
}

.footer-newsletter p {
  font-family: var(--f1);
  font-style: italic;
  font-size: 17px;
  color: var(--c15);
  margin-bottom: 20px;
}

.newsletter-form label {
  display: block;
  text-align: left;
  font-size: 12px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--c18);
}

.newsletter-input-wrap {
  display: flex;
  align-items: center;
  border-bottom: 1px solid var(--c16);
  padding-bottom: 6px;
}

.newsletter-input-wrap input {
  flex: 1;
  border: none;
  outline: none;
  background: transparent;
  font-size: 14px;
  padding: 4px 0;
  font-family: inherit;
}

.newsletter-input-wrap button {
  background: none;
  border: none;
  cursor: pointer;
  color: var(--c19);
  font-size: 16px;
}

.footer-bottom {
  background: var(--c20);
  padding: 10px 0;
  text-align: center;
}

button i {
  color: var(--c6);
  font-size: 15px;
}

.footer-bottom p {
  font-family: var(--f1);
  font-style: italic;
  font-size: 19px;
  color: var(--c12);
  margin: 0;
}

input::placeholder {
  color: var(--c8);
  font-family: var(--f2);
  letter-spacing: 3px;
  font-size: 12px;
}

.footer-space {
  padding: 41px;
  border-left: 1px solid var(--c13);
}

.footer-logo.footer-space {
  padding: 70px;
}

.footer-newsletter.footer-space {
  border-right: 1px solid var(--c13);
}

.navbar-toggler-custom {
  display: none;
  flex-direction: column;
  justify-content: center;
  gap: 5px;
  width: 34px;
  height: 30px;
  background: transparent;
  border: none;
  cursor: pointer;
  margin-left: auto;
}

.navbar-toggler-custom span {
  display: block;
  width: 100%;
  height: 2px;
  background: var(--c1);
  transition: all .3s ease;
}

.navbar-toggler-custom.active span:nth-child(1) {
  transform: translateY(7px) rotate(45deg);
}

.navbar-toggler-custom.active span:nth-child(2) {
  opacity: 0;
}

.navbar-toggler-custom.active span:nth-child(3) {
  transform: translateY(-7px) rotate(-45deg);
}[Uploading responsive.css…]()


@media (max-width: 1199px) {
  .banner-title h1 {
    font-size: 60px;
    letter-spacing: 12px;
    line-height: 1.3;
  }
  .authentic-img img,
  .blushing-bride .authentic-img img,
  .capture-emotion .authentic-img img {
    width: 100%;
    height: auto;
  }
  .authentic-box-main.blushing-bride {
    width: 100%;
  }
  .love-shades .authentic-img img {
    height: auto;
  }
  .testi-content-main {
    padding: 60px 40px;
    width: 100%;
    left: 0;
  }
  .web-title h2 {
    font-size: 38px;
    letter-spacing: 6px;
    white-space: normal;
  }
}

@media (max-width: 991px) {
  .spacing {
    padding: 60px 0;
  }
  .header-logo img {
    width: 150px;
  }
  .row.align-item-center {
    position: relative;
  }
  .navbar-toggler-custom {
    display: flex;
  }
  .navigation {
    position: absolute;
    top: 100%;
    left: 0;
    width: 100%;
    background: var(--bg);
    border-bottom: 1px solid var(--c10);
    max-height: 0;
    overflow: hidden;
    transition: max-height .4s ease;
    z-index: 99;
  }
  .navigation.open {
    max-height: 400px;
  }
  .navigation nav ul {
    flex-direction: column;
    align-items: flex-start;
    gap: 0;
    padding: 10px 15px 20px;
  }
  .navigation nav ul li {
    width: 100%;
    padding: 10px 0;
    border-bottom: 1px solid rgba(0, 0, 0, 0.06);
  }
  .banner-img img {
    height: 550px;
  }
  .banner-title h1 {
    font-size: 42px;
    letter-spacing: 6px;
    line-height: 1.3;
    margin-bottom: 15px;
  }
  .banner-title p {
    font-size: 15px;
    margin-bottom: 20px;
  }
  .banner-title.web-title.web-btn a {
    padding: 12px 40px;
    font-size: 13px;
    border-radius: 5px;
  }
  .banner-dots {
    bottom: 20px;
  }
  .banner-dots .dot {
    width: 30px;
    height: 30px;
  }
  .capture-emotion,
  .love-shades {
    margin-top: 40px;
  }
  .col-lg-5 + .col-lg-5 {
    margin-top: 40px;
  }
  .love-shades-img {
    display: none;
  }
  .video-title p {
    font-size: 16px;
  }
  .video-button a {
    width: 150px;
    height: 150px;
    font-size: 13px;
  }
  .plant-img {
    display: none;
  }
  .counter-box {
    text-align: center;
    margin-bottom: 40px;
  }
  .counter-box h2 {
    position: static;
    font-size: 60px;
    line-height: 1;
    margin-bottom: 10px;
    color: var(--c21);
  }
  .counter-box h4 {
    margin-right: 0;
  }
  .testi-img {
    top: 0;
    margin-bottom: 30px;
  }
  .testi-content-main {
    padding: 40px 25px;
  }
  .footer-space {
    border-left: none;
    padding: 25px 15px;
  }
  .footer-logo.footer-space {
    padding: 25px 15px;
  }
  .footer-newsletter.footer-space {
    border-right: none;
  }
  .footer-top-row > div {
    margin-bottom: 10px;
  }
  .touch-plant-img-1,
  .touch-plant-img-2 {
    display: none;
  }
}

@media (max-width: 767px) {
  .spacing {
    padding: 45px 0;
  }
  .banner-img img {
    height: 420px;
  }
  .banner-title h1 {
    font-size: 30px;
    letter-spacing: 3px;
  }
  .banner-title p {
    font-size: 13px;
  }
  .web-title h2 {
    font-size: 28px;
    letter-spacing: 3px;
  }
  .web-title p {
    font-size: 16px;
  }
  .authentic-content h2 {
    font-size: 19px;
  }
  .video-title p {
    font-size: 14px;
    letter-spacing: 1px;
  }
  .video-button a {
    width: 110px;
    height: 110px;
    font-size: 11px;
  }
  .counter-sec {
    margin: 30px 0;
  }
  .counter-box h2 {
    font-size: 42px;
  }
  .counter-box h4 {
    font-size: 11px;
  }
  .testi-content p {
    font-size: 14px;
  }
  .blog-content a h2 {
    font-size: 20px;
  }
  .Touch {
    padding: 45px 0;
  }
  .row.touch-form-row {
    padding: 35px 15px;
  }
  .touch-btn-wrap.web-btn a {
    padding: 14px 40px;
    font-size: 12px;
    border-radius: 5px;
  }
  .footer-logo h3 {
    font-size: 28px;
    letter-spacing: 3px;
  }
}

@media (max-width: 480px) {
  .header-logo img {
    width: 120px;
  }
  .banner-img img {
    height: 340px;
  }
  .banner-title h1 {
    font-size: 22px;
    letter-spacing: 1.5px;
    line-height: 1.4;
  }
  .banner-title p {
    font-size: 12px;
    margin-bottom: 15px;
  }
  .banner-title.web-title.web-btn a {
    padding: 10px 26px;
    font-size: 11px;
    border-radius: 5px;
  }
  .banner-dots .dot {
    width: 22px;
    height: 22px;
    margin: 0 4px;
  }
  .web-title h2 {
    font-size: 22px;
  }
  .web-title p {
    font-size: 13px;
  }
  .video-button a {
    width: 90px;
    height: 90px;
    font-size: 10px;
  }
  .counter-box h2 {
    font-size: 32px;
  }
  .testi-content-main {
    padding: 30px 15px;
  }
  .testi-date h4 {
    font-size: 18px;
  }
  .footer-social {
    flex-wrap: wrap;
  }
}
