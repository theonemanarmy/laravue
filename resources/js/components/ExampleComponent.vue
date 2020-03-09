<template>
    <div>
        <v-container>
            <v-row>
                <v-col cols="12">
                   <v-alert type="success">Soy un alert jiji</v-alert>
                   <router-link to="/foo">a foo</router-link>
                   <router-link to="/bar">a bar</router-link>
                   <router-link to="/user/Juan">Usuario</router-link>

                </v-col>
            </v-row>

            <v-content>
                <router-view></router-view>
            </v-content>
        </v-container>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
