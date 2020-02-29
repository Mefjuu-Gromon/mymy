<template>
  <div class="home">
    <div class='firstView'>
      <h1 class='HeroStyles-Text pos01'> Hejka</h1>
      <h1 class='HeroStyles-Text pos02'> Naklejka!</h1>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
};
</script>

<style lang='scss' scoped>
*{
  margin: 0;
  padding:0;
}

body{
  margin:0;
  padding:0;
  border: 0;
}

.firstView{
  display:flex;
  width:100%;
  height:98vh;
  font-family: 'Muli', ;
}
.pos01{
  @media(min-width: 1350px){
    margin-top:30%;
    margin-left: 59%;
  }

  @media(min-width: 300px){
    margin-top: 60%;
  }
  @media(min-width: 1350px){
    margin-top:20%;
    font-size: 5.4rem;
  }

}

.pos02{
  @media(min-width: 1050px){
    margin-top:30%;
  }

  @media(min-width: 300px){
    margin-top: 60%;
  }
  @media(min-width: 1350px){
    margin-top:25%;
    font-size: 5.4rem;
  }
}

</style>
