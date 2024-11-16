<template>
  <Layout>
    <h1 class="text-center title text-green-900 text-5xl pt-8 pb-3">About Omar</h1>
    <div class="content-width px-7">
      <p class="pt-3 pb-4">
        Omar became Muslim in 2001 with Hafiz M. Shafique at Masjid al-Qur'an in Milwaukee, WI and began studying Classical Arabic in 2005 at Qasid Institute in Jordan. He has a Bachelor of Arts in Linguistics from the University of Wisconsin-Milwaukee, and he completed a 130-Hour Certificate in Teaching English as a Foreign Language (TEFL) and a 20-Hour Certificate in Teaching Test Preparation from the Wisconsin ESL Institute (WESLI) in Madison, WI. He taught English to non-native speakers in Aden, Yemen and Bursa, Turkey, and he taught Arabic and ESL at Clara Mohammed School in Milwaukee, WI. He designed and taught a curriculum in Classical Arabic for the Fox Valley Islamic Society. 
      </p>
      
      <p class="pt-3 pb-9">
        Omar resides with his family in Green Bay, WI. He is currrently pursuing studies in Maliki fiqh and related subjects with Shaykh Mujahid Abdul-Karim at Fayda Institute, teacher training for 'Why Islam is True' with Shaykh Hamza Karamali at Basira Education, and a Masters of Arts in Islamic Studies at The Islamic Seminary of America (TISA) with Dr. James Jones, Dr. Tamara Gray, Dr. Yasir Qadhi, Dr. Julie Lowe, Dr. Omar Imady, and Dr. Jonathan Brown.
      </p>

      <figure class="pt-3 pb-5">
          <img src="/images/self-image-trees.avif" alt="image of Omar"  class="center-image self-image"> 
      </figure>
      
      <h2 class="text-center title text-green-900 text-3xl pt-8 pb-3">Arabic Studies</h2>
    
       
          <p class="pt-3 pb-2">Omar's Arabic teachers include Shaykh Faraz Khan, Shaykh Sohail Hanif, Shaykh Ahmad Snobar, and Ustadh Amer Melham (Qasid Institute); Dr. Hamid Ouali (University of Wisconsin-Milwaukee); Shaykh Sulayman Van Ael (Sunnipath); Shaykh Farid Dingle (Qibla); Mufti Yusuf Mullan (Toronto Shariah Program); Ustadh Muhammad Metweley (Studio Arabiyyah); Ustadh Sayed Fathy (Sibawayh Center); Mawlana Syed Javed Ali Shah (private Skype lessons); and Shaykh Abdul-Rahim Reasat (Seeker's Guidance).</p>
          
          <p class="pt-3 pb-4">In addition to Arabic, he has studied traditional Islamic sciences like aqidah ('Ashari), fiqh (Shafi'i, Hanafi, and Maliki), 'usul al-fiqh, hadith methodology, and tajwid with Shaykh Hamza Karamali, Shaykh Mujahid Abdul-Karim, Shaykh Abdul-Karim Yahya, Mawlana Syed Javed Ali Shah,  Shaykh Ashraf Muneeb, Shaykh Faraz Rabbani, Shaykh Isa Husayn, Shaykh Saifullah Abu M., Shaykh Salah al-Kurdi, Shaykh Ali Hani, and others.</p>
          
    </div>

    <CoursesButton />
  </Layout>
</template>



<script>

import CoursesButton from '~/components/CoursesButton.vue'

export default {
  
  metaInfo: {
    title: 'About'
  },
  components: {
    CoursesButton
  },
    
}
</script>

<style scoped>
   

    .center-image {
        display: block;
        margin: 0 auto;
    }

    .self-image {
        height: 400px;
        width: 300px;
    }

    @media only screen and (min-width: 720px) {
        .self-image {
            height: 480px;
            width: 360px;
        }  
    }
    
    .content-width {
      max-width: 700px;
      display: block;
      margin: 0 auto;
    }
</style>
