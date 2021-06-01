<template>
  <div>
    <svg-icon icon-class="question" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'JinXiuDoc',
  data() {
    return {
      url: 'http://doc.jinxiuyun.com/jinxiu-vue'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
