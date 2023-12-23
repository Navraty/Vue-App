<template>
 <!-- la navbar -->
  <nav class="flex justify-between py-3 px-10 gap-2">

    <div class = "flex gap-5 items-center">
        <img src="./assets/Group 8.png" alt="">
        <a href="">AeroVision</a>
    </div>
   
    <div class="flex gap-10 items-center
                lg:flex lg:gap-10 lg:items-center
                md:flex md:gap-10 md:items-center">
      <a href="">Home</a>
      <a href="">About Me</a>
      <a href="">Service</a>
      <a href="">Blog</a>
      <a href="">Contact Me</a>

      <button class="text-white px-6 bg-[#0077FF] rounded-full">
        Let's chat
      </button>
    </div>
      
  </nav>
  <!-- la section hiro -->

  <section class="py-5 flex flex-col px-10">
    <div class="flex justify-between items-center">
      <div class="flex px-3 flex-col ">
        <p class="font-bold">Welcom to my portfolio</p>
        <span class="font-bold text-3xl">Hi I'm </span>
        <span class="font-bold text-[#0077FF] text-3xl">Robert Junior</span>
        <span class="font-bold text-3xl">Product Designer</span>
        <p class="text-gray-700 py-3">
          collaborating with highly skilled individuals,<br>
          our agency delivers top-quality services.
        </p>
        <div class="flex gap-5 py-7">
          <button class="px-3 rounded-full text-white bg-[#0077FF]">Hire Me! </button>
          <button class="px-3 rounded-full text-[#0077FF] font-bold border  ">Download Cv</button>
        </div>
      </div>
      <img src="./assets/photo1.png" class="w-[400px]" alt="">
    </div>
  </section>

  <!-- les partenaires -->

    <div class="flex bg-gray-100 py-3 px-10">
      <img src="./assets/logo-1.png" alt="">
      <img src="./assets/logo-2.png" alt="">
      <img src="./assets/logo-5.png" alt="">
      <img src="./assets/logo-6.png" alt="">
    </div>

    <div class="flex justify-evenly py-10">
      <img src="./assets/pexels1.png" class="w-[400px]" alt="">
      <div class="">
        <div>
          <span class="text-[#0077FF] text-sm font-bold">ABOUT ME</span><br>
          <span class="text-[#0077FF] font-bold text-3xl">20 Year's Experience</span><br>
          <span class="font-bold text-3xl">On Product Design</span>
          <p class="py-5">Hello there I'm Robert Junior. I specialize in web design and <br> 
            devlopement , and i"m deeply passionate and committed to my craft <br>
            With 20 years of experiences as a professional graphic designer </p>
        </div>

        <div class="flex gap-5 py-12">
          <button class="bg-[#0077FF] rounded-full text-white px-6 font-bold text-sm ">
            Main Skills
          </button>
          <button class="text-[#0077FF] rounded-full px-6 font-bold text-sm  border border-[#0077FF]">
            Awards
          </button>
          <button class="text-[#0077FF] rounded-full px-6 font-bold text-sm border border-[#0077FF]">
            Education
          </button>
        </div>

       <div class="flex flex-col gap-3">
          <div class=" ">
            <span class="font-bold ">User Experience Design - UI/UX</span>
            <div class="w-full bg-gray-200 rounded-full h-2.5">
              <div class="bg-[#0077FF] h-2.5 rounded-full" style="width: 98%"></div>
              </div>
          </div>

          <div>
            <span class="font-bold ">Web & User Interface Design - Developement</span>
            <div class="w-full bg-gray-200 rounded-full h-2.5">
              <div class="bg-[#0077FF] h-2.5 rounded-full" style="width: 92%"></div>
              </div>
          </div>

          <div>
            <span class="font-bold ">Interface Design - Animation</span>
            <div class="w-full bg-gray-200 rounded-full h-2.5">
              <div class="bg-[#0077FF] h-2.5 rounded-full" style="width: 86%"></div>
              </div>
          </div>
        </div>

      </div>
    </div>

    <div class="py-10 px-10">
      <div class="flex items-center flex flex-col">
        <span class="font-bold text-[#0077FF] text-">SERVICES</span>
        <span class="font-bold text-3xl">Exploring My Design <span class="font-bold text-3xl text-[#0077FF]">Skills</span></span>
        <span class="font-bold flex">We transform you ideas into a distinctive web project that both inspires <br>
           </span> <span class="font-bold">you and captivates your customes</span>
      </div>

      <div class="grid grid-cols-4 gap-4 py-20">
        <div class="bg-[#0077FF] rounded-lg px-5 py-6 ">
            <img src="./assets/icon.png" class="w-[200px] " alt="">
            <span class="font-bold text-white">Website / App Design <br>UX /UI Design </span>
            <p class="text-white text-semi-bold text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design</p>
              <button class="text-white">Learn more</button>
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg">
            <img src="./assets/front1.png" class="w-[50px]" alt="">
            <span class="font-bold text-white text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-white text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF]">Learn more</button>
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg">
            <img src="./assets/front1.png" class="w-[50px]" alt="">
            <span class="font-bold text-white text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-white text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF]">Learn more</button>
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg">
            <img src="./assets/front1.png" class="w-[50px]" alt="">
            <span class="font-bold text-white text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-white text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF]">Learn more</button>
        </div>
      </div>
    </div>
    
    <div class="bg-[#0077FF] py-5">
      <div class="flex items-center flex-col py-5">
        <span class="text-sm text-white">Our MILESTONES</span>
        <span class="font-bold text-3xl text-white">What sets our studio apart <br></span>
        <span class="font-bold text-3xl text-white">for your projects?</span>
      </div>

      <div class="grid grid-cols-4 gap-5 px-10 py-5">
        <div class="shadow-lg bg-white rounded-lg items-center flex flex-col">
          <span class="font-bold text-3xl">8300+</span>
          <span class="">Figma ipsum component <br> variant main layer.Hand</span>
        </div>

        <div class="shadow-lg bg-white rounded-lg items-center flex flex-col">
          <span class="font-bold text-3xl">100%</span>
          <span class="">Figma ipsum component <br> variant main layer.Hand</span>
        </div>

        <div class="shadow-lg bg-white rounded-lg items-center flex flex-col">
          <span class="font-bold text-3xl">3.5k</span>
          <span class="">Figma ipsum component <br> variant main layer.Hand</span>
        </div>

        <div class="shadow-lg bg-white rounded-lg items-center flex flex-col py-3">
          <span class="font-bold text-3xl">240+</span>
          <span class="">Figma ipsum component <br> variant main layer.Hand</span>
        </div>
      </div>

    </div>

      <div class="flex flex-col gap-4 py-10 px-10 items-center">
        <div class="flex items-center flex-col py-5">
        <span class="text-sm text-[#0077FF]">OUR PROJECTS</span>
        <span class="font-bold text-3xl text-black">Presenting My Design <br></span>
        <span class="font-bold text-3xl text-black">Porfolio and Case Studies</span>
      </div>

      <div class=" flex gap-10">
          <button class="bg-[#0077FF] rounded-full py-1 text-white px-10 font-bold text-sm ">
            All
          </button>
          <button class="text-[#0077FF] rounded-full py-1 px-6 font-bold text-sm  border border-[#0077FF]">
            UI/UX Design
          </button>
          <button class="text-[#0077FF] rounded-full py-1 px-6 font-bold text-sm border border-[#0077FF]">
            Branding Design
          </button>
          <button class="text-[#0077FF] rounded-full px-6 font-bold py-1 text-sm border border-[#0077FF]">
            Wordpress
          </button>
        </div>

        <div class="grid grid-col-3 px-10 py-6 ">
          <div class="flex gap-5 py-2">
            <img src="./assets/preview2.png" alt="">
            <img src="./assets/box.png" alt="">
            <img src="./assets/preview3.png" alt="">
          </div>

          <div class="flex gap-5 py-2">
            <img src="./assets/box (1).png" alt="">
            <img src="./assets/bloc.png" alt="">
            <img src="./assets/preview6.png" alt="">
          </div>
          
        </div>
      </div>
</template>

<script>

</script>