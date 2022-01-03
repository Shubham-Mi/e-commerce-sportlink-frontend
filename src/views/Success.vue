<template>
  <div class="page-success">
    <div class="columns is-multiline">
      <idv class="column is-12">
        <h1 class="title">Thank you</h1>
        <p>Your order will be processed soon.</p>
      </idv>
    </div>
  </div>
</template>

<script>
export default {
  name: "Success",
  mounted() {
    document.title = "Success | Sport-Link";
  },
};
</script>
