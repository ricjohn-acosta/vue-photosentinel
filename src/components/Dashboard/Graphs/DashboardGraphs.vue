<template>
  <div class="grid m-0">
    <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-4">
      <Card class="card">
        <template #title>
          <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
            <i class="pi pi-bolt" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
            Voltage log
          </div>
        </template>
        <template #content>
          <div class="imageContainer">
            <img src="/voltage-log.png"/>
          </div>
        </template>
      </Card>
    </div>

    <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-4">
      <Card class="card">
        <template #title>
          <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
            <i class="pi pi-box" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
            Free space log
          </div>
        </template>
        <template #content>
          <div class="imageContainer">
            <img src="/free-space-log.png"/>
          </div>
        </template>
      </Card>
    </div>

    <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-4">
      <Card class="card">
        <template #title>
          <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
            <i class="pi pi-cog" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
            Temperature log
          </div>
        </template>
        <template #content>
          <div class="imageContainer">
            <img src="/temperature-log.png"/>
          </div>
        </template>
      </Card>
    </div>
  </div>
</template>

<script setup>
import Card from "primevue/card";
</script>

<style>
.card {
  width: 100%;
  height: 260px;
  background-color: white;
  border-radius: 22px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.imageContainer {
  width: 100%; /* Set the width of the container */
  height: 200px; /* Set the height of the container */
}

.imageContainer img {
  width: 100%; /* Make the image fill the width of the container */
  height: 200px; /* Make the image fill the height of the container */
  border-radius: 22px;
}

</style>