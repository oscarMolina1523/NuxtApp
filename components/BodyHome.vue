<script setup></script>

<template>
    <div class="container">
       <div class="user-data">
        <img class="image-user" src="https://www.recordnet.com/gcdn/presto/2021/03/22/NRCD/9d9dd9e4-e84a-402e-ba8f-daa659e6e6c5-PhotoWord_003.JPG" alt="this is the image">
        <div style="padding-top: 5px; margin-left: 10px">
            <span style="font-weight: bold;">emily_green</span>
            <br>
            <span style="font-size: 13px;"></span>San Francisco, California</span>
        </div>
       </div>
       <img class="body-image" src="https://e0.pxfuel.com/wallpapers/464/288/desktop-wallpaper-fondos-paisajes-naturales-naturaleza-zen-beautiful-scenery-relaxing-zen-nature.jpg" alt="this is the body image">
    </div>
</template>

<style scoped>
.container{
    width: 700px;
    text-align: center;
    flex-direction: column;
    border-right: 1px solid #ccc;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    margin-left: 50px;
}

.user-data{
    height: 50px;
    text-align: start;
    display: flex;
}

.image-user{
  object-fit: cover;
  border-radius: 50%;
  align-items: center;
  height: 40px;
  width: 40px;
  margin-top: 5px;
  margin-left: 5px;
}

.body-image{
  object-fit: cover;
  align-items: center;
  height: 400px;
  width: 500px;
}

span{
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}
</style>
