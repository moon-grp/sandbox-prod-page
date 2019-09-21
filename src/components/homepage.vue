<template>
    
       <v-container fluid fill-height class="home">
        <v-layout justify-center align-start column pa-5>
            <div class="body-1 font-weight-black white--text text-left">Premium Coffee</div>
            <div class="display-2 font-weight-black white--text text-left mb-3">A cup of coffee is one of</div>
            <div class="display-2 font-weight-black white--text text-left mb-3">the most important,</div>
            <div class="display-2 font-weight-black white--text text-left mb-3">simple pleasures in life.</div>
            <v-btn rounded dark class="mt-5 brown darken-4">
             <v-icon left>mdi-hand-pointing-right</v-icon>   Shop now
            </v-btn>
        </v-layout>
    </v-container>
</template>


<script>
export default {
    name:'homepage'
    
}
</script>

<style >

.home {
    background: url('../assets/firstbg.jpg');
    background-size: cover;
    width: 100%;
    height: 100%;
}

</style>