<template>
  <p v-on:click="audioPikachu.play">Picachu short</p>
  <audio controls src="sound1.mp4" ref="audioPikachu" v-show="false">
    <a href="sound1.mp4"> Download audio </a>
  </audio>

  <p v-on:click="audioPikapi.play">Pika-pi</p>
  <audio controls src="sound2.mp4" ref="audioPikapi" v-show="false">
    <a href="sound2.mp4"> Download audio </a>
  </audio>

  <p v-on:click="audioAmongUs.play">?</p>
  <audio controls src="AmongUs.mp4" ref="audioAmongUs" v-show="false">
    <a href="AmongUs.mp4"> Download audio </a>
  </audio>

  <p v-on:click="audioGymLeader.play">Gym</p>
  <audio controls src="GymLeader.mp4" ref="audioGymLeader">
    <a href="GymLeader.mp4"> Download audio </a>
  </audio>

  <p v-on:click="audioKyaa.play">????</p>
  <audio controls src="Kyaa.mp4" ref="audioKyaa" v-show="false">
    <a href="GymLeader.mp4"> Download audio </a>
  </audio>
</template>

<script setup lang="ts">
const audioPikachu = ref();
const audioPikapi = ref();
const audioAmongUs = ref();
const audioGymLeader = ref();
const audioKyaa = ref();

onMounted(() => {
  console.log('sdfsdfsd');
});
</script>
