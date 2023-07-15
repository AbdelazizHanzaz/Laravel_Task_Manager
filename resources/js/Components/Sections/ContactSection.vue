<template>
  <section class="bg-gray-900 dark:text-white py-16">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
        <div>
          <h2 class="text-4xl font-bold mb-6">Contact Us</h2>
          <div class="flex mb-4 items-start">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-green-500 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2C6.486 2 2 6.486 2 12c0 2.944 1.137 5.752 3.187 7.812.574.573 1.2 1.106 1.876 1.617l.149.104c.264.175.546.317.843.423.296.106.604.174.922.204.318.03.638.02.956-.026.317-.047.628-.143.925-.296l.128-.08c.279-.176.54-.393.772-.647l.057-.055c.518-.57.952-1.206 1.29-1.897l.08-.127c.153-.293.25-.607.296-.925.035-.318.056-.638.03-.956-.026-.317-.12-.625-.295-.922l-.055-.14c-.252-.232-.47-.494-.645-.773l-.08-.13c-.245-.34-.46-.703-.63-1.082l-.033-.08C16.04 17.752 19.858 16 24 16v-2c0-4.411-3.589-8-8-8z" />
            </svg>
            <div>
              <h4 class="text-lg font-semibold">Address</h4>
              <p class="text-neutral-500 dark:text-neutral-200">123 Main Street, City, Country</p>
            </div>
          </div>
          <div class="flex mb-4 items-start">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-green-500 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2C6.486 2 2 6.486 2 12c0 2.944 1.137 5.752 3.187 7.812.574.573 1.2 1.106 1.876 1.617l.149.104c.264.175.546.317.843.423.296.106.604.174.922.204.318.03.638.02.956-.026.317-.047.628-.143.925-.296l.128-.08c.279-.176.54-.393.772-.647l.057-.055c.518-.57.952-1.206 1.29-1.897l.08-.127c.153-.293.25-.607.296-.925.035-.318.056-.638.03-.956-.026-.317-.12-.625-.295-.922l-.055-.14c-.252-.232-.47-.494-.645-.773l-.08-.13c-.245-.34-.46-.703-.63-1.082l-.033-.08C16.04 17.752 19.858 16 24 16v-2c0-4.411-3.589-8-8-8z" />
            </svg>
            <div>
              <h4 class="text-lg font-semibold">Phone</h4>
              <p class="text-neutral-500 dark:text-neutral-200">+1 123 456 7890</p>
            </div>
          </div>
          <div class="flex items-start">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-green-500 mr-2">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2C6.486 2 2 6.486 2 12c0 2.944 1.137 5.752 3.187 7.812.574.573 1.2 1.106 1.876 1.617l.149.104c.264.175.546.317.843.423.296.106.604.174.922.204.318.03.638.02.956-.026.317-.047.628-.143.925-.296l.128-.08c.279-.176.54-.393.772-.647l.057-.055c.518-.57.952-1.206 1.29-1.897l.08-.127c.153-.293.25-.607.296-.925.035-.318.056-.638.03-.956-.026-.317-.12-.625-.295-.922l-.055-.14c-.252-.232-.47-.494-.645-.773l-.08-.13c-.245-.34-.46-.703-.63-1.082l-.033-.08C16.04 17.752 19.858 16 24 16v-2c0-4.411-3.589-8-8-8z" />
            </svg>
            <div>
              <h4 class="text-lg font-semibold">Email</h4>
              <p class="text-neutral-500 dark:text-neutral-200">info@example.com</p>
            </div>
          </div>
        </div>
        <div>
          <form>
            <div class="mb-4">
              <label for="name" class="block text-lg font-semibold">Name</label>
              <input type="text" id="name" class="w-full rounded-lg border-gray-300 bg-gray-100 dark:bg-gray-800 px-4 py-2 focus:border-green-500 focus:ring-green-500" />
            </div>
            <div class="mb-4">
              <label for="email" class="block text-lg font-semibold">Email</label>
              <input type="email" id="email" class="w-full rounded-lg border-gray-300 bg-gray-100 dark:bg-gray-800 px-4 py-2 focus:border-green-500 focus:ring-green-500" />
            </div>
            <div class="mb-4">
              <label for="message" class="block text-lg font-semibold">Message</label>
              <textarea id="message" rows="5" class="w-full rounded-lg border-gray-300 bg-gray-100 dark:bg-gray-800 px-4 py-2 focus:border-green-500 focus:ring-green-500"></textarea>
            </div>
            <button type="submit" class="bg-green-600 hover:bg-green-700 text-white font-bold py-3 px-6 rounded-lg">
              Send Message
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection',
};
</script>
