<template>
    <header class="bg-white shadow h-16 flex justify-between items-stretch">
        <router-link :to="{ name: 'home' }" class=" inline-flex items-center h-full">
            Home
        </router-link>
        <div class="flex items-center gap-1">
            <router-link :to="{ name: 'byName' }"
                class=" inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">
                Search Meals
            </router-link>
            <router-link :to="{ name: 'byLetter' }"
                class=" inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">
                meals by letters
            </router-link>
            <router-link :to="{ name: 'byIngredient' }"
                class=" inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">
                meals by ingredients
            </router-link>
        </div>
    </header>
</template>
