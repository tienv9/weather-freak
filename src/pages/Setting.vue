<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Settings</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
        <ion-item>
          <ion-label>Dark Mode</ion-label>
          <ion-toggle slot="end"></ion-toggle>
        </ion-item>
        <ion-item>
          <ion-label>Notifications</ion-label>
          <ion-toggle slot="end"></ion-toggle>
        </ion-item>
        <ion-item>
          <ion-label>GPS</ion-label>
          <ion-toggle slot="end"></ion-toggle>
        </ion-item>
        <ion-item>
          <ion-label>Location</ion-label>
          <ion-select slot="end" interface="action-sheet">
            <ion-select-option value="spokane">Spokane, WA</ion-select-option>
            <ion-select-option value="seattle">Seattle, WA</ion-select-option>
            <ion-select-option value="portland">Portland, OR</ion-select-option>
            <ion-select-option value="boise">Boise, ID</ion-select-option>
          </ion-select>
        </ion-item>
      </ion-list>
    </ion-content>
    
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle } from '@ionic/vue';
</script>
