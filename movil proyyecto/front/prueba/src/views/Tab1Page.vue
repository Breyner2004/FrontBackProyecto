<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Autores</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content >
      <ion-card>
    <ion-card-header>
      <ion-card-title>aMigueo</ion-card-title>
      <ion-card-subtitle>obras</ion-card-subtitle>
    </ion-card-header>
    <ion-card-content>
      <ion-list>
        <ion-item>
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
          </ion-thumbnail>
          <ion-label>Don quijote</ion-label>
        </ion-item>

        <ion-item>
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
          </ion-thumbnail>
          <ion-label>sxd</ion-label>
        </ion-item>

        <ion-item>
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
          </ion-thumbnail>
          <ion-label><dfn>s</dfn></ion-label>
        </ion-item>

        <ion-item lines="none">
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
          </ion-thumbnail>
          <ion-label>as</ion-label>
        </ion-item>
      </ion-list>
    </ion-card-content>
  </ion-card>


    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>
