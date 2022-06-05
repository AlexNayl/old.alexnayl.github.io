<template>
  <div class="home p-5">
    <div class="row justify-content-md-center">
      <img alt="Personal Photo" src="../assets/headshot.png" class="headshot col-sm-2 p-3">
      <div class="col-sm-4 d-flex align-items-center justify-content-md-center">
        <div class="row row-cols-1 justify-content-md-center">
          <h3 class="col">Hi, I'm Alexander Naylor, a Computer Science undergraduate student focusing on Data Science.</h3>
          <a class="btn btn-dark col-sm-7" href="/Resume.pdf">Download My Resume<img src="../assets/downloadPDF.svg" class="icon"></a>
        </div>

      </div>
    </div>

  </div>
</template>

<script>

</script>

<style scoped>
.headshot{
  height: auto;
  width: 300px;
}

h3{
  color: var(--color2)
}

.icon{
  height: 60pt;
}
</style>
