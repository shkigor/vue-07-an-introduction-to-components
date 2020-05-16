<template>
    <div id="app" class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <servers></servers>
            <app-server-details></app-server-details>
        </div>
        <hr>
        <appFooter></appFooter>
    </div>
</template>

<script>
    import Header from "./components/Shared/Header";
    import Footer from "./components/Shared/Footer";
    import Servers from "./components/Server/Servers";
    import ServerDetails from "./components/Server/ServerDetails";

    export default {
        components: {
            appHeader: Header,
            appFooter: Footer,
            Servers,
            'app-server-details': ServerDetails
        }
    }
</script>

<style>

</style>
