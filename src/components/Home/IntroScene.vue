<template>
  <section class="scene-intro" id="intro">
    <div class="static-container">
      <h1 class="title">
        <span class="iuri">van</span>
        <span class="func">.is()</span>
      </h1>

      <TextBlock>
        <p class="-purple">Nguyen Lam Van</p>
        <p class="-gray">Frontend developer</p>
      </TextBlock>
    </div>
  </section>
</template>

<script>
import TextBlock from '../TextBlock.vue'

export default {
  name: 'IntroScene',
  components: { TextBlock },
}
</script>
