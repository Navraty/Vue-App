

<template>

 <!-- la navbar -->

  <nav class="flex justify-between py-3 px-10 gap-2">

    <div class = "flex gap-5 items-center">
        <a href="#"><img src="./assets/Group 8.png" alt=""></a>
        <a href="" class="font-bold">AeroVision</a>
    </div>
   
    <div class="hidden 
                 lg:items-center lg:font-bold lg:flex
                md:flex-row md:gap-10 md:items-center md:block md:font-bold">

      <a href="">Home</a>
      <a href="">About Me</a>
      <a href="">Service</a>
      <a href="">Blog</a>
      <a href="">Contact Me</a>

      <button class="text-white px-6 bg-[#0077FF] py-2 rounded-full ml-[150px] hover:bg-white hover:text-[#0077FF] border border-[#0077FF]">
        Let's chat
      </button>
    </div>
    <a href=""><img src="./assets/menu.png" class="w-[40px] md:hidden lg:hidden" alt="menu"></a>
    
  </nav>
 
  <!-- la section hiro -->

  <section class="py-5 flex flex-col px-2">

    <div class="flex flex-col-reverse gap-5 items-center  
                lg:flex-row lg:justify-arround  lg:text-wrap
                md:flex md:justify-between md:items-center">

      <div class="flex px-3 flex-col
                  Lg:flex-row lg:flex-col lg:px-10">

        <p class="font-bold">Welcom to my portfolio</p>
        <span class="font-bold text-4xl">Hi I'm </span>
        <span class="font-bold text-[#0077FF] text-4xl">Robert Junior</span>
        <span class="font-bold text-4xl">Product Designer</span>
        <p class="text-gray-700 py-3">
          collaborating with highly skilled individuals,<br>
          our agency delivers top-quality services.
        </p>
        <div class="flex gap-6 py-7">
          <button class="px-3 rounded-full text-white bg-[#0077FF] font-bold  py-2 hover:bg-white hover:text-[#0077FF] border border-[#0077FF]">Hire Me! </button>
          <button class="px-3 rounded-full text-[#0077FF] font-bold border py-2 hover:bg-[#0077FF] hover:text-white flex gap-2">Download Cv <img src="./assets/icon-download 1.png" alt=""> </button>
       
        </div>
      </div>
      <img src="./assets/photo1.png" class="w-[400px]" alt="">
    </div>
  </section>

  <!-- les partenaires -->

  <div class="flex flex-col gap-3 items-center bg-gray-100 
                lg:flex-row lg:bg-gray-100 lg:py-3 lg:px-2">
      <img src="./assets/logo-1.png" alt="">
      <img src="./assets/logo-2.png" alt="">
      <img src="./assets/logo-3 (2).png" alt="">
      <img src="./assets/logo-5.png" alt="">
      <img src="./assets/logo-6.png" alt="">
      
  </div>
  <!-- la section A props -->

  <div class="flex flex-col items-center py-5 px-5
                lg:flex-row lg:justify-arround lg:py-10
                md:flex-row md:justify-evenly md:py-10">

      <img src="./assets/pexels1.png" class="w-[400px]" alt="">

      <div class="">
        <div class=" flex flex-col  py-3 px-5 text-wrap ">
          <span class="text-[#0077FF] text-sm font-bold">ABOUT ME</span><br> 
          <span class="text-[#0077FF] font-bold text-3xl">20 Year's Experience</span><br>
          <span class="font-bold text-3xl">On Product Design</span>
          <p class="py-5">Hello there I'm Robert Junior. I specialize in web design and <br> 
            devlopement , and i"m deeply passionate and committed to my craft <br>
            With 20 years of experiences as a professional graphic designer </p>
        </div>

        <div class="flex flex-col gap-5 px-5 py-3
                    lg:flex-row lg:gap-5 lg:py-12
                    md:flex-row md:gap-5 md:py-12">

          <button class="bg-[#0077FF] rounded-full py-2 text-white px-6 font-bold text-sm hover:bg-white hover:text-[#0077FF] border border-[#0077FF] ">
            Main Skills
          </button>
          <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
            Awards
          </button>
          <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm border border-[#0077FF] hover:bg-[#0077FF] hover:text-white ">
            Education
          </button>
        </div>
        <!-- la progress-bar -->

       <div class="flex flex-col gap-3 px-5 py-5
                    lg:flex-row lg:flex-col lg:gap-3
                    md:flex md:flex-col md:gap-3">
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
    <!-- les Skills -->

  <div class="py-10 px-10">
      <div class="flex flex-col items-center  
                  lg:flex-row lg:items-center lg:flex lg:flex-col
                  md:flex-row md:items-center md:flex md:flex-col">

        <span class="font-bold text-[#0077FF] ">SERVICES</span>
        <span class="font-bold text-3xl py-2">Exploring My Design <span class="font-bold text-3xl text-[#0077FF]">Skills</span></span>
        <span class="text-semibold flex ">We transform you ideas into a distinctive web project that both inspires <br>
           </span> <span class="">you and captivates your customes</span>
      </div>

      <div class="grid gap-3 py-3
                  lg:grid lg:grid-cols-4 lg:gap-4 lg:py-20
                  md:grid md:grid-cols-2 md:gap-4 md:py-20">

        <div class="bg-[#0077FF] rounded-lg px-5 py-6  ">
            <img src="./assets/icon.png" class="w-[200px] " alt="">
            <span class="font-bold text-white">Website / App Design <br>UX /UI Design </span>
            <p class="text-white text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design</p>
               <button class="text-white flex items-center gap-3">Learn more <img src="./assets/Arrow 1 (3).png" alt=""></button>
           
              
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg  hover:bg-[#0077FF] hover:text-white">
            <img src="./assets/front1.png" class="w-[50px] " alt="">
            <span class="font-bold text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-black text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF] flex items-center gap-3">Learn more <img src="./assets/Arrow 1 (2).png" alt=""></button>
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg  hover:bg-[#0077FF] hover:text-white border border-[#0077FF]">
            <img src="./assets/front1.png" class="w-[50px]" alt="">
            <span class="font-bold text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-black text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF] flex items-center gap-3">Learn more <img src="./assets/Arrow 1 (2).png" alt=""></button>
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg hover:bg-[#0077FF] hover:text-white border border-[#0077FF]">
            <img src="./assets/front1.png" class="w-[50px]" alt="">
            <span class="font-bold text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-black text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF] flex items-center gap-3">Learn more <img src="./assets/Arrow 1 (2).png" alt=""></button>
        </div>
      </div>
  </div>
    <!-- les projets -->

  <div class="bg-[#0077FF] py-5">
      <div class="flex items-center flex-col py-5">
        <span class="text-sm text-white font-bold">OUR MILESTONES</span>
        <span class="font-bold text-3xl text-white">What sets our studio apart <br></span>
        <span class="font-bold text-3xl text-white">for your projects?</span>
      </div>

      <div class="flex flex-col bg-[#0077FF] gap-5 px-3
                  lg:grid lg:grid-cols-4 lg:gap-5 lg:px-10 lg:py-5
                  md:grid md:grid-cols-2 md:gap-5 md:px-10 py-5
                  ">

        <div class="shadow-lg bg-white rounded-lg items-center flex flex-col g">
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
    <!-- Our Project -->

  <div class="flex flex-col gap-4 py-8 px-10 items-center">
        <div class="flex flex-col items-center px-5
                      lg:flex-row lg:items-center lg:flex-col lg:py-5
                      md:flex md:items-center md:flex-col md:py-5">

        <span class="text-sm text-[#0077FF] font-bold">OUR PROJECTS</span>
        <span class="font-bold text-3xl text-black">Presenting My Design <br></span>
        <span class="font-bold text-3xl text-black">Porfolio and Case Studies</span>
      </div>

      <div class=" grid grid-cols-2 gap-3
                  lg:grid lg:grid-cols-4 gap-10
                md:grid md:grid-cols-2 mdp-10">
          <button class="bg-[#0077FF] rounded-full py-2 text-white px-10 font-bold text-sm  hover:bg-white hover:text-[#0077FF] border border-[#0077FF]">
            All
          </button>
          <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm  border border-[#0077FF] hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
            UI/UX Design
          </button>
          <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm border border-[#0077FF] hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
            Branding Design
          </button>
          <button class="text-[#0077FF] rounded-full px-6 font-bold py-2 text-sm border border-[#0077FF] hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
            Wordpress
          </button>
        </div>

        <div class="flex flex-col gap-5
                    lg:grid lg:grid-cols-3 lg:grid-col-col lg:gap-4 
                    md:grid md:grid-col-3 md:px-10 md:py-6">

            <img src="./assets/preview2.png" alt="">
            <img src="./assets/box.png" alt="">
            <img src="./assets/preview3.png" alt="">

            <img src="./assets/box (1).png" alt="">
            <img src="./assets/bloc.png" alt="">
            <img src="./assets/preview6.png" alt="">
          
        </div>
  </div>
    <!-- les temoignages -->

  <div>
        <div class="flex items-center flex-col">
          <span class="text-[#0077FF] text-sm font-bold">TESTIMONIALS</span>
          <span class="text-3xl font-bold mb-6">The Trust From Clients</span>
          <div class="flex gap-2 py-3">
           <a href=""> <img src="./assets/bton.png" alt=""></a>
           <a href=""> <img src="./assets/button arrow.png" alt=""></a>
          </div>
        </div>

        <div class="flex flex-col 
                    lg:grid lg:grid-cols-4 
                    md:grid md:grid-cols-4 md:gap-2 md:px-10 ">

          <div class="border border-gray-200 shadow-lg flex flex-col items-center px-3 rounded-lg py-5 ">
            <img src="./assets/1.png" class="w-[100px]" alt="">
            <img src="./assets/etoile.png" class="w-[6em]" alt="">
            <p class=" ">
              Lorem ipsum dolor sit amet  molestiae consectetur adipisicing elit  molestiae <br>
             Excepturi hic exercitationem  molestiae <br>
               recusandae dolores molestiae adipisci labore quia, corporis rerum sequi <br>Excepturi hic exercitationem  molestiae <br>
               <br>
               
            </p>
            <p class=" flex items-center flex-col py-2">
              <span class="font-bold">SAVANNAH NGUYEN</span>
              <span>President of Saves</span>
          </p>
          </div>

          <div class="border border-gray-200  rounded-lg shadow-lg flex flex-col items-center py-5 px-3">
            <img src="./assets/Ellipse 3.png" class="w-[100px]" alt="">
            <img src="./assets/etoile.png" class="w-[6em]" alt="">
            <p>
              Lorem ipsum dolor sit amet  molestiae consectetur adipisicing elit  molestiae <br>
             Excepturi hic exercitationem  molestiae <br>
               recusandae dolores molestiae adipisci labore quia, corporis rerum sequi <br>Excepturi hic exercitationem  molestiae <br>
               <br>
            </p>
            <p class=" flex items-center flex-col py-2">
              <span class="font-bold">JENNY WILSON</span>
              <span>Medical assistant</span>
          </p>
          </div>

          <div class="bg-[#0077FF] border  rounded-lg border-gray-200 shadow-lg flex flex-col items-center py-5 px-3">
            <img src="./assets/4.png" class="w-[100px]" alt="">
            <img src="./assets/etoile.png" class="w-[6em]" alt="">
            <p class="text-white">
              Lorem ipsum dolor sit amet  molestiae consectetur adipisicing elit  molestiae <br>
             Excepturi hic exercitationem  molestiae <br>
               recusandae dolores molestiae adipisci labore quia, corporis rerum sequi <br>Excepturi hic exercitationem  molestiae <br>
               <br>
            </p>
            <p class=" flex items-center flex-col py-2">
              <span class="font-bold text-white">ESTHER HOWARD</span>
              <span class="text-white">Nursing Assistant</span>
            </p>
            </div>

          <div class="border border-gray-200 rounded-lg shadow-lg flex flex-col items-center py-5 px-3">
            <img src="./assets/5.png" class="w-[100px]" alt="">
            <img src="./assets/etoile.png" class="w-[6em]" alt="">
            <p>
              Lorem ipsum dolor sit amet  molestiae consectetur adipisicing elit  molestiae <br>
             Excepturi hic exercitationem  molestiae <br>
               recusandae dolores molestiae adipisci labore quia, corporis rerum sequi <br>Excepturi hic exercitationem  molestiae <br>
               <br>
            </p>
            <p class=" flex items-center flex-col py-2">
              <span class="font-bold">CAMERON WILLIAMSON</span>
              <span>Marketing Coordinator</span>
          </p>
          </div>

        </div>
  </div>
  <!-- le footer -->
    <div class=" mt-8 flex flex-col text-white items-center bg-[#0077FF] py-5 ">
      <h2 class="font-bold text-xl mb-2">CONTACT ME</h2>
      <h1 class="font-bold text-3xl mb-2">Request Free Consultancy</h1>
    </div>
  <footer class="bg-[#0077FF]">
    <div class="flex flex-col py-4 px-3
                lg:grid lg:grid-cols-2 lg:gap-4 lg:px-10 lg:justify-arround 
                md:grid md:grid-cols-2 md:gap-4 md:px-10 md:justify-arround md:py-5">

      <div class="bg-white text-black rounded-lg h-[22em] px-6 mb-5 ">  
        <p class="font-bold text-1xl mt-5">Hotline 24/7:</p>
        <p class="font-bold text-3xl">(+23) 5535 68 68</p>
        <p class="mt-14 "><b>Address:</b>3727 Westheimer Rd., Santa Ana, Illinois 65486</p> 
        <p class="mt-2"><b>Email:</b> info@example.com</p>
        <p class="mt-2"><b>Work Hours:</b> Mon - Sat : 10:00 - 18:00</p>
      </div>

      <form class="grid gap-3 lg:gap-6">

        <div class="flex flex-col gap-3 py-3
                    lg:flex-row lg:justify-between
                    md:flex md:justify-between md:gap-2">

                    <input class="py-3 px-4 text-white rounded lg:w-1/2" type="email" placeholder="Email Address*">
                    <input class="py-3 px-4 text-white rounded lg:w-1/2" type="text" placeholder="Name*">
         </div>

          <textarea class="py-3 px-4 text-white rounded h-[50px]" placeholder="How can we help you?"></textarea>
          <textarea class="py-3 px-4 text-white rounded h-[11em] mt-2" placeholder="How can we help you?"></textarea>
          <div>
              <input type="checkbox" id="terms">
              <label for="terms" class="ml-2 text-white">By submitting, I agree to the Terms & Conditions</label>
        </div>
          <button class="py-2 px-4 bg-blue-800 hover:bg-[#0077FF] text-white font-bold rounded-full lg:w-1/2">Request Now</button>
      </form>
    </div>

    <div class="flex flex-col items-center
                lg:flex-row lg:justify-between">

      <div class = "flex text-white flex-col items-center gap-2
                    lg:flex-row lg:gap-5 lg:items-center lg:px-10 lg:text-white
                    md:flex md:gap-5 md:items-center md:px-10 md:text-white">

        <a href="#"><img src="./assets/Group 8.png" alt=""></a>
        <a href="" class="font-bold">AeroVision</a>
        <p>© AeroVision | ©2021 All rights reserved.</p>
      </div>  
          
      <div class="text-white flex gap-5 py-2 items-center
                  lg:text-white lg:flex lg:px-10">
            <span>© FOLLOW US:</span>
        <div class="flex gap-2">
              <img src="./assets/facebook icon.png" alt="">
              <img src="./assets/Group 7.png" alt="">
              <img src="./assets/icon linkedin.png" alt="">
              <img src="./assets/icon email.png" alt="">
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
</script>