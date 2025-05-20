<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Call Plumber</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Hero Section -->
  <section class="bg-blue-600 text-white py-16 px-8 text-center">
    <h1 class="text-4xl font-bold mb-4">Need a Plumber Fast?</h1>
    <p class="text-lg mb-6">Reliable, affordable plumbing services available 24/7.</p>
    <a href="#contact" class="bg-white text-blue-600 px-6 py-3 rounded-lg font-semibold hover:bg-gray-200 transition">
      Call Now or Book Online
    </a>
  </section>

  <!-- Services -->
  <section class="py-16 px-8">
    <h2 class="text-2xl font-bold text-center mb-10">Our Services</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-xl font-semibold mb-2">Emergency Repairs</h3>
        <p>24/7 plumbing repairs for leaks, clogs, and burst pipes.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-xl font-semibold mb-2">Drain Cleaning</h3>
        <p>Fast and effective unclogging services for sinks, showers, and toilets.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-xl font-semibold mb-2">Installations</h3>
        <p>Water heaters, faucets, toilets, and more — installed by pros.</p>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="bg-gray-100 py-16 px-8">
    <h2 class="text-2xl font-bold text-center mb-10">Happy Customers</h2>
    <div class="max-w-3xl mx-auto space-y-6">
      <blockquote class="bg-white p-6 rounded-lg shadow-md">
        <p class="italic">"Call Plumber showed up within the hour and fixed our burst pipe in no time. Excellent service!"</p>
        <footer class="mt-2 text-right">— Sarah M.</footer>
      </blockquote>
      <blockquote class="bg-white p-6 rounded-lg shadow-md">
        <p class="italic">"Professional, courteous, and affordable. Highly recommended!"</p>
        <footer class="mt-2 text-right">— James T.</footer>
      </blockquote>
    </div>
  </section>

  <!-- Contact Form -->
  <section id="contact" class="py-16 px-8">
    <h2 class="text-2xl font-bold text-center mb-10">Contact Us</h2>
    <form class="max-w-xl mx-auto bg-white p-6 rounded-lg shadow-md space-y-4">
      <input type="text" placeholder="Your Name" class="w-full border px-4 py-2 rounded-md" required />
      <input type="email" placeholder="Your Email" class="w-full border px-4 py-2 rounded-md" required />
      <input type="tel" placeholder="Phone Number" class="w-full border px-4 py-2 rounded-md" />
      <textarea placeholder="How can we help?" class="w-full border px-4 py-2 rounded-md" rows="4"></textarea>
      <button type="submit" class="w-full bg-blue-600 text-white py-2 rounded-md font-semibold hover:bg-blue-700 transition">
        Send Message
      </button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-600 text-white text-center py-6">
    &copy; 2025 Call Plumber. All rights reserved.
  </footer>

</body>
</html>
