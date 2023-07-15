<template>
    <section class="bg-gray-900 dark:text-white py-16">
      <div class="container mx-auto">
        <h2 class="text-3xl font-bold text-center mb-8">Testimonials</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg p-6 flex flex-col items-center text-green-800">
            <div class="mb-4">
              <img src="https://via.placeholder.com/64" alt="User Avatar" class="w-16 h-16 rounded-full" />
            </div>
            <div class="text-center">
              <p class="text-lg font-semibold mb-2">John Doe</p>
              <p class="text-gray-800">"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque ac felis leo. Nunc vitae lorem et ante consectetur convallis."</p>
            </div>
          </div>
          <div class="bg-white rounded-lg p-6 flex flex-col items-center text-green-800">
            <div class="mb-4">
              <img src="https://via.placeholder.com/64" alt="User Avatar" class="w-16 h-16 rounded-full" />
            </div>
            <div class="text-center">
              <p class="text-lg font-semibold mb-2">Jane Smith</p>
              <p class="text-gray-800">"Sed feugiat dui sed lacus maximus, id ullamcorper nunc rutrum. Morbi pellentesque consectetur nisl vitae pharetra."</p>
            </div>
          </div>
          <div class="bg-white rounded-lg p-6 flex flex-col items-center text-green-800">
            <div class="mb-4">
              <img src="https://via.placeholder.com/64" alt="User Avatar" class="w-16 h-16 rounded-full" />
            </div>
            <div class="text-center">
              <p class="text-lg font-semibold mb-2">David Johnson</p>
              <p class="text-gray-800">"Integer eu erat non neque vestibulum cursus id vitae lorem. Aenean euismod pharetra interdum."</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'TestimonialsSection',
  };
  </script>
  