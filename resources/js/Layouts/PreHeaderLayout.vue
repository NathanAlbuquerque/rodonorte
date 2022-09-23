<script setup>
    import InfosLink from '@/Components/InfosLink.vue';
    import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
    import { Link } from '@inertiajs/inertia-vue3';
</script>

<template>
    <div>
        <div class="bg-red-600">
            <InfosLink>
                <font-awesome-icon icon="fa-brands fa-whatsapp" />
                <template #texto>Atendimento</template>
                <Link :href="route('dashboard')" class="text-white">(99) 9411516564</Link>
            </InfosLink>
        </div>
    </div>
</template>