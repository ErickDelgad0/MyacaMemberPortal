<!--
  Infinite scrolling skewed carousel
  Created by Steven Tey (https://twitter.com/steventey)

  As seen on Dub.co
-->

<div class="flex flex-col justify-start items-start pt-8 pb-8">
    <div class="ml-32">
        <!-- Title with adjusted size -->
        <h2 class="text-xl md:text-2xl font-bold text-blue-500">Our Services</h2>
        <!-- Paragraphs directly underneath the title -->
        <p class="mt-2">Our team offers top-notch web development services tailored to meet your business needs.</p>
        <p>We ensure high-quality, scalable solutions that help you achieve your goals.</p>
    </div>
</div>

  
<div class="flex w-screen items-center justify-center">
    <div class="relative w-full max-w-screen-lg overflow-hidden">
        
      <!-- For some reason the white vignette effect don't work in this sandbox but if you uncomment the following lines in VSCode, they should work -->
  
        <div class="pointer-events-none absolute -top-1 z-10 h-20 w-full bg-gradient-to-b from-white to-transparent" />
        <div class="pointer-events-none absolute -bottom-1 z-10 h-20 w-full bg-gradient-to-t from-white to-transparent" />
        <div class="pointer-events-none absolute -left-1 z-10 h-full w-20 bg-gradient-to-r from-white to-transparent" />
        <div class="pointer-events-none absolute -right-1 z-10 h-full w-20 bg-gradient-to-l from-white to-transparent" />
  
      <div class="mx-auto grid h-[250px] w-[300px] animate-skew-scroll grid-cols-1 gap-5 sm:w-[600px] sm:grid-cols-2">
  
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
        <div class="flex cursor-pointer items-center space-x-2 rounded-md border border-gray-100 p-5 shadow-md transition-all hover:-translate-y-1 hover:translate-x-1 hover:scale-[1.025] hover:shadow-xl">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-6 w-6 flex-none text-primary">
            <circle cx="12" cy="12" r="10" />
            <path d="m9 12 2 2 4-4" />
          </svg>
          <p class="text-gray-600">Priority support</p>
        </div>
      </div>
    </div>
  </div>
  