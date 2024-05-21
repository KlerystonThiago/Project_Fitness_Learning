<template>
    <nav class="nav_top d_flex justify_between">
        <div class="box_brand d_flex align_items_center gap_10">
            <i class="fa-solid fa-dumbbell fa-fw text_white"></i>
            <img src="../assets/images/brand2.png" class="brand" alt="">
        </div>
        <ul class="d_flex" :class="nav_toogle ? 'nav_open' : 'nav_closed'">
            <li class="active">
                <a href="#">Home</a>
            </li>
            <li>
                <a href="#">About</a>
            </li>
            <li>
                <a href="#">Services</a>
            </li>
            <li>
                <a href="#">Reviews</a>
            </li>
            <li>
                <a href="#">Contacts</a>
            </li>
            <li class="nav_login">
                <a href="#">Login</a>
            </li>
        </ul>
        <div class="nav_icon_menu">
            <i @click="toggleMenu" class="fa-solid fa-bars text_white"></i>
        </div>
        <div class="auth d_flex align_items_center">
            <a href="#" class="auth_button">Login</a>
        </div>
    </nav>
</template>

<script setup>
    import { ref } from 'vue'
    
    let nav_toogle = ref(false);

    function toggleMenu() {
        nav_toogle.value = !nav_toogle.value;
    }
</script>