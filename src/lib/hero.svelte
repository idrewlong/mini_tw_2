<script>
      const btn = document.getElementById("menu-btn");
      const menu = document.getElementById("menu");

      btn.addEventListener('click', navToggle)

      function navToggle () {
            btn?.classList.toggle('open')
            menu?.classList.toggle('flex')
            menu?.classList.toggle('hidden')
      }

</script>


<section id="hero">
      <!-- Hero Container -->
      <div class="container max-w-6xl mx-auto px-6 py-12">
      <!-- Nav/ Logo Container  -->
            <nav class="flex items-center justify-between font-bold text-white">
                  <img src="/logo.svg" alt="logo">
      <!-- Menu -->
      <div class="hidden h-10 font-alata md:flex md:space-x-8">
            <div class="group">
                  <a href="#">About</a>
                  <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
                  <a href="#">Careers</a>
                  <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
                  <a href="#">Events</a>
                  <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
                  <a href="#">Products</a>
                  <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
                  <a href="#">Support</a>
                  <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
      </div>
      <!-- Hamburger -->
      <div class="md:hidden">
            <button id="menu-btn" type="button" class="open z-40 block hamburger md:hidden focus:outline-none">
                  <span class="hamburger-top"></span>
                  <span class="hamburger-middle"></span>
                  <span class="hamburger-bottom"></span>
            </button>
      </div>
            </nav>
      <!-- Mobile Menu -->
            <div id="menu" class="absolute top-0 bottom-0 left-0 hidden flex flex-col self-end w-full min-h-screen py-1 pt-40 pl-12 space-y-3 text-lg text-white uppercase bg-black">
                  <a href="#" class="hover:text-pink-500">About</a>
                  <a href="#" class="hover:text-pink-500">Careers</a>
                  <a href="#" class="hover:text-pink-500">Events</a>
                  <a href="#" class="hover:text-pink-500">Products</a>
                  <a href="#" class="hover:text-pink-500">Support</a>
            </div>
      <!-- Hero -->
      <div class="max-w-lg mt-32 mb-32 p-4 font-sans text-4xl text-white uppercase border-2 md:p-10 md:m-32 md:mx-0 md:text-6xl">Impressive Experiences That Deliver</div>
      </div>
</section>