<template>
    <layout>
        <div>
            <h1 class="text-center title text-green-900 text-5xl py-7">Let's Connect</h1>

            <div class="leaves my-3"></div>

            <div class="my-3 py-3"></div>
            <div class="w-96 md:w-full max-w-lg contact-form">
                <form action="https://formsubmit.co/871b77a3771c1f5953f344193a030234" method="POST" class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4"> <!-- contact-form py-5 form-margin-show-button -->
                <!--<form action="https://formsubmit.co/info@arabicwithomar.com" method="POST" class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4"> --> <!-- contact-form py-5 form-margin-show-button -->

                <!-- Name input -->
                    <div class="mb-4">
                        <label class="block text-gray-700 text-sm font-bold mb-2" for="name">Name</label>
                        <input type="text" id="name" name="name" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" required/> <!-- class="form-control" -->
                    </div>

                    <!-- Email input -->
                    <div class="mb-4">
                        <label class="block text-gray-700 text-sm font-bold mb-2" for="email">Email address</label>
                        <input type="email" id="email" name="email" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" required/>
                        
                    </div>

                    <!-- Subject -->
                    <!-- <input type="hidden" name="_subject" value="submission from Arabic Instructor"> -->
                    <div class="mb-4">
                        <label class="block text-gray-700 text-sm font-bold mb-2" for="subject">Subject</label>
                        <input type="text" id="subject" name="_subject" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" required/>
                        
                    </div>
                    <!-- Message input -->
                    <div class="mb-4">
                        <label class="block text-gray-700 text-sm font-bold mb-2" for="message">Message</label>
                        <textarea class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="message" name="message" rows="4" required></textarea>
                    </div>

                    <!-- Submit button -->
                    <button type="submit" class="bg-green-900 hover:bg-green-800 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline button-margin">Send</button>
                </form>
            </div>
        </div>
    </layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Contact'
  }
}
</script>

<style scoped>
    .contact-form {
        /*width: 350px;*/
        display: block;
        margin: 0 auto;
    }

    .leaves {
        background-image: url('/images/leaves-three-sisters.avif');
        height: 300px;
        width: 340px;
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        display: block;
        margin: 0 auto;
        border-radius: 25px; /* rounded corners */
    }
   
    @media only screen and (min-width: 400px) {
       
        .leaves {
            width: 375px;
        }
       
    }
    

    @media only screen and (min-width: 768px) {
        .leaves {
            width: 500px;
            height: 350px;
        }
       
    }
</style>