<template>
  <div>
    <!-- Header -->
    <header class="bg-gray-900 text-white py-8 px-12">
      <div class="container mx-auto flex justify-between items-center">
        <!-- Navigasi di kiri -->
        <nav>
          <ul class="flex space-x-6">
            <li><a href="#" class="text-yellow-400">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#work">Works</a></li>

            <li><a href="#contact">Contact</a></li>
          </ul>
        </nav>
        <!-- Tulisan di kanan -->
        <h1 class="text-3xl font-bold ml-10">IFAD'S PORTFOLIO</h1>
      </div>
    </header>

    <!-- Main Section -->
    <main>
      <!-- Hero Section -->
      <section class="bg-gray-800 text-white py-20 text-center">
        <h2 class="text-5xl font-bold">Hey there!, I'm Ifadah</h2>
        <p class="text-xl mt-4">I'm an Information Technology Student</p>
        <button @click="scrollToProfile" class="mt-6 bg-yellow-400 text-black py-2 px-6 rounded font-bold">Check this out!</button>
      </section>

      <!-- About Section -->
      <section class="bg-white py-20" id="about">
        <div class="container mx-auto flex flex-col lg:flex-row items-center">
          <div class="w-full lg:w-1/2 px-4">
            <img ref="profileImage" src="./assets/WhatsApp Image 2024-09-25 at 13.22.27_2112cd64.jpg" alt="Ifadah" class="rounded-lg shadow-lg transform translate-y-20 scale-100 opacity-0 transition-all duration-700 ease-in-out">
          </div>
          <div class="w-full lg:w-1/2 px-4 lg:pl-12 mt-12 lg:mt-0">
            <h3 class="text-3xl font-bold">Who am I?</h3>
            <p class="text-gray-700 mt-6">
              My name is Ifadah Aulia Muhti Sinaga, Most people call me ifad. I'm from North Sumatera. I was born on May 4, 2005 in Sibolga, and now I'm 19 years old. I am currently studying at Brawijaya University. Nice to meet you!
            </p>
            <!-- Skills Section -->
            <h3 class="text-3xl font-bold mt-8">Skills</h3>
            <ul class="list-disc mt-4 text-gray-700 space-y-2">
              <li class="flex items-center">
                <img src="https://freepngdesign.com/content/uploads/images/javascript-logo-7539.png" alt="JavaScript" class="h-6 w-6 mr-2"> Basic JavaScript
              </li>
              <li class="flex items-center">
                <img src="https://logodix.com/logo/2030502.png" alt="Vue.js" class="h-6 w-6 mr-2"> Basic Vue.js
              </li>
              <li class="flex items-center">
                <img src="http://pngimg.com/uploads/php/php_PNG7.png" alt="PHP" class="h-6 w-6 mr-2"> Basic PHP
              </li>
              <li class="flex items-center">
                <img src="https://world-it.ro/images/logo_html.png" alt="HTML" class="h-6 w-6 mr-2"> Basic HTML
              </li>
              <li class="flex items-center">
                <img src="http://logonoid.com/images/css3-logo.png" alt="CSS" class="h-6 w-6 mr-2"> Basic CSS
              </li>
              <li class="flex items-center">
                <img src="https://vectorified.com/images/art-icon-transparent-31.png" alt="Graphic Design" class="h-6 w-6 mr-2"> Graphic Design
              </li>
              <li class="flex items-center">
                <img src="https://png.pngtree.com/png-vector/20221028/ourmid/pngtree-pen-icon-object-symbol-office-vector-png-image_39885430.png" alt="Logo Maker" class="h-6 w-6 mr-2"> Logo maker
              </li>
            </ul>

            <h3 class="text-3xl font-bold mt-8">Hobbies</h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-4 ">
              <div class="relative bg-white shadow-lg rounded-lg overflow-hidden">
                <img src="https://images.unsplash.com/photo-1523592121529-f6dde35f079e?q=80&w=500&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Traveling" class="w-full h-40 object-cover">
                <div class="absolute inset-0 bg-gray-500 opacity-0 hover:opacity-75 transition-opacity duration-300 flex items-center justify-center">
                  <div class="text-center">
                    <h4 class="text-lg font-bold text-white">Traveling</h4>
                    <p class="text-white">Likes to go exploring and walking around</p>
                  </div>
                </div>
              </div>
              <div class="relative bg-white shadow-lg rounded-lg overflow-hidden">
                <img src="https://images.unsplash.com/photo-1525715843408-5c6ec44503b1?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Reading" class="w-full h-40 object-cover">
                <div class="absolute inset-0 bg-gray-500 opacity-0 hover:opacity-75 transition-opacity duration-300 flex items-center justify-center">
                  <div class="text-center">
                    <h4 class="text-lg font-bold text-white">Reading</h4>
                    <p class="text-white">Enjoys reading books and comics</p>
                  </div>
                </div>
              </div>
              <div class="relative bg-white shadow-lg rounded-lg overflow-hidden">
                <img src="https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Gaming" class="w-full h-40 object-cover">
                <div class="absolute inset-0 bg-gray-500 opacity-0 hover:opacity-75 transition-opacity duration-300 flex items-center justify-center">
                  <div class="text-center">
                    <h4 class="text-lg font-bold text-white">Gaming</h4>
                    <p class="text-white">Loves playing video games</p>
                  </div>
                </div>
              </div>
              <div class="relative bg-white shadow-lg rounded-lg overflow-hidden">
                <img src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?q=80&w=2071&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Photography" class="w-full h-40 object-cover">
                <div class="absolute inset-0 bg-gray-500 opacity-0 hover:opacity-75 transition-opacity duration-300 flex items-center justify-center">
                  <div class="text-center">
                    <h4 class="text-lg font-bold text-white">Photography</h4>
                    <p class="text-white">Sometimes take a random picture <br> in every place</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Portfolio Section -->
      <section class="bg-gray-100 py-20 p-20" id="work">
        <div class="container mx-auto text-center">
          <h3 class="text-3xl font-bold">My Work</h3>
          <div class="flex justify-center mt-8 space-x-4">
            <a href="#graphic" class="text-gray-600">Graphic</a>
            <a href="#art" class="text-gray-600">Pencil Art</a>
            <a href="#photography" class="text-gray-600">Photography</a>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mt-8">
            <div class="relative bg-white shadow-lg rounded-lg overflow-hidden">
              <img src="./assets/portfolio 2.jpg" alt="Project 1" class="w-full h-64 object-cover">
              <div class="absolute inset-0 bg-yellow-400 opacity-0 hover:opacity-75 transition-opacity duration-300 flex items-center justify-center">
                <div class="text-center">
                  <h4 class="text-lg font-bold text-black">Design Project</h4>
                </div>
              </div>
            </div>
            <div class="relative bg-white shadow-lg rounded-lg overflow-hidden">
              <img src="./assets/portfolio 3.jpg" alt="Project 2" class="w-full h-64 object-cover">
              <div class="absolute inset-0 bg-yellow-400 opacity-0 hover:opacity-75 transition-opacity duration-300 flex items-center justify-center">
                <div class="text-center">
                  <h4 class="text-lg font-bold text-black">Pencil Art</h4>
                </div>
              </div>
            </div>
            <div class="relative bg-white shadow-lg rounded-lg overflow-hidden">
              <img src="./assets/portfolio 4.jpg" alt="Project 3" class="w-full h-64 object-cover">
              <div class="absolute inset-0 bg-yellow-400 opacity-0 hover:opacity-75 transition-opacity duration-300 flex items-center justify-center">
                <div class="text-center">
                  <h4 class="text-lg font-bold text-black">Photography</h4>
                </div>
              </div>
            </div>
          </div>
          <button @click="scrollToTop" class="mt-8 px-6 py-2 bg-yellow-400 text-black rounded font-bold">Back to the top</button>
        </div>
      </section>

      <!-- Contact Section -->
      <section class="bg-gray-800 text-white py-20 text-center" id="contact">
        <h3 class="text-3xl font-bold mb-4">Contact Me</h3>
        <p class="mb-4">Jalan Joyo Agung Perum PNS<br> C-09, Kel. Tlogomas, Kec. Lowokwaru,<br> Kota Malang</p>
        <div class="container mx-auto flex flex-col md:flex-row justify-center items-center">
          <div class="flex items-center mb-4 md:mb-0 md:mr-8">
            <img src="https://logos-world.net/wp-content/uploads/2020/04/Instagram-Emblem.png" alt="Instagram" class="h-8 w-15">
            <a href="@ifadahaulia_" class="text-yellow-400 hover:underline">@ifadahaulia_</a>
          </div>
          <div class="flex items-center mb-4 md:mb-0 md:mr-8">
            <img src="https://multarte.com.br/wp-content/uploads/2018/10/logo-whatsapp-png-transparente12.png" alt="WhatsApp" class="h-8 w-15 mr-2">
            <a href="+62-821-6543-9899" class="text-yellow-400 hover:underline">+62-821-6543-9899</a>
          </div>
          <div class="flex items-center">
            <img src="https://www.shareicon.net/data/2048x2048/2016/07/13/606885_linkedin_2048x2048.png" alt="LinkedIn" class="h-10 w-15 mr-1">
            <a href="Ifadah Aulia" target="_blank" class="text-yellow-400 hover:underline">Ifadah Aulia</a>
          </div>
          <div class="flex items-center">
          </div> 
        </div>
      </section>
    </main>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  mounted() {
    const profileImage = this.$refs.profileImage;

    // Using IntersectionObserver for scroll animation from bottom to top
    const observer = new IntersectionObserver(
      (entries) => {
        entries.forEach((entry) => {
          if (entry.isIntersecting) {
            entry.target.classList.add('translate-y-0', 'opacity-100', 'scale-100');
          } else {
            entry.target.classList.remove('translate-y-0', 'opacity-100', 'scale-90');
          }
        });
      },
      {
        threshold: 0.5, // Animation triggers when 50% of the element is visible
      }
    );

    observer.observe(profileImage);
  },
  methods: {
    scrollToProfile() {
      const profileImage = this.$refs.profileImage;
      if (profileImage) {
        profileImage.scrollIntoView({ behavior: 'smooth' });
      }
    },
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    },
  },
};
</script>

<style scoped>
/* Additional styles if needed */
</style>
