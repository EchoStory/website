<style>
    .menu-horizontal ul{
        margin-top: 1.25rem;
    }
</style>

<div class="navbar bg-white border-b border-gray-200 px-4 py-2">
    <div class="navbar-start">
        <div class="dropdown">
            <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor">
                    <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M4 6h16M4 12h8m-8 6h16" />
                </svg>
            </div>
            <ul class="menu menu-sm dropdown-content bg-white rounded-box z-50 mt-3 w-52 p-2 shadow-lg border border-gray-200">
                <li><a class="hover:bg-gray-100">Item 1</a></li>
                <li>
                    <a class="hover:bg-gray-100">Parent</a>
                    <ul class="p-2 bg-gray-50">
                        <li><a class="hover:bg-gray-100">Submenu 1</a></li>
                        <li><a class="hover:bg-gray-100">Submenu 2</a></li>
                    </ul>
                </li>
                <li><a class="hover:bg-gray-100">Item 3</a></li>
            </ul>
        </div>
        <a class="btn btn-ghost text-xl font-bold text-gray-800">&gt; echo "Story"</a>
    </div>
    <div class="navbar-center hidden lg:flex">
        <ul class="menu menu-horizontal px-1">
            <li><a class="hover:bg-gray-100 rounded-md px-3 py-2">Item 1</a></li>
            <li>
                <details>
                    <summary class="hover:bg-gray-100 rounded-md px-3 py-2 cursor-pointer">Parent</summary>
                    <ul class="p-2 bg-white shadow-lg border border-gray-200 rounded-md">
                        <li><a class="hover:bg-gray-100 rounded-md px-3 py-1">Submenu 1</a></li>
                        <li><a class="hover:bg-gray-100 rounded-md px-3 py-1">Submenu 2</a></li>
                    </ul>
                </details>
            </li>
            <li><a class="hover:bg-gray-100 rounded-md px-3 py-2">Item 3</a></li>
        </ul>
    </div>
</div>