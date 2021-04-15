<template>

<!-- Main App Header that redirects to / page -->
<header>
<router-link to="/">
<h3><span>Vue</span>Movies</h3>
</router-link>
</header>

<main>
<router-view/>
</main>

</template>

<style>

*{
margin: 0;
padding: 0;
box-sizing: border-box;
}

body{
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
background-color: rgb(57, 55, 66);
color: #fff;
}

header{
font-size: 1.5rem;
text-align: center;
padding: 16px 10px;
font-weight: bold;
color: #fff;
}

header span{
color: rgb(16, 143, 84);
}

header h3{
color: #fff;
}

header a{
text-decoration: none;
}


</style>
