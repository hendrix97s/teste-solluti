<template>
  <div class="container-fluid p-0">
    
    <div class="row">
      <div class="col-md-12">
        <div class="card">
          <div class="card-header">
            <h1>Card Home</h1>
          </div>

          <div class="card-body">
            {{ example }}
            <i class="fas fa-pencil-alt"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  props: ["data"],

  data() {
    return {
      example: "Home Component",
    };
  },
  mounted() {},
  methods: {
    acao() {},
  },
  beforeMount() {},
};
</script>
