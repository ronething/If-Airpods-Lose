<template>
  <div>
    <full-page :options="options" id="fullpage" ref="fullpage">
      <div class="section" id="section1">
        <img src="/airpods.jpg" width="100%" />
        <h1>如果您捡到我的 AirPods..</h1>
      </div>
      <div class="section">
          <h1><a href="mailto:admin@ronething.cn">希望可以联系我</a></h1>
      </div>
    </full-page>
  </div>
</template>

<script>
export default {
  name: "",
  props: [""],
  data() {
    return {
      options: {
        navigation: true,
        },
    };
  },

  components: {},

  computed: {},

  watch: {},

  beforeMount() {},

  mounted() {},

  methods: {}
};
</script>
<style scoped>
h1 {
    font-family: "Microsoft YaHei"
}
</style>