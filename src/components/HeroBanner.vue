<template>
    <header>
        <section>
            <SocialMenu />
            <NavigationMenu />
            <PageTitle />
        </section>
    </header>
</template>

<script>
import NavigationMenu from './NavigationMenu.vue';
import SocialMenu from './herobanner/SocialMenu.vue';
import PageTitle from './herobanner/PageTitle.vue';

export default {
    name: "HeroBanner",
    components: {
        NavigationMenu,
        SocialMenu,
        PageTitle
    }
}
</script>