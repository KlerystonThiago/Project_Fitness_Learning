<template>
    <div class="clip_header">
        <header>
            <div class="container z_index_3">
                <Navgation/>
            </div>
            <div class="container">
                <div class="resume_header d_flex flex_direction_column justify_center align_items_center text_white gap_50">
                    <div class="resumes d_flex flex_direction_column justify_center align_items_center gap_10">
                        <h1 class="header_title text_center f_weight_4 f_size_50">
                            Professional Gym with a Poll
                            and a variety of Group Programs
                        </h1>
                        <p class="f_weight_3 header_subtitle text_white">
                            FITNESS - GYM - SWIMMING - POOL - GROUP - TRANNING
                        </p>
                    </div>                

                    <div class="header_contacts w_100 d_flex justify_between f_size_12">
                        <div class="d_flex gap_10">
                            <i class="fa-solid fa-map-location-dot"></i>
                            Rua 5 Centro - Ferreiros - PE
                        </div>
                        <div class="d_flex gap_10">
                            <i class="fa-solid fa-phone-volume"></i>
                            (81) 99400-3340
                        </div>
                        <div class="d_flex gap_10">
                            <i class="fa-solid fa-envelope"></i>
                            kleryston.thiago@gmail.com
                        </div>
                    </div>
                </div>
            </div>
        </header>
    </div>    
</template>

<script setup>
    import { ref } from 'vue'
    import Navgation from './Navgation.vue'       
</script>