<script setup>
import { useLayout } from '@/layout/composables/layout';

const { toggleMenu, toggleDarkMode, isDarkTheme } = useLayout();
</script>

<template>

    <div class="card flex flex-col gap-4">
        <div class="font-semibold text-xl">Навигация и подсказки</div>
        <Message severity="success">Слева вверху открыть/скрыть меню <i class="pi pi-bars"></i></Message>
        <Message severity="success">Справа вверху темная/светлая тема <i class="pi pi-bars"></i></Message>
        <Message severity="success">Настроить палитру справа вверху <i class="pi pi-bars"></i></Message>
        
            <div class="flex flex-wrap gap-2">
                <Button label="Раскрыть главное меню" @click="toggleMenu"></Button>
                <button class="layout-menu-button layout-topbar-action" @click="toggleMenu">
                <i class="pi pi-bars"></i>
            </button>
            </div>
    </div>

    <div className="card">
        
        <div class="font-semibold text-xl mb-4">Empty Page</div>
        <p>Us this page to start from scratch and place your custom content.</p>
        <div class="font-semibold text-xl">Default</div>
        <div class="flex flex-wrap gap-2">
                    <Button label="Раскрыть меню"></Button>
                    <Button label="Disabled" :disabled="true"></Button>
                    <Button label="Link" class="p-button-link" />
        </div>
    </div>


</template>
