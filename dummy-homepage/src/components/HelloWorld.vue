<template>
  <div class="layout" style="padding: 90px 0px; background-image: url('main-background.jpg');">
    <center><img src="hello.svg" alt="" style="width: 50%;     margin-bottom: 50px;"></center>

    <div class="main-themes" style="background-image: url('mindcobweb.svg')">
      <center>
        <img class="main-ava" src="ava.png" alt="">
      </center>
          <div class="topics">
      <div class="topic a"><p>backend <br>engineering</p></div>
      <div class="topic b"><p>data <br>engineering</p></div>
      <div class="topic c"><p>product <br>development</p></div>
      <div class="topic d"><p>knowledge <br>sharing</p></div>
      <div class="topic e"><p>blogging <br>ideas<br></p></div>
      <div class="topic f"><p>team <br>working</p></div>
      <div class="topic g"><p>graphic <br>design</p></div>
    </div>
    </div> 

    <center>
      <p class="desc" style="margin: 35px 0px 40px 0px;">
My <b>passion</b> is creating <b>digital products</b>. Combining both the <b>creative</b> and <b>technical</b> skills,<br> 
I bring <b>original ideas</b> to life. I'm <b>passionate</b> about programming, design and photography. <br> 
I have a <b>MA</b> in Computer Science and more than <b>six year</b> work <b>experince</b> in software engineering. <br> 
Welcome to my <b>website</b> where I <b>share</b> my ideas and thoughts with the world. <br> 
Below are my various <b>projects</b>. Hope you find this <b>exiting</b> and useful!<br> 
<b>Follow me</b> on the social media: <br> 
      </p>
    </center>
    <div class="under-construction" style="background-image: url('under-construction.svg')">
      <p>{ ... website under construction ... }</p>
    </div>   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  image: "themes.svg"
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

.layout {
  background:#44207e;
  background-repeat: repeat;
}

.main-themes {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 50%;
    max-width: 748px;
    max-height: 408px;
    margin: auto auto 115px auto;
    height: 400px;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
}

.under-construction {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 410px;
    height: 172px;
    margin: 30px auto 0px auto;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
}

.under-construction p {
    color: #bf99fd;
    font-size: 17px;
    font-weight: 200;
    margin-top: 14px;
}

.main-ava {
    max-width: 195px;
    border: solid 12px #44207e;
    border-radius: 300px;
    margin-top: -82%;
    margin-left: 7%;
}

.desc {
    font-size: 17px;
    line-height: 32px;
    color: #FFFFFF;
    font-style: normal;
    font-weight: 200;
}

.desc b {
  font-weight: 600;
}

.topics {
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 0px;
}

.topic {
    padding: 14px 25px 1px 25px;
    border: 1px dashed #FFFFFF;
    border-radius: 30px 0px;
    text-align: center;
    font-size: 12px;
    line-height: 15px;
    color: white;
    margin: 10px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}


.a {
    margin-top: -107px;
    margin-right: -51px;
}

.b {
    margin-top: 140px;
    margin-right: 125px;
}

.c {
    margin-top: 306px;
    margin-left: -131px;
}

.d {
    margin-top: 492px;
    margin-right: 37px;
}

.e {
    margin-top: 312px;
}

.f {
    margin-top: 108px;
    margin-right: -71px;
}

.g {
    margin-top: -124px;
    margin-right: 231px;
}
        @media screen and (max-width: 850px) {
          .a {
    margin-top: -85px;
    margin-right: -71px;
          }

          .b {
    margin-top: 119px;
    margin-right: -283px;
          }

          .c {
    margin-top: 295px;
    margin-left: 232px;
          }

          .d {
    margin-top: 431px;
    margin-right: 4px;
          }

          .e {
margin-top: 281px;
          }

          .f {
    margin-top: 92px;
    margin-right: -83px;
          }

          .g {
    margin-top: -98px;
    margin-right: 225px;
          }
        }

        @media screen and (max-width: 700px) {

.main-themes {
    display: block;
    background-image: none !important;
    justify-content: center;
    align-items: center;
    width: 50%;
    max-width: 748px;
    margin: auto;
    height: auto;
    max-height: none;
}

.topics {
    display: block;
    min-width: 300px;
    height: 318px;
    margin: 29px auto 10px 0px;
}

.topic {
    display: block;
    float: left;
}

.main-ava {
    margin-top: 0px;
    margin-left: 0px;
}


          .a {
    margin-top: 10px;
    margin-right: 10px;
          }

          .b {
    margin-top: 10px;
    margin-right: 10px;
          }

          .c {
    margin-top: 10px;
    margin-left: 10px;
          }

          .d {
    margin-top: 10px;
    margin-right: 4px;
          }

          .e {
margin-top: 10px;
          }

          .f {
    margin-top: 10px;
    margin-right: 10px;
          }

          .g {
    margin-top: 10px;
    margin-right: 10px;
          }
    
        }


 @media screen and (max-width: 520px) {

  .topics {
    display: block;
    width: 150px;
    height: 555px;
    margin: 29px auto auto 30px;
}

  .topic {
    width: 150px;
    min-width: none;
}

 }


</style>
