<template>
    <v-container>
        <v-row>
            <v-col class="my-4" cols="12">
                <h1 class="text-center display-2 font-weight-bold mb-3">Bâtiment A</h1>
                <v-img
                    :src="require('@/assets/schema_batiment.jpg')"
                    class="my-3"
                    contain
                    height="200"
                />
            </v-col>

            <v-col class="mb-5">
                <v-row align="center" justify="center">
                    <v-card color="primary" dark>
                        <v-card-title>Zone 1</v-card-title>
                        <v-card-text>
                          <span>Nombre de logements :</span><br />
                          <span>Ratio habitable :</span><br />
                          <span>Surface utile (m²) :</span><br />
                          <span class="ml-2">Groupe 1 :</span><br />
                          <span class="ml-2">Groupe 2 :</span><br />
                          <span class="font-weight-medium">Nombre d'occupants :</span><br />
                        </v-card-text>
                    </v-card>
                </v-row>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    name: "LayoutOccupationZone",

};
</script>
