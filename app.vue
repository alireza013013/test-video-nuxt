<template>
  <div
    style="background-color: black;display: flex;flex-direction: column;align-items: center ;width: 100%;min-height: 100vh;height: 100%;">
    <h1 style="color: white;">Welcome To nuxt</h1>
    <h3 style="color: white;">Test Vidoe Iphone Site</h3>
    <!-- <video controls autoplay muted playsinline width="640" height="360">
      <source
        src="https://avtshare01.rz.tu-ilmenau.de/avt-vqdb-uhd-1/test_1/segments/bigbuck_bunny_8bit_200kbps_360p_60.0fps_h264.mp4"
        type="video/mp4" />
      مرورگر شما از ویدیو پشتیبانی نمی‌کند.
    </video> -->


    <span style="color: white; margin-bottom: 20px">From Server</span>
    <video loop controls autoplay muted playsinline width="640" height="360">
      <source src="https://boomilia.com/media/media/78b2c406497b444ea3e0beada80f98c7.mp4" type="video/mp4" />
      مرورگر شما از ویدیو پشتیبانی نمی‌کند.
    </video>


    <span style="color: white; margin-bottom: 20px">From Local</span>
    <video loop controls autoplay muted playsinline width="640" height="360">
      <source src="./test.mp4" type="video/mp4" />
      مرورگر شما از ویدیو پشتیبانی نمی‌کند.
    </video>
  </div>
</template>


<style>
body {
  margin: 0;
}
</style>