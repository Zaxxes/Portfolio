<template>
    <v-footer dark padless>
        <v-card flat tile class="black white--text py-5 px-5 text-center" width="100%">
            <v-row>
                <v-col cols="12" sm="4">
                    <v-card-text class="white--text pt-2">
                        <v-btn icon>
                        </v-btn >
                    </v-card-text>
                </v-col>
                    <v-col cols="12" sm="4">
                        <v-card-text class="pt-2">
                            <v-btn v-for="icon in icons" :key="icon" class="mx-1 white--text" icon>
                                <v-icon size="24">{{ icon }}</v-icon>
                            </v-btn>
                        </v-card-text>
                    </v-col>
                    <v-col cols="12" sm="4">
                        <v-card-text class="pt-2">
                            <v-btn class="mx-20 white--text" icon>
                                <v-icon color="#043A4E">mdi-human-greeting</v-icon>                              
                            </v-btn>
                            <p>Created by Bernie</p>
                        </v-card-text>
                    </v-col>
            </v-row>
            </v-card>
            
    </v-footer>
</template>

<script>
export default {
    name: 'FooterComponent',

    data: () =>({
        icons:[
            "mdi-facebook", "mdi-twitter", "mdi-instagram", "mdi-linkedIn"
        ]
    })
}

</script> 

<style>

</style>