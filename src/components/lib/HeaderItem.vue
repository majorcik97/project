<template>
    <header class="header">
        <router-link to="/" class="logo">
            <img src="@/assets/img/logo.jpg" alt="logo">
        </router-link>
        <ul class="header__menu">
            <li><router-link to="/">kursi</router-link></li>
            <li><router-link to="/">biz haqimizda</router-link></li>
            <li><router-link to="/">blog</router-link></li>
            <li>
                <span>yana</span>
                <ul class="header__dropdown">
                    <li><router-link to="/">FAQ</router-link></li>
                    <li><router-link to="/">Kontact</router-link></li>
                    <li><router-link to="/">Tolovlar</router-link></li>
                </ul>
            </li>
        </ul>
        <button class="btn">Kirish</button>
    </header>
</template>

<script>
export default {
    components: {}
}
</script>

<style lang="scss"> 
    @import '@/styles/components/header.scss';
</style>