<template>
  <div class="container">
    <h2 class="title">
      TB#14 1.X Nikon D5600
    </h2>
    <CameraStatus/>
    <Dropdown/>
    <div class="dateRangePicker">
      <SplitButton label="Last 2 days: May 20 - May 23, 2024" text severity="secondary"></SplitButton>
<!--      <div class="flex justify-content-start align-items-center pt-1">-->
<!--        Last 2 days: May 20 - May 23, 2024-->
<!--        <i class="pi pi-chevron-down" style="font-size: 16px; margin-left: 6px; color: #0000bd"></i>-->
<!--      </div>-->
    </div>
    <EventLogs/>
    <DashboardGraphs/>
  </div>
</template>

<script setup>
import SplitButton from 'primevue/splitbutton';
import CameraStatus from './Status/CameraStatus.vue'
import EventLogs from './Logs/EventLogs.vue'
import DashboardGraphs from "@/components/Dashboard/Graphs/DashboardGraphs.vue";
</script>

<style>
.container {
  margin-left: 15%;
  margin-right: 15%;
}

.dateRangePicker {
  display: flex;
  justify-content: start;
  margin-top: 10px;
  margin-left: 20px;
  border-bottom-style: solid;
  border-bottom-width: 0.5px;
  border-color: lightgrey;
}

.title {
  display: flex;
  justify-content: start;
}
</style>