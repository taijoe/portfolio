<template>
  <div id="footer">
    Made with 💙 by Me
  </div>
</template>
<script>
export default {
  name: "Footer"
};
</script>

<style lang="scss" scoped>
$blue: #2257ea;
$lightgrey: #f7f7f7;
$secondarycolor: #213059;
#footer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 15vh;
  background: $secondarycolor;
  color: $lightgrey;
  a {
    text-decoration: none;
    color: $lightgrey;
  }
}
</style>
