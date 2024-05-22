<template>
  <div>
    <div class="grid m-0">
      <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-8">
        <Card class="imageCard">
          <template #content>
            <div class="imageContainer">
              <div class="cameraLocation">
                <i class="pi pi-map-marker" style="font-size: 16px; color: white; margin-right: 2px"></i>
                Australia/Melbourne
              </div>
              <img src="/sentinel.jpeg" class="w-full h-full bg-cover"/>
              <div class="takenAt">Uploaded May 22, 2024 - 3:00 pm</div>
              <i class="pi pi-cloud-upload"
                 style="position: absolute; font-size: 16px; bottom: 10px; right: 30px; color: white"></i>
              <i class="pi pi-wifi"
                 style="position: absolute; font-size: 16px; bottom: 10px; right: 10px; color: red"></i>
            </div>
          </template>
        </Card>
      </div>
      <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-4">
        <Card class="card">
          <template #title>
            <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
              <i class="pi pi-clock" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
              Time
            </div>
          </template>
          <template #content>
            <div class="pt-2 pl-4">
              <div class="text-left mb-3">
                <div class="labelTitle">
                  Last Contact Time
                </div>
                <div>
                  May 5, 2024 - 5:40 pm
                </div>
              </div>

              <div class="text-left mb-3">
                <div class="labelTitle">
                  Estimated Next Contact
                </div>
                <div class="text-orange-500">
                  May 5, 2024 - 5:50 pm
                </div>
              </div>

              <div class="text-left mb-3">
                <div class="labelTitle">
                  Estimated Next Camera Use
                </div>
                <div>
                  May 23, 2024 - 9:00 am
                </div>
              </div>
            </div>
          </template>
        </Card>
      </div>
      <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-6">
        <Card class="card">
          <template #title>
            <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
              <i class="pi pi-tablet" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
              Device information
            </div>
          </template>
          <template #content>
            <div class="pt-2 pl-4">
              <div class="text-left mb-2">
                <div class="labelTitle">
                  Current Voltage
                </div>
                <div>
                  8.2V
                </div>
              </div>

              <div class="text-left mb-2">
                <div class="labelTitle">
                  Firmware Version
                </div>
                <div class="text-orange-500">
                  APEX-dev-3.1.0-422
                </div>
              </div>

              <div class="text-left mb-2">
                <div class="labelTitle">
                  IMEI Number
                </div>
                <div>
                  354375090007624
                </div>
              </div>

              <div class="text-left mb-2">
                <div class="labelTitle">
                  Serial Number
                </div>
                <div>
                  TB#14
                </div>
              </div>

            </div>
          </template>
        </Card>
      </div>
      <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-6">
        <Card class="card">
          <template #title>
            <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
              <i class="pi pi-box" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
              Storage
            </div>
          </template>
          <template #content>
            <div class="pt-2 pl-4">
              <div class="text-left mb-2">
                <div class="labelTitle">
                  SD/CF Card Free Space
                </div>
                <div>
                  14.800 GiB
                </div>
              </div>

              <div class="text-left mb-2">
                <div class="labelTitle">
                  External Drive Free Space
                </div>
                <div class="text-orange-500">
                  426.005 GiB
                </div>
              </div>

              <div class="text-left mb-2">
                <div class="labelTitle">
                  External Drive Capacity
                </div>
                <div>
                  465.746 GiB
                </div>
              </div>
            </div>
          </template>
        </Card>
      </div>
    </div>
  </div>

</template>

<script setup>
import Card from 'primevue/card';
</script>

<style scoped>

.container {
//margin-left: 24%; //margin-right: 15%;
}

.card {
  width: 100%;
  height: 260px;
  background-color: white;
  border-radius: 22px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.imageCard {
  position: relative;
  width: 100%;
  height: 260px;
  background-color: white;
  border-radius: 22px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.imageContainer {
  width: 100%; /* Set the width of the container */
  height: 260px; /* Set the height of the container */
}

.imageContainer img {
  width: 100%; /* Make the image fill the width of the container */
  height: 250px; /* Make the image fill the height of the container */
  object-fit: cover;
  border-radius: 22px;
}

.labelTitle {
  font-size: 13px;
  font-weight: bold;
  color: grey;
}

.takenAt {
  position: absolute;
  bottom: -1px;
  padding: 10px;
  font-size: 12px;
  font-weight: bold;
  color: white;
}

.cameraLocation {
  display: flex;
  align-items: center;
  position: absolute;
  bottom: 18px;
  padding: 10px;
  font-size: 12px;
  font-weight: bold;
  color: white;
}

</style>