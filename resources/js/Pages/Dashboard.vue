<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Tableau de bord" />

    <AuthenticatedLayout>
       <div class="mt-20 ">
            <h2 class="font-semibold text-xl text-gray-800 leading-tight max-w-7xl pl-5 mx-auto sm:px-6 lg:px-8">Tableau de bord</h2>

            <div class="py-12">
                <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                    <div class="bg-white overflow-hidden shadow-sm sm:rounded-lg">
                        <div class="p-6 text-gray-900">Vous êtes connectez !</div>
                    </div>
                </div>
            </div>
       </div>
    </AuthenticatedLayout>
</template>

