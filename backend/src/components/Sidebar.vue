<template>
    <div class="w-[200px] transition-all bg-indigo-700 text-gray-100 py-4 px-2">
        <router-link :to="{ name: 'app.dashboard' }" class="flex py-2 px-3 mb-2 rounded transition-colors items-center hover:bg-black/20">
            <span class="mr-2">
                <HomeIcon class="w-5" />
            </span>
            <span class="text-sm">Dashboard</span>
        </router-link>

        <router-link :to="{ name: 'app.products' }" class="flex py-2 px-3 mb-2 rounded transition-colors items-center hover:bg-black/20">
            <span class="mr-2">
                <ListBulletIcon class="w-5" />
            </span>
            <span class="text-sm">Products</span>
        </router-link>

        <router-link :to="{ name: 'app.dashboard' }" class="flex py-2 px-3 mb-2 rounded transition-colors items-center hover:bg-black/20">
            <span class="mr-2">
                <UsersIcon class="w-5" />
            </span>
            <span class="text-sm">Users</span>
        </router-link>

        <router-link :to="{ name: 'app.dashboard' }" class="flex py-2 px-3 mb-2 rounded transition-colors items-center hover:bg-black/20">
            <span class="mr-2">
                <ChartBarIcon class="w-5" />
            </span>
            <span class="text-sm">Reports</span>
        </router-link>

    </div>
</template>

<script setup>
import { HomeIcon, UsersIcon, ListBulletIcon, ChartBarIcon } from '@heroicons/vue/24/solid'
</script>

<style scoped></style>
