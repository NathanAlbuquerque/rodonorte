<template>
    <div>
        <div class="parte1">
            <slot name="icone" />
        </div>
        <div class="parte2">
            <h3 class="text-white"><slot name="texto" /></h3>
            <slot />
        </div>
    </div>
</template>