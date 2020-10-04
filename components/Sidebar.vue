<template>
    <div>
        <b-sidebar id="sidebar" aria-labelledby="sidebar" no-header shadow>
            <template v-slot:default="{hide}">
                <nav>
                    <b-nav vertical>
                        <b-nav-item active @click="hide">Home</b-nav-item>
                        <b-nav-item @click="hide">Files</b-nav-item>
                        <b-nav-item @click="hide">Favorites</b-nav-item>
                        <b-nav-item @click="hide">Shared</b-nav-item>
                    </b-nav>
                </nav>
            </template>
        </b-sidebar>
    </div>
</template>

<script>
export default {
    name: "Sidebar"
}
</script>