<template>
    <div>
        <b-navbar toggleable="lg" type="dark" variant="info">
            <b-navbar-nav>
                <b-button v-b-toggle.sidebar>Open Menu</b-button>
            </b-navbar-nav>
        </b-navbar>
    </div>
</template>

<script>
export default {
    name: "Header"
}
</script>