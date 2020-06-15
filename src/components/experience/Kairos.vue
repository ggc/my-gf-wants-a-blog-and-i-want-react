<template>
    <div>
        <p class="text-2xl">Frontend Developer</p>
        <p>
            KAIROS DIGITAL SOLUTIONS
            <span class="float-right">(May 2018 – Present)</span>
        </p>

        <p>
            Project: Verisure's security experts sales app
            <span
                class="float-right"
            >Madrid Area, Spain</span>
        </p>
        <br />

        <p>We provide an hybrid app to allow security experts to register activities, monitor operations, and display statistics and sales feedback about any client or product, sold or installed.</p>

        <ul class="list-disc list-inside my-4">
            Technically talking it's an Ionic 3 + Angular 5 + Spring + MongoDB + CI/CD project built with:
            <li>Microservices</li>
            <li>Docker for the deployments (and local environments)</li>
            <li>Everything deployed in Azure with Kubernetes as well as some On-Premise solutions (dev)</li>
            <li>Acceptance testing using Gherkin sintax over Selenium and Appium with Python</li>
            <li>Google Analytics for close-user evaluation</li>
            <li>And one NodeJS service with GraphQL to aggregate and filter requests</li>
        </ul>
        <ul class="list-disc list-inside my-4">
            We're currently working using tools like:
            <li>Scrum framework</li>
            <li>Code Review (Validation and Verification)</li>
            <li>SOLID principles</li>
            <li>Gitflow with merge strategy (for now)</li>
            <li>And ping-pong in between</li>
        </ul>

        <i>
            P.S. We're a team of 7* who lunch together and talk a lot ❤
            * 2 Back, 2 Front, 1 Full(Back oriented), 1 SM and 1 QA
        </i>
    </div>
</template>

<script>
export default {
    name: "kairos",
    props: {
        msg: String
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
