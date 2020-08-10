<template>
    <v-container>
        <v-row>
            <v-col cols="12" md="6">
                <v-textarea outlined label="■■■" v-model="口口口口" height="80vh">
                </v-textarea>
            </v-col>
            <v-col cols="12" md="6">
                <v-textarea outlined label="■■■" :value="口口口口口" height="80vh" readonly>
                </v-textarea>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
    export default {
        data: () => ({
            口口口口: '',
        }),

        computed: {
            口口口口口() {
                return this.口口口口
                    .replace(/[,.，。《》：;:；‘’“”'"/—?？…]/g, ' ')
                    .replace(/[^\s ]/g, '■')
            }
        },
    }
</script>