<script setup>

</script>

<template>
  <div className='bio'>
    <div className='avatar'>
        <img src="https://avatars.githubusercontent.com/u/4542805?v=4" />
    </div>
    <div>
        <h1>Sillas Soares</h1>
        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec et consequat ex. Vivamus rhoncus lobortis leo, ac ultrices eros tempor eu. Maecenas nec massa ligula. Proin in tellus ligula. Integer rhoncus accumsan turpis, eu aliquet massa varius quis. In dignissim, nunc eu aliquet tincidunt, tellus ipsum tempor odio, nec pretium ante eros hendrerit lacus. Nam egestas, ex aliquet eleifend vehicula, lorem felis iaculis orci, vitae congue risus ligula a nisi. Donec at tincidunt dui. Proin dictum ex a mauris varius luctus. </span>
    </div>
  </div>
</template>

<style scoped>

.bio {
    display: flex;
    flex: 1;
    background-color: #2F568D;
    width: 100%;
    color: #fff;
    padding: 10px 70px;
    align-items: center;
}

.avatar {
    padding: 50px;
}

img {
    height: 150px;
    width: 150px;
    border-radius: 50%;
}

span {
    padding-top: 70px;
}
</style>
