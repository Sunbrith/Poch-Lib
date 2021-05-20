<template>
<div class="btnAjouter">
    <button
      depressed
      rounded
      dark
    >
      Ajouter un livre
    </button>
  </div>  
</template>

<script>
export default {
  name: 'AddABook',
  props: {
    
  }
}
</script>

<style scoped>
.btnAjouter {
display: inline-block;
    margin: 0.5em 0;
    padding: 1em 2em;
    background: rgb(102, 187, 162);
    border: 1px solid rgb(24, 184, 144);
    border-radius: 3px;
    color: whitesmoke;
    font-family: "Quicksand", sans-serif;
    font-size: 1em;
    font-weight: 700;
    letter-spacing: 0.02em;
    line-height: 1;
    text-decoration: none;
    text-transform: uppercase;
    cursor: pointer;
    transition: 0.3s;
  }

  .button:hover {
    background: rgb(24, 184, 144);
    color: #fff;  
}
</style>
