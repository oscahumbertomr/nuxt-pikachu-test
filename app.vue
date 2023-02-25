<template>
  <div class="main">
    <div v-on:click="audioPikachu.play" class="button">
      Picachu short
      <audio controls src="sound1.mp4" ref="audioPikachu" v-show="false">
        <a href="sound1.mp4"> Download audio </a>
      </audio>
    </div>

    <div v-on:click="audioPikapi.play" class="button">
      Pika-pi
      <audio controls src="sound2.mp4" ref="audioPikapi" v-show="false">
        <a href="sound2.mp4"> Download audio </a>
      </audio>
    </div>

    <div v-on:click="audioAmongUs.play" class="button">
      ?
      <audio controls src="AmongUs.mp4" ref="audioAmongUs" v-show="false">
        <a href="AmongUs.mp4"> Download audio </a>
      </audio>
    </div>
    <div v-on:click="audioGymLeader.play" class="button">
      Gym
      <audio controls src="GymLeader.mp4" ref="audioGymLeader">
        <a href="GymLeader.mp4"> Download audio </a>
      </audio>
    </div>

    <div v-on:click="audioKyaa.play" class="button">
      ????
      <audio controls src="Kyaa.mp4" ref="audioKyaa" v-show="false">
        <a href="GymLeader.mp4"> Download audio </a>
      </audio>
    </div>
  </div>
</template>

<style>
.main {
  display: flex;
  flex-wrap: wrap;
  width: 100vw;
}
.button {
  padding: 5em 2em;
  margin: 1em 1em;
  text-align: center;
  flex: 30%;
  border-style: solid;
  cursor: pointer;
}
</style>

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
