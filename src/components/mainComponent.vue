<template>
  <div class="m-5">
    <h1 class="title is-1">Main title</h1>

    <b-collapse aria-id="someId" :open="false" class="panel">
      <template #trigger>
        <div class="panel-heading" role="button" aria-controls="taxiProject">
          <strong>any Title</strong>
        </div>
      </template>

      <div class="panel-block p-4">any short description</div>
      <div class="p-4 panel-block is-justify-content-center">
        <p>any long desctiption</p>
      </div>
      <h4 class="title is-4 has-text-centered">Видео</h4>
      <div class="p-4 panel-block is-justify-content-center">
        <video style="width: 80%" controls="controls">
          <source src="./../assets/somevideo.mp4" />
        </video>
      </div>
    </b-collapse>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>