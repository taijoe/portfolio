<template>
  <div id="home">
    <div class="text-area">
      <span>
        <h1>LOC VAN TAI</h1>
        <h3>Web Developer</h3>
      </span>
     <div class="btn_h">
       <button style="background: #2257ea">
        <a href="#projects">See my work</a>
      </button>
      <button style="background: #2257ea">
        <a href="/cv.pdf" target="_blank">Resume</a>
      </button>
     </div>
    </div>
    <img
      src="../assets/undraw_web_developer_p3e5.svg"
      alt="web developer"
      id="web-dev-img"
      width="50%"
    />
  </div>
</template>
<script>
export default {
  name: "Home"
};
</script>

<style lang="scss" scoped>
#home {
  display: flex;
  justify-content: space-between;
  align-items: center;
  overflow: hidden;
  padding: 0 3rem;
  min-height: 60vh;
  h1 {
    font-weight: 900;
    margin-bottom: 0px;
  }
  h3 {
    margin-top: 0px;
  }
  .btn_h{
    display: flex;
    button{
      margin: 5px;
    }
  }
  .text-area {
    display: flex;
    font-size: 1.4rem;
    flex-direction: column;
    justify-content: space-evenly;
    padding: 3rem;
  }
  .svg {
    position: absolute;
    right: 3rem;
    top: 8rem;
  }
}
@media only screen and (max-width: 900px) {
  #web-dev-img {
    display: none;
  }
  .text-area {
    text-align: center;
    align-items: center;
    padding: 0rem;
    margin: 0rem;
  }
  #home {
    justify-content: center;
    padding: 0rem;
  }
}
</style>
