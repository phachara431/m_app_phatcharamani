<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 4</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 3</ion-title>
        </ion-toolbar>
      </ion-header>

<ion-content fullscreen>
        <ion-card>
          <img src="https://scontent.fphs2-1.fna.fbcdn.net/v/t39.30808-6/271242885_3037655973150217_6350590440241557616_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=730e14&_nc_eui2=AeH9dksD0bTVHtaV4dRpcta3HYSdOIah7BcdhJ04hqHsFxK-qAyxSkQyMThxb3VhTDVu9f3wRZ6AAdeX9ZZUhryI&_nc_ohc=cnqAGjBS8kIAX_Watcs&_nc_ht=scontent.fphs2-1.fna&oh=00_AT9vIMDeSJa6g2YTfT-uf0wzROheJ9dnugi1oRxiUS3-3w&oe=62299A9E" />
          <ion-card-header>
            
            <ion-card-title>พัชรมณี เกตุขวง </ion-card-title>
          </ion-card-header>
          <ion-card-content>
            รหัสนักศึกษา : 62442206001-9
<ion-card-subtitle>เบอร์โทร : 0947402204 </ion-card-subtitle>
           

          </ion-card-content>
        </ion-card>
      </ion-content>
      
       <ExploreContainer name="Tab 4 page" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab3Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});


</script>
