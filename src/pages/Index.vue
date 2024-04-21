<template>
  <Layout>
   
    <!-- Learn how to use images here: https://gridsome.org/docs/images 
    <g-image alt="Example image" src="~/favicon.png" width="135" />
    -->

    <div class="green-mountain-banner flex justify-center items-center" title="green mountain image">
        <h1 class="title text-center text-7xl text-white">Classical Arabic with Omar</h1>
    </div>

    <div class="content-width pt-5 px-7">
        <h2 class="title text-center pt-8 pb-3 text-4xl">Classical Arabic Program</h2>
        <p class="py-3">Learn Classical Arabic in a step by step methodology designed to help you understand the meanings of the Qur'an and access traditional Islamic texts in the original Arabic.</p>
        <p class="py-1">Step 1: Foundations of Classical Arabic</p>
        <p class="py-1">Step 2: Keys to Classical Arabic</p>
        <p class="py-1">Step 3: Navigating Classical Arabic</p>
        <p class="py-2">Sign up for current classes in the <g-link class="text-emerald-700 underline" to="https://arabicinstructor.teachable.com/" target="_blank">student portal</g-link>.</p>
    </div>
    
    <div class="pb-10"></div>
    
    
    <CoursesButton />
   
    <!--
    <h2 class="title text-center pt-8 pb-8 text-4xl">Join our mailing list!</h2>
    <Mailchimp />
    <div class="py-3"></div>
    -->

    
  </Layout>
</template>

<script>
import Mailchimp from '~/components/Mailchimp.vue'
import CoursesButton from '~/components/CoursesButton.vue'

export default {
  
  metaInfo: {
    title: 'Home'
  },
  components: {
    Mailchimp,
    CoursesButton
  },
    
}
</script>

<style>
  .green-mountain-banner {
        background-image: url('/images/green-mountain-unsplash.avif');
        height: 400px;
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        border-bottom: #eee 1px solid;   
    }

    @media only screen and (min-width: 720px) {
        .green-mountain-banner {
            height: 650px;
        }
    }

    .content-width {
      max-width: 700px;
      display: block;
      margin: 0 auto;
    }

    .courses-button {
      display: block;
      margin: 0 auto;
    }
</style>
