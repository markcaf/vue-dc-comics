<template>
  <div class="comic mb-5">
    <div class="image-container">
      <img class="comic-cover" :src="imageUrl" :alt="title" />
    </div>
    <div class="title text-white text-uppercase mt-3">
      {{ title }}
    </div>
  </div>
</template>

<script>
export default {
  props: {
    imageUrl: String,
    title: String,
    price: String,
    type: String,
  },
};
</script>

<style lang="scss" scoped>
    .comic {
    width: calc(100% / 6);

        .image-container {
            height: 192px;
            width: 192px;

            img.comic-cover {
            height: 100%;
            width: 100%;
            object-fit: cover;
            object-position: top;
            }
        }

        .title {
            font-size: 14px;
        }
    }
</style>