<template>
    <div class="max-w-sm overflow-hidden px-5">
        <form class="w-full max-w-sm">
            <div class="flex items-center px-auto">
                <input class="bg-white focus:outline-none border border-gray-300 py-2 px-4 block w-full appearance-none leading-normal mr-2" type="text" placeholder="Search Form">
                 <button class="bg-gray-300 hover:bg-gray-700 text-gray-700 font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline mr-1" type="button">
                    Search
                </button>
            </div>
        </form>
    </div>
</template>

<script>
    export default {
        name: 'SearchForm'
    }
</script>