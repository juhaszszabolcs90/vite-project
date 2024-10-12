<script>
  var time = new Date();
  var szam = 0;

  function update() {
    
  }
  setInterval(() => {
    time = new Date();
    1000
  })
</script>

<main>
  <h1>{time.toLocaleTimeString()}</h1>
  <p>{time.toLocaleString()}</p>
  
  {time.toLocaleDateString()}

  <hr><input type="text" bind:value={szam}>
  <br>
  2-es számrendszer: {Number(szam).toString(2)};
  16-os számrendszer: {Number(szam).toString(16)};

</main>

<style>

</style>
