<template>
  <div>
    <v-app-bar
      light
      fixed
      prominent
      elevate-on-scroll
    >
      <v-toolbar-title class="image">
        <a class="a_icon" href="https://f-ventures.vc" target="_blank">
          <v-img :src="require('~/assets/img/F-Ventures_logo2.jpg')" />
        </a>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <a class="a_form a_button" href="https://docs.google.com/forms/d/e/1FAIpQLSfUOTLJO3ItHCT-CcBCwqD0FnQ3arEQWxJHzbUlKbRPvHRk9w/viewform?usp=sf_link" target="_blank">
        <v-btn color="#3399ff" class="nav_button_send" x-large :min-height="60" :min-width="80">
          <span class="span_container1">
            The Prologueに申し込む
          </span>
        </v-btn>
      </a>
    </v-app-bar>
  </div>
</template>

<style>
  .container {
    width: 100%;
    height: 100%;
  }
  .image {
    width: 400px;
    margin: 15px;
    display: block;
  }
  .menu {
    margin: 15px;
    padding: 30px;
    text-align: right;
  }
  .twitter {
    margin: 40px 40px 0px 60px;
  }
  .button {
    color: "#fff"
  }
  .a_form {
    text-decoration: none;
    color: "#fff"
  }
  .a_icon {
    text-decoration: none;
    color: "#fff"
  }

  @media screen and (max-width: 767px) {
  .img{
    width: 100%;
    height: 100%;
    max-width: 375px;
    min-height: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .nav_button_send {
    display: none;
  }
  .a_button {
    display: none;
  }
  .nav_button_twitter {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 10px 15px 10px 10px;
    margin: 55px 0px 20px 10px;
    font-size: 15px;
    font-weight: bold;
    display: center;
  }
  .span {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 15px
  }
  .h1_subtitle{
    margin: 10px;
    font-size: 40px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 3px;
    font-size: 10px;
    font-weight: bold ;
  }
  .a_icon {
    text-decoration: none;
    color: "#fff"
  }

  .span_icon {
    margin: 0px 10px 0px 290px;
    font-size: 20px;
    font-weight: bold ;
    text-decoration: none;
    color: "#fff"
  }
  .span_container1 {
    color: #fff;
    font-size: 20px;
    font-weight: bold ;
  }
  .twitter_icon {
    margin: 10px 0 0 0;
  }
}

@media screen and (min-width:768px) {
  .img{
    margin-top: 150px;
    width: 100%;
    height: 100%;
    max-width: 800px;
    min-height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .nav_button_send {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 18px;
    margin: 30px;
    color: "#fff";
    font-size: 17px;
    font-weight: bold ;
    display: center;
  }  
  .a_button {
  }
  .nav_button_twitter {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px 50px 15px 30px;
    margin: 30px;
    font-size: 20px;
    font-weight: bold ;
    display: center;
  }
  .span {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 30px
  }
  .h1_subtitle{
    margin: 10px;
    font-size: 50px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 5px;
    font-size: 20px;
    font-weight: bold ;
  }
  .span_icon {
    margin: 10px;
    font-size: 40px;
    font-weight: bold ;
    text-decoration: none;
    color: "#fff"
  }
  .span_container1 {
    color: #fff;
    font-size: 30px;
    font-weight: bold ;
  }
  .twitter_icon {
    margin: 18px 0 0 0;
  }
}
</style>