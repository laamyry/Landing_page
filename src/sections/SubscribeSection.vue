<script setup>
import { ref } from 'vue'
import Swal from 'sweetalert2'

let email = ref('')
let emailError = ref(false)
const emailRegex = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/

let handleSubmit = () => {
  if (!email.value || !emailRegex.test(email.value)) {
    emailError.value = true
  } else {
    console.log(emailRegex.test(email.value))
    Swal.fire({
      icon: 'success',
      title: 'Thank You',
      text: `${email.value} subscribed to our newsletter!`,
    })
  }
}
</script>

<template>
  <!-- Newsletter Section Start -->
  <div id="subscribe" class="">
    <div class="">
      <section class=""></section>
    </div>
  </div>
  <!-- Newsletter Section End -->
</template>
