<template>
    <nav>
        <article>
            <div>
                <i class="fa-solid fa-fan"></i>
            </div>
            <h3>
                FLEX
            </h3>
        </article>
        <MegaMenu />
        <MobileMenu />
    </nav>
</template>

<script>
import MegaMenu from './menu/MegaMenu.vue';
import MobileMenu from './menu/MobileMenu.vue';

export default {
    name: "NavigationMenu",
    components: {
        MegaMenu,
        MobileMenu
    }
}
</script>