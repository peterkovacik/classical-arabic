<template>
  <Layout>
    <h1 class="text-center title display-3 pt-5 pb-4">About Omar</h1>
        <div class="content-width px-5 mb-5">
            <p class="py-2">Omar became Muslim in 2001 and began studying Classical Arabic in 2005 at Qasid Institute in Jordan. He has a Bachelor of Arts in Linguistics from the University of Wisconsin-Milwaukee and certificates in Teaching English as a Foreign Language from the Wisconsin ESL Institute (WESLI) in Madison, WI. He taught English to non-native speakers in Aden, Yemen and Bursa, Turkey, he taught Arabic and ESL at Clara Mohammed School in Milwaukee, WI, and he designed and taught a program for Classical Arabic at Fox Valley Islamic Society in Neenah, WI. He is currently resides with his family in Green Bay, WI and is pursuing a Masters of Divinity in Islamic Chaplaincy at The Islamic Seminary of America (TISA) while  taking additional coursework at Basira Education, Fayda Institute, and the Maliki School.</p>
            <figure class="mt-5 mb-5">
                <img src="/images/self-image-trees.avif" alt="image of Omar"  class="center-image self-image"> 
            </figure>
            <p class="py-2">Omar's teachers in the Arabic language include: Ustadh Amer Melham, Shaykh Faraz Khan, Shaykh Sohail Hanif (Qasid Institute); Dr. Hamid Ouali (University of Wisconsin-Milwaukee); Mufti Yusuf Mullan (Toronto Shariah Program); Ustadh Farid Dingle (Qibla); Ustadh Muhammad Metlwey (Studio Arabiyyah); Ustadh Sayed Fathy (Sibawyah Institute); and Mawlana Syed Javed Ali Shah (private lessons).</p>
            <p class="py-2">His teachers in Islamic Studies include: Hafiz M. Shafique (Masjid al-Qur'an in Milwaukee); Shaykh Salah al-Kurdi (Dar al-Hamd); Shaykh Ali Hani (private lessons); Shaykh Hamza Karamali (Sunnipath and Basira Education); Shaykh Abdul-Karim Yahya, Shaykh Faraz Rabbani (Sunnipath); Dr. Ashraf Muneeb (Qibla); Ustadh Abdo (Masjid al-'Aydarous in Aden); Mawlana Syed Javed Ali Shah (private lessons); Shaykh Isa Johannsen; Shaykh Mujahid Abdul-Karim (Fayda Institute); Shaykh Saifullah Abu M. (Maliki School); Dr. James Jones, Dr. Julie Lowe, Dr. Omar Imady, Dr. Tamara Gray, and Dr. Yasir Qadhi (The Islamic Seminary of America).</p>
        </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About us'
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
