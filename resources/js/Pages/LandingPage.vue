<script setup>
</script>

<template>
    
        <div class="bg-gray-100">
      <!-- Hero Section -->
      <section class="hero py-20">
        <div class="container mx-auto">
          <h1 class="text-4xl font-bold mb-4">Welcome to Task Manager</h1>
          <p class="text-gray-600 text-lg">Manage your tasks efficiently.</p>
          <div class="mt-8">
            <a href="/tasks" class="btn-primary">Get Started</a>
            <a href="/login" class="btn-secondary">Log In</a>
          </div>
        </div>
      </section>
  
      <!-- Features Section -->
      <section class="features py-20">
        <div class="container mx-auto">
          <h2 class="text-3xl font-bold mb-8">Features</h2>
          <div class="flex flex-wrap justify-center">
            <!-- Feature 1 -->
            <div class="w-full md:w-1/2 lg:w-1/3 p-4">
              <div class="bg-white rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-4">Task Tracking</h3>
                <p class="text-gray-600">Track and organize your tasks with ease.</p>
              </div>
            </div>
  
            <!-- Feature 2 -->
            <div class="w-full md:w-1/2 lg:w-1/3 p-4">
              <div class="bg-white rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-4">Collaboration</h3>
                <p class="text-gray-600">Work together with your team on shared tasks.</p>
              </div>
            </div>
  
            <!-- Feature 3 -->
            <div class="w-full md:w-1/2 lg:w-1/3 p-4">
              <div class="bg-white rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-4">Due Date Reminders</h3>
                <p class="text-gray-600">Never miss a deadline with automatic reminders.</p>
              </div>
            </div>
          </div>
        </div>
      </section>
  
      <!-- Testimonials Section -->
      <section class="testimonials py-20">
        <div class="container mx-auto">
          <h2 class="text-3xl font-bold mb-8">Testimonials</h2>
          <div class="flex flex-wrap -mx-4">
            <!-- Testimonial 1 -->
            <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
              <div class="bg-white rounded-lg shadow-lg p-6">
                <p class="text-gray-600">"Task Manager helped me stay organized and focused on my work. Highly recommended!"</p>
                <p class="text-gray-800 font-semibold mt-4">- John Doe</p>
              </div>
            </div>
  
            <!-- Testimonial 2 -->
            <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
              <div class="bg-white rounded-lg shadow-lg p-6">
                <p class="text-gray-600">"I've tried several task management tools, but Task Manager is by far the best. It has all the features I need."</p>
                <p class="text-gray-800 font-semibold mt-4">- Jane Smith</p>
              </div>
            </div>
  
            <!-- Testimonial 3 -->
            <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
              <div class="bg-white rounded-lg shadow-lg p-6">
                <p class="text-gray-600">"With Task Manager, I can easily track and prioritize my tasks. It has greatly improved my productivity."</p>
                <p class="text-gray-800 font-semibold mt-4">- Michael Johnson</p>
              </div>
            </div>
          </div>
        </div>
      </section>
  
      <!-- Call to Action Section -->
      <section class="cta py-20">
        <div class="container mx-auto text-center">
          <h2 class="text-3xl font-bold text-white mb-4">Start managing your tasks today!</h2>
          <a href="/register" class="btn-primary">Sign Up</a>
        </div>
      </section>
    </div>
    
  
  </template>
  
  <script>
  export default {
    name: 'LandingPage',
  }
  </script>
  
  <style scoped>
  /* Customize the styles as needed */
  .hero {
    background-image: url('/path/to/hero-image.jpg');
    background-position: center;
    background-size: cover;
  }
  
  .btn-primary {
    padding: 12px 24px;
    background-color: #4a90e2;
    color: #fff;
    text-decoration: none;
    border-radius: 4px;
    font-weight: bold;
    transition: background-color 0.3s;
  }
  
  .btn-primary:hover {
    background-color: #3f81d9;
  }
  
  .btn-secondary {
    padding: 12px 24px;
    background-color: #fff;
    color: #4a90e2;
    text-decoration: none;
    border-radius: 4px;
    font-weight: bold;
    transition: background-color 0.3s;
    border: 1px solid #4a90e2;
  }
  
  .btn-secondary:hover {
    background-color: #f2f7ff;
  }
  </style>
  