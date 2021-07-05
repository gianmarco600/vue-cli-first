<template>
    <div class="jumbo">
        <h2>Mi ci dovrò abituare a vue cli, ma sembra davvero utile!</h2>
    </div>
</template>

<script>
export default {
  name: 'Jumbo',
}
</script>

<style scoped>
.jumbo{
    background-image: url('https://lh3.googleusercontent.com/proxy/YiT0-xnug3pXgt1QD-6ESHJvmMDerLrakc1aAmPyqE9cPMoXdVGx-eJ91bAEXk78ImBZiqRg-tGYplPNFwD5xUMVJSV9ZLQ0Hzu-4WaQrtwmZ3bIODaNtfiZiqUU8habe7-y47vRZg');
    width: 100%;
    height: 800px;
    background-size: cover;
    display: flex;
    align-items: center;
}

h2{
    display: block;
    width: 40%;
    color: white;
}

</style>