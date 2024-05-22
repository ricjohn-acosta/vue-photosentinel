<template>
  <div class="grid m-0">
    <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-6">
      <Card class="card">
        <template #title>
          <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
            <i class="pi pi-file" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
            System logs
          </div>
        </template>
        <template #content>
          <div class="cardHeader">
            <div>
              Event
            </div>

            <div>
              Date
            </div>
          </div>

          <div class="cardBody">
            <div>
              Status update
            </div>
            <div class="eventDate">
              May 22, 2024 - 8:10 pm
              <i class="pi pi-chevron-right" style="font-size: 12px; margin-left: 6px; color: #0000bd"></i>
            </div>
          </div>
          <div class="cardBody">
            <div>
              Status update
            </div>
            <div class="eventDate">
              May 22, 2024 - 8:10 pm
              <i class="pi pi-chevron-right" style="font-size: 12px; margin-left: 6px; color: #0000bd"></i>
            </div>
          </div>
          <div class="cardBody">
            <div style="color: #0000bd">
              Photo uploaded
            </div>
            <div class="eventDate" style="color: #0000bd">
              May 22, 2024 - 8:10 pm
              <i class="pi pi-chevron-right" style="font-size: 12px; margin-left: 6px; color: #0000bd"></i>
            </div>
          </div>
          <div class="cardBody">
            <div style="color: #0000bd">
              Photo uploaded
            </div>
            <div class="eventDate" style="color: #0000bd">
              May 22, 2024 - 8:10 pm
              <i class="pi pi-chevron-right" style="font-size: 12px; margin-left: 6px; color: #0000bd"></i>
            </div>
          </div>
          <div class="cardBody">
            <div>
              Status update
            </div>
            <div class="eventDate">
              May 22, 2024 - 8:10 pm
              <i class="pi pi-chevron-right" style="font-size: 12px; margin-left: 6px; color: #0000bd"></i>
            </div>
          </div>
        </template>
      </Card>
    </div>
    <div class="flex justify-content-center align-items-center col-12 md:col-6 lg:col-6">
      <Card class="card">
        <template #title>
          <div class="flex justify-content-start align-items-center pt-4 pl-4 font-bold text-xl">
            <i class="pi pi-exclamation-triangle" style="font-size: 16px; margin-right: 6px; color: #0000bd"></i>
            Alerts
          </div>
        </template>

        <template #content>
          <div class="cardHeader">
            <div>
              Status
            </div>

            <div>
              Severity
            </div>
          </div>
        </template>
      </Card>
    </div>
  </div>
</template>

<script setup>
import Card from "primevue/card";

</script>

<style scoped>

.card {
  width: 100%;
  height: 260px;
  background-color: white;
  border-radius: 22px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.cardHeader {
  display: flex;
  justify-content: space-between;
  border-bottom-style: solid;
  border-bottom-width: 0.5px;
  border-color: lightgrey;
  margin-left: 24px;
  margin-right: 24px;
  margin-top: 10px;
  color: grey;
  font-size: 13px;
  font-weight: bold;
}

.cardBody {
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
  margin-left: 24px;
  margin-right: 24px;
}

.eventDate {
  display: flex;
  justify-content: center;
  align-items: center;
}

</style>