

<script>
	import logo from '$lib/images/logo.png';
   
    import Sidebar from './Sidebar.svelte';


</script>

    <nav class="absolute top-0 w-full border-gray-20 dark:border-gray-700">
        <div class="flex flex-wrap items-center justify-between mx-auto">
            <a href="/" class="flex items-center md:w-1/4 w-2/4">
                <img src={logo} class="w-full" alt="" />
            </a>
            <button data-collapse-toggle="navbar-multi-level" type="button"
                class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
                aria-controls="navbar-multi-level" aria-expanded="false">
                <span class="sr-only">Open main menu</span>
                <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                    viewBox="0 0 17 14">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M1 1h15M1 7h15M1 13h15" />
                </svg>
            </button>
            <div class="md:w-3/4 w-full md:pe-40 flex justify-center pe-0 hidden md:block" id="navbar-multi-level">
                <ul
                    class="main-nav flex justify-between w-full font-medium p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-9 md:mt-0 md:border-0 md:bg-white dark:border-gray-700 flex-wrap">
                    <li class="w-full mb-6 md:mb-0 md:w-auto">
                        <a href="/"
                            class="text-2xl block py-2 pl-3 pr-4 text-white rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500">My
                            House</a>
                    </li>
                    <li class="w-full mb-6 md:mb-0 md:w-auto">
                        <a href="/"
                            class="text-2xl block py-2 pl-3 pr-4 text-white rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500">Vergleich</a>
                    </li>
                    <li class="w-full mb-6 md:mb-0 md:w-auto">
                        <a href="/"
                            class="text-2xl block py-2 pl-3 pr-4 text-white rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500">About
                            Us</a>
                    </li>
                    <li class="w-full md:w-auto">
                        <a href="/"
                            class="text-2xl block py-2 pl-3 pr-4 text-white rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500">Kontakt</a>
                    </li>
                </ul>
            </div>

        <Sidebar/>
        </div>
    </nav>

