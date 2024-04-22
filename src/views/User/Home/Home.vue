<template>
    <div class="containPage">
      <div class="titlePage">
        <h2>
          Welcome to
          <span class="titleWeb">H<span class="text-dark">BOOKS</span></span>
        </h2>
      </div>
      <div class="contentPage">
        <!-- Section: Design Block -->
        <section class="">
          <!-- Jumbotron -->
          <div class="text-center text-lg-start">
            <div class="container">
              <div class="row gx-lg-5 align-items-center">
                <div class="col-lg-6 mb-5 mb-lg-0">
                  <h1 class="my-5 fw-bold ls-tight titleIntro">
                    <!-- There is no friend as loyal as a
                    <span class="titleWeb"
                      >Book.<span class="text-dark"></span
                    ></span> -->
                    <br />
                    <span class="text-primary">Franklin D. Roosevelt</span>
                  </h1>
                  <p style="color: hsl(217, 10%, 50.8%)">
                    Sách không chỉ là nguồn kiến thức, mà còn là người bạn đồng hành trung thành trong cuộc đời. Chúng là ngọn đèn dẫn đường, là nguồn cảm hứng, và là cánh cửa mở ra thế giới vô tận của tri thức và trí tưởng tượng.
                  </p>
  
                  <router-link to="/about" class="text-decoration-none">
                    <button class="btnReadMore">Order now</button>
                  </router-link>
                </div>
  
                <div class="col-lg-6 mb-5 mb-lg-0">
                  <div class="card">
                    <div class="imageCup">
                      <img src="https://i.pinimg.com/564x/a6/cf/46/a6cf46901190c430ab2f22a5163944cd.jpg" alt="" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Jumbotron -->
        </section>
        <!-- Section: Design Block -->
      </div>
    </div>
  </template>
  
  <script setup></script>
  
  <style lang="scss" scoped>
  @import "./Home.scss";
  </style>