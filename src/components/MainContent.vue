<template>
    <main>
        <!-- SERVICES SECTION -->
        <ServicesComponent />
        <!-- SERVICES SECTION END -->
        <PortfolioComponent />
        <!-- PORTFOLIO SECTION -->
        <!-- PORTFOLIO SECTION END -->
        <!-- TEAM SECTION -->
        <!-- TEAM SECTION END -->
        <!-- CONTACT SECTION -->
        <!-- CONTACT SECTION END -->
    </main>
</template>

<script>
import ServicesComponent from './maincontent/ServicesComponent.vue';
import PortfolioComponent from './maincontent/PortfolioComponent.vue';

export default {
    name: "MainContent",
    components : {
        ServicesComponent,
        PortfolioComponent
    }
}
</script>