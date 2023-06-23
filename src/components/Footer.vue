<template>
    <footer class="bg-light mt-4 py-4">
        <div class="text-center">
            <span><p class="text-center copyright mx-1">&copy; 2023 | Peter Omar Kovacik</p></span>
            <NuxtLink class="nav-link instagram-link mx-1" to="https://www.instagram.com/omarkovacik/" target="_blank">
                <g-image src="../assets/images/pngtree-instagram.png" alt="Instagram icon" width="35px" height="35px" class="instagram-icon align-middle"/>
            </NuxtLink>
        </div>   
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style>
    footer {
        background-image: url('../assets/images/islamic-gray-background.png');
        background-repeat: no-repeat;
        background-size: cover;
        border-top: #eee 1px solid;   
    }

    .copyright {
        display: inline-block;
    }
    
    .instagram-link {
        display: inline-block;
        /*margin: 0 auto; */
    }
   
</style>