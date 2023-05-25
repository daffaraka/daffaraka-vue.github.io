<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Greeting from './components/Greeting.vue'
import MySkills from './components/MySkills.vue'
import MyProject from './components/MyProject.vue'
import Footer from './components/Footer.vue'

</script>

<template>
   <header>
        <a href="#" class="logo">PORTOFOLIO</a>
        <ul>
            <li> <a href="#"> Home </a></li>
            <li> <a href="#informasi"> About Me </a></li>
            <li> <a href="#myskill"> Services </a></li>
            <li> <a href="#myproject"> Project </a></li>
            <li> <a href="#footer"> Contact </a></li>
        </ul>
    </header>

    <Greeting> </Greeting>
    <MySkills> </MySkills>
    <MyProject> </MyProject>
    <Footer> </Footer>
</template>
