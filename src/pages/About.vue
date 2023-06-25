<template>
  <Layout>
    <h1 class="text-center title text-4xl pt-8 pb-3">About Omar</h1>
    <div class="content-width px-7">
        <p class="pt-3 pb-4">Omar became Muslim in 2001 and began studying Classical Arabic in 2005 at Qasid Institute in Jordan. He has a Bachelor of Arts in Linguistics from the University of Wisconsin-Milwaukee and certificates in Teaching English as a Foreign Language from the Wisconsin ESL Institute (WESLI) in Madison, WI. He taught English to non-native speakers in Aden, Yemen and Bursa, Turkey, he taught Arabic and ESL at Clara Mohammed School in Milwaukee, WI, and he designed and taught a program for Classical Arabic at Fox Valley Islamic Society in Neenah, WI. He is currently resides with his family in Green Bay, WI and is pursuing a Masters of Divinity in Islamic Chaplaincy at The Islamic Seminary of America (TISA) while  taking additional coursework at Basira Education, Fayda Institute, and the Maliki School.</p>
        <figure class="pt-3 pb-9">
            <img src="/images/self-image-trees.avif" alt="image of Omar"  class="center-image self-image"> 
        </figure>
        <p class="pt-4 pb-2 font-bold">Omar's teachers in the Arabic language include (chronologically):</p>
        <ul class="list-disc ml-7">
          <li class="">Ustadh Amer Melham, Shaykh Faraz Khan, Shaykh Sohail Hanif (Qasid Institute)</li>
          <li class="">Dr. Hamid Ouali (University of Wisconsin-Milwaukee)</li>
          <li class="">Mufti Yusuf Mullan (Toronto Shariah Program)</li>
          <li class="">Ustadh Farid Dingle (Qibla)</li>
          <li class="">Ustadh Muhammad Metlwey (Studio Arabiyyah)</li>
          <li class="">Ustadh Sayed Fathy (Sibawyah Institute)</li>
          <li class="">Mawlana Syed Javed Ali Shah (private lessons)</li>
        </ul> 
        
        <p class="pt-7 pb-2 font-bold">His teachers in Islamic Studies include (chronologically):</p>
        <ul class="list-disc ml-7 mb-10">
          <li class="">Hafiz M. Shafique (Masjid al-Qur'an in Milwaukee)</li>
          <li class="">Shaykh Salah al-Kurdi (Dar al-Hamd)</li>
          <li class="">Shaykh Ali Hani (private lessons)</li>
          <li class="">Shaykh Hamza Karamali (Sunnipath and Basira Education)</li>
          <li class="">Shaykh Abdul-Karim Yahya, Shaykh Faraz Rabbani (Sunnipath)</li>
          <li class="">Dr. Ashraf Muneeb (Qibla)</li>
          <li class="">Ustadh Abdo (Masjid al-'Aydarous in Aden)</li>
          <li class="">Mawlana Syed Javed Ali Shah (private lessons)</li>
          <li class="">Shaykh Isa Johannson</li>
          <li class="">Shaykh Mujahid Abdul-Karim (Fayda Institute)</li>
          <li class="">Dr. James Jones, Chaplain Omer Bajwa, Dr. Tamara Gray, Dr. Yasir Qadhi, Dr. Omar Imady, and Dr. Julie Lowe (The Islamic Seminary of America)</li>
          <li class="">Shaykh Saifullah Abu M. (Maliki School)</li>
        </ul> 
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About'
  }
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
