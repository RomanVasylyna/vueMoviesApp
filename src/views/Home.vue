<template>
<div class="main">

<div class="movie-img">
<img src="https://m.media-amazon.com/images/M/MV5BZmQ5NGFiNWEtMmMyMC00MDdiLTg4YjktOGY5Yzc2MDUxMTE1XkEyXkFqcGdeQXVyNTA4NzY1MzY@._V1_SX300.jpg" alt="Movie Poster">

<div class="movie-details">
<h3 class="movie-title">Naruto</h3>
<p class="movie-plot">
       Naruto Uzumaki, a mischievous adolescent ninja, struggles as he searches
       for recognition and dreams of becoming the Hokage, the village's leader
       and strongest ninja.
</p>
</div>
</div>

<form class="movie-form">
<input type="text" placeholder="Type Movie Name">
<input type="submit">
</form>



</div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style>
.movie-img img{
display: block;
object-fit: cover;
width: 100%;
height: 300px;
z-index: 0;
}

.movie-details{
padding: 16px;
z-index: 1;
background-color: rgba(0, 0, 0, 0.7);
position: absolute;
bottom: 49.7vh;
}

.movie-form{
margin-top: 20px;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
}

.movie-form [type="text"]{
padding: 10px 5px;
border: none;
outline: none;
border-radius: 8px;
width: 80%;
margin-bottom: 5px;
}



</style>
