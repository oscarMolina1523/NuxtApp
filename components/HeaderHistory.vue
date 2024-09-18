<script setup>
const images = [
  {
    title: 'john_doe',
    url: 'https://imgv3.fotor.com/images/share/fotor-ai-generate-a-lifelike-dragon.jpg'
  },
  {
    title: 'jane_smith',
    url: 'https://i.blogs.es/0ca9a6/aa/1366_2000.jpeg'
  },
  {
    title: 'emily_green',
    url: 'https://png.pngtree.com/thumb_back/fh260/background/20230611/pngtree-wolf-animals-images-wallpaper-for-pc-384x480-image_2916211.jpg'
  },
  {
    title: 'laura_miller',
    url: 'https://img.freepik.com/foto-gratis/fondo-pantalla-arbol-luna-arte-digital_23-2150918811.jpg'
  },
  {
    title: 'amanda_clark',
    url: 'https://images.unsplash.com/photo-1598759310798-18f8497d9858?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxleHBsb3JlLWZlZWR8MXx8fGVufDB8fHx8fA%3D%3D'
  }

]

</script>

<template>
    <div class="container">
        <div class="image-container" v-for="image in images" :key="image.title">
            <img :src="image.url" :alt="image.title">
            <br>
            <span>{{ image.title }}</span>
        </div>
    </div>
</template>

<style scoped>
.container{
    height: 145px;
    width: 700px;
    align-items: start;
    margin-left: 50px;
    margin-right: 50px;
    border: 1px solid #ccc;
    display: column;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

h2{
    margin-top: 25px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}
.image-container{
    text-align: center;
}

.image-container:hover{
    background-color: rgb(240, 235, 235)
}

img{
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
  align-items: center;
  height: 100px;
  width: 100px;
  margin-left: 20px;
  border: 3px solid #da1b47;
}

span{
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    margin-left: 20px;
    font-size: 14px;
}
</style>
