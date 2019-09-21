<template>
  <v-app >
 <toolbar />
    
       <full-page :options="options">
      <div class="section">
    <home />
      </div>
      <div class="section">
       <qapage />
      </div>
    </full-page>
    
    
  </v-app>
</template>

<script>
import toolbar from './components/toolbar'
import home from './components/homepage'
import qapage from './components/qapage'


export default {
  name: 'App',
  components: {
    toolbar,
    home,
    qapage
  },
  data: () => ({
    //
  }),
   options: {
        licenseKey: 'YOUR_KEY_HEERE',
        menu: '#menu',
        anchors: ['page1', 'page2', 'page3'],
        sectionsColor: ['#41b883', '#ff5f45', '#0798ec']
      },
};
</script>

<style >
.home {
    background: url('./assets/firstbg.jpg');
    background-size: cover;
    width: 100%;
    height: 100%;
  
}

</style>
