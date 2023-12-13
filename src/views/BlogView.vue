<template>
  <div class="container mx-auto p-3 md:p-8">
    <div class="flex flex-col-reverse md:flex-row relative">
      <div class="w-full md:w-2/3">
        <div class="flex flex-col gap-4 md:px-20 fade-zoom-up">
          
          <div class="flex">
            <img :style="{ width: '200px', height: 'auto' }" src="/img/porfolio-kmph.jpg" alt="Your Image Description" />
            <div class="white-text">College Matriculation Pahang</div>
            </div>
        </div>
      </div>
       
      <div class="w-full md:w-1/3 h-fit p-8 md:sticky md:top-24">
        <!-- Sidebar -->
        <div class="flex flex-col text-left">
          <div class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">Just a random article i fetch using API. And below is my contact. 
          </div>
          <div class="h-[1px] mt-7 mb-7 w-20 bg-amber-200 aos-init aos-animate mr-2"></div>
          <div class="md:block">
            <div class="text-white text-md font-semibold">My contact link</div>
            <div class="mt-3 flex flex-wrap gap-1">
              <a
          class="py-2 px-3 rounded-2xl bg-[#1e1e1f] hover:bg-white/20 text-white text-xs cursor-pointer"
          href="https://api.whatsapp.com/send?phone=+601119221464"
        >
          +601119221464
        </a>
        <a
          class="py-2 px-3 rounded-2xl bg-[#1e1e1f] hover:bg-white/20 text-white text-xs cursor-pointer"
          href="mailto:aimanahmad0004@gmail.com"
        >
          aimanahmad0004@gmail.com
        </a>
        <a
          class="py-2 px-3 rounded-2xl bg-[#1e1e1f] hover:bg-white/20 text-white text-xs cursor-pointer"
          href="mailto:ca19063@student.ump.edu.my"
        >
          ca19063@student.ump.edu.my
        </a></div>
            <!-- <div class="h-[1px] mt-7 mb-7 w-20 bg-amber-200 aos-init aos-animate mr-2"></div>
            <div class="text-white text-md font-semibold">Popular Articles</div> -->

          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style scoped>
.paraf {
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
  text-overflow: ellipsis;
  overflow: hidden;
}
@media (min-width: 768px) { 
  .paraf {
    display: -webkit-box;
  }
}
@keyframes fadeZoomUp {
  0% {
    opacity: 0;
    transform: scale(0.5);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
.fade-zoom-up {
  animation: fadeZoomUp 1s ease-in-out;
  /* animation-delay: 1000ms; */
}

</style>