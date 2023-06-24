<template>
    <layout>
        <div>
            <h1 class="text-center title">Let's Connect</h1>

            <div class="leaves"></div>

            <form action="https://formsubmit.co/871b77a3771c1f5953f344193a030234" method="POST" class="contact-form form-margin-show-button">
            <!-- Name input -->
            <div class="">
                <label class="" for="name">Name</label>
                <input type="text" id="name" name="name" class="form-control" required/>
            </div>

            <!-- Email input -->
            <div class="">
                <label class="" for="email">Email address</label>
                <input type="email" id="email" name="email" class="form-control" required/>
                
            </div>

            <!-- Subject -->
            <!-- <input type="hidden" name="_subject" value="submission from Arabic Instructor"> -->
            <div class="">
                <label class="l" for="subject">Subject</label>
                <input type="text" id="subject" name="_subject" class="form-control" required/>
                
            </div>
            <!-- Message input -->
            <div class="">
                <label class="" for="message">Message</label>
                <textarea class="form-control" id="message" name="message" rows="4" required></textarea>
            </div>

            <!-- Submit button -->
            <button type="submit" class="">Send</button>
        </form>
        </div>
    </layout>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .contact-form {
        width: 350px;
        display: block;
        margin: 0 auto;
    }

    .leaves {
        background-image: url('/images/leaves-three-sisters.avif');
        height: 300px;
        width: 350px;
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        display: block;
        margin: 0 auto;
        border-radius: 25px; /* rounded corners */
    }
   
    

    @media only screen and (min-width: 720px) {
        .contact-form {
            width: 450px;
        }
        .leaves {
            width: 450px;
        }
       
    }
</style>