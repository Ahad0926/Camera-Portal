<!-- src/page.svelte -->
<div class="min-h-screen flex flex-col flex-auto flex-shrink-0 antialiased bg-white dark:bg-gray-700 text-black dark:text-white">
  <div class="h-full ml-7 mt-7 mb-10 md:ml-64">

    <h2 class="text-center text-3xl">Monday, August 14</h2>
    <h1 class="text-center text-6xl pb-3">Good Morning</h1>
    
    <!--Overview-->
    <div class="max-h-screen">
      <div class="max-w-4xl mx-auto">
        <div class="bg-gray-100 rounded-3xl p-8">
          <div class="grid grid-cols-3">
            <div class=" text-xs">
              <select class="bg-gray-100 ml-2 cursor-pointer">
                <option value="" disabled selected>My Week</option>
                <option>Option 1</option>
                <option>Option 2</option>
              </select>
            </div>
            <div class=" text-xs">Tasks Completed</div>
            <div class=" text-xs">Collaborators</div>
          </div>
        </div>
      </div>
    </div>

    <!--grid for Main Page Content-->
    <div class="grid grid-cols-2 p-4 gap-4 text-black">
      
      <!--Customization Prompt-->
      <div class="col-span-2">
        <div class="grid grid-cols-2 p-4 gap-2 text-black box-border border-2 rounded-3xl bg-gray-100">
          <ul class="space-y-2">
            <li class="p-4 bg-gray-200 border rounded-xl text-gray-800 space-y-2 font-bold">Customize Home</li>
            <li class="p-4 bg-gray-200 border rounded-xl text-gray-800 space-y-2 font-bold">Continue setting up your project</li>
            <li class="p-4 bg-gray-200 border rounded-xl text-gray-800 space-y-2 font-bold">Download mobile and desktop apps</li>
            <li class="p-4 bg-gray-200 border rounded-xl text-gray-800 space-y-2 font-bold">Browse integrations</li>
            
            <li class="p-4 bg-gray-200 border rounded-xl text-gray-800 space-y-2 font-bold">Personalize your profile</li>
          </ul>
          <div class="col my-auto mx-auto">
            <div>
              <p>Customize your background and add widgets to make Home your own.</p>
              <button class="rounded-lg py-2 px-4 my-3 bg-blue-500 hover:bg-blue-400 text-white">Customize Home</button>
              <br/>
              <button class="hover:text-gray-500">Next step ></button>
            </div>
          </div>
        </div>
      </div>
      
      <!--Priorities-->
      <div class="col">
        <div class="grid grid-cols-2 p-4 gap-2 text-black box-border border-2 rounded-3xl bg-gray-100">
          <div class="col-span-2 flex items-center mb-4">
              <h2 class="text-xl font-semibold">My Priorities</h2>
          </div>
          <ul class="col-span-2 flex space-x-4">
              <button class="hover:text-gray-400">Upcoming</button>
              <button class="hover:text-gray-400">Overdue</button>
              <button class="hover:text-gray-400">Completed</button>
          </ul>
          <div class="col-span-2">
            <input type="text" placeholder="Click here to add a task..." class="w-full px-4 py-2 bg-gray-100 rounded mb-4">
              <ul class="space-y-2">
                <li class="flex items-center">
                  <input type="checkbox" class="mr-2">
                  <span>Sample Task 1</span>
                </li>
                <li class="flex items-center">
                  <input type="checkbox" class="mr-2">
                  <span>Sample Task 2</span>
                </li>
              </ul>
          </div>
        </div>
      </div>
    
      <!--Projects-->
      <div class="col">
        <div class="grid grid-cols-2 p-4 gap-2 pb-36 text-black box-border border-2 rounded-3xl bg-gray-100">
          <div class="col-span-2 flex items-center mb-4">
              <h2 class="text-xl font-semibold">Projects</h2>
              <select class="bg-gray-100 ml-2 cursor-pointer">
                <option value="" disabled selected>Recent</option>
                <option>Project 1</option>
                <option>Project 2</option>
              </select>
          </div>
          <div class="col-span-2">
            <button class="hover:text-gray-400">+ Create Project</button>
          </div>
        </div>
      </div>
    
    </div>
  </div>
</div>