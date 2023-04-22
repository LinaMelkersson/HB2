<template>
      <footer>
      <div style="border: 2px solid red; display: grid; justify-content: center;">
        <font-awesome-icon style="color: black; height: 6vh; margin-top: 2vh;" icon="fa-brands fa-instagram" />

      </div>
      <div style="border: 2px solid yellow;">

      </div>
      <div style="border: 2px solid green;">
        
      </div>
    </footer>
</template>

<script>
export default {
    name: 'MyFooter'

}
</script>

<style>
footer {
  height: 30vh;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  margin-top: 3vh;
}

</style>