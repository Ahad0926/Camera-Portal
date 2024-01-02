<!--src/lib/Sidebar-->
<aside class="fixed top-0 left-0 w-64 h-full">
    <div class="overflow-y-auto py-5 px-3 h-full bg-white border-r border-gray-200">
        <!--Logo and collapse button-->
        <div class="pt-2 pb-10 border-t border-b border-gray-200">
            <ul class="flex items-center">
                <li class="flex items-center justify-between w-full">
                    <span>Logo</span>
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8 hover:bg-gray-100 px-2 rounded-full cursor-pointer">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M10.5 19.5L3 12m0 0l7.5-7.5M3 12h18" />
                    </svg>
                </li>
            </ul>
        </div>
        <!--Navigation-->
        <ul>
            <li>
                <a class="flex p-2 text-gray-900 hover:bg-gray-100" href="#">Home</a></li>
            <li>
                <a class="flex p-2 text-gray-900 hover:bg-gray-100" href="#">My Tasks</a></li>
            <li>
                <a class="flex p-2 text-gray-900 hover:bg-gray-100" href="#">Inbox</a></li>
            <li>
                <a class="flex p-2 text-gray-900 hover:bg-gray-100" href="#">Reporting</a></li>
            <li>
                <a class="flex p-2 text-gray-900 hover:bg-gray-100" href="#">Portfolios</a></li>
            <li>
                <a class="flex p-2 text-gray-900 hover:bg-gray-100" href="#">Goals</a></li>
        </ul>
        <div class="pt-2 pb-10 border-t border-b border-gray-200">
            <ul class="flex items-center">
                <a href="#" class="flex items-center justify-between w-full hover:bg-gray-100 p-2 rounded">
                    My Workspaces
                    <span class="hover:bg-gray-100 px-2 rounded-full">+</span>
                </a>
            </ul>
        </div>
    <!--Footer Navigation-->
    </div>
    <div class="absolute bottom-0 left-0 justify-center w-full lg:flex bg-white border-t border-gray-200">
        <ul class="w-full">
            <li class="border border-gray-200">
                <a href="#" class="block p-2 text-gray-900 hover:bg-gray-100">
                    Invite Teammates</a></li>
            <li class="border border-gray-200">
                <a href="#" class="block p-2 text-gray-900 hover:bg-gray-100">
                    Help and Getting Started</a></li>
        </ul>
    </div>
  </aside>