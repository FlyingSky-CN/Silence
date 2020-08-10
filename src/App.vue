<template>
    <v-app>
        <v-app-bar app color="white" elevate-on-scroll>
            <div class="d-flex align-center">
                <v-toolbar-title>■■■■</v-toolbar-title>
            </div>

            <v-spacer></v-spacer>

            <v-btn href="#" target="_blank" text>
                <span class="mr-2">■■■■ ■■</span>
                <v-icon small>mdi-earth</v-icon>
            </v-btn>
        </v-app-bar>

        <v-main>
            <Editor></Editor>
        </v-main>
    </v-app>
</template>

<script>
    import Editor from './components/Editor';

    export default {
        name: 'App',

        components: {
            Editor
        },

        data: () => ({
            //
        }),
    };
</script>