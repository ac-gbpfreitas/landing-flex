<template>
    <main>
        <!-- SERVICES SECTION -->
        <ServicesComponent />
        <!-- SERVICES SECTION END -->
        <!-- PORTFOLIO SECTION -->
        <PortfolioComponent />
        <!-- PORTFOLIO SECTION END -->
        <!-- TEAM SECTION -->
        <TeamComponent />
        <!-- TEAM SECTION END -->
        <!-- CONTACT SECTION -->
        <!-- CONTACT SECTION END -->
    </main>
</template>

<script>
import ServicesComponent from './maincontent/ServicesComponent.vue';
import PortfolioComponent from './maincontent/PortfolioComponent.vue';
import TeamComponent from './maincontent/TeamComponent.vue';

export default {
    name: "MainContent",
    components : {
        ServicesComponent,
        PortfolioComponent,
        TeamComponent
    }
}
</script>