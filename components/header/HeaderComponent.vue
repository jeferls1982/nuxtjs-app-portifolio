<template>
    <div class="navbar">
        <span class="title">Rede Social</span>
        <span class="actions">
            <IconLogin class="icon" />
            <IconUser class="icon"  />
        </span>
    </div>
</template>

<script>
import IconLogin from '~/assets/icons/IconLogin.vue';
import IconUser from '~/assets/icons/IconUser.vue';

export default {
    setup() {
        return {};
    },
    components: { IconLogin, IconUser }
}
</script>

<style  scoped>
.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.title{
    font-size: 2rem;
    margin-left: 1rem;
}
.actions{
    margin-right: 1rem;
    font-size: 50px;
    width: 5%;
    display: flex;
    justify-content: space-around;
}
.icon{
    cursor: pointer;
    
}
</style>