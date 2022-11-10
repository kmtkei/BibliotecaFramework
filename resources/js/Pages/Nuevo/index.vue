<script setup>
import {Head, Link} from '@inertiajs/inertia-vue3';
import AppLayout from '@/Layouts/AppLayout.vue';
defineProps({
   nuevos: Array, 
});

</script>
<template>
    <AppLayout title="Dashboard">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Nuevo
            </h2>
        </template> 
        
        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">
                    <DIV>
                        ASDJLASKDJFLASJ
                        <P>LASDKJALKSDJ</P>
                        <P>LASDKJALKSDJ</P>
                        <P>LASDKJALKSDJ</P>
                        <P>LASDKJALKSDJ</P>
                        <P>LASDKJALKSDJ</P>
                        
                    </DIV>
                </div>
            </div>
        </div>
        </AppLayout>

        
</template>