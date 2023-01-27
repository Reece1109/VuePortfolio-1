<template>
  <div class="about-page">
    <h1 class="page-title"> About Me</h1> 
    <div class="about-me-container">
      <img class="profile-pic col-6" src="https://i.postimg.cc/436n23kr/fb-img-1667475337493.jpg" alt="Profile Picture">
      <div class="about-me-content col-6">
        <p>My name is Reece Simon and I am a open-minded, goal driven and an aspiring Developer.
          I am always looking for new opportunities to grow and acquire new skills and tools. 
          I see myself as a asset to any workspace because of my work ethic, perseverance and drive for success .
          I am really interested in the Cyber Security part of coding. As I am all about safeguarding and protecting privileged information and theft.</p>
      </div>
    </div>
  </div>
</template>

<script>
import {  } from 'vue'
export default {
  
}
</script>

<style>
.about-page {
  text-align: center;
  background-image: url(https://i.postimg.cc/sxwPgq23/about-port.jpg);
}

.page-title {
  margin-top: 50px;
  font-size: 50px;
}

.about-me-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 50px;
  font-size: 30px;
  margin-bottom: 50px;
}

.about-me-content {
  text-align: left;
  margin-left: 50px;
}

.profile-pic {
  width: 500px;
  height: 500px;
  /* border-radius: 50%; */
}

.contact-info {
  margin-top: 50px;
}
</style>
