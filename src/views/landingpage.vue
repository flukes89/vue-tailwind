

<template>
  <div class="flex gap-4  mt-8">

<leftsidebar />

    
<CenterBar />
    
<RightsideBar />

    

  </div>
</template>


<script>
import TextField from '../components/fields/TextField.vue';
import PasswordField from '../components/fields/PasswordField.vue';
import leftsidebar from '../components/ui/leftsidebar.vue';
import CenterBar from '../components/ui/CenterBar.vue';
import RightsideBar from '../components/ui/RightsideBar.vue';

export default {
  data() {
      return {
          email: null,
          password: null
      }

  },
  components: {
      TextField,
      PasswordField,
      leftsidebar,
      CenterBar,
      RightsideBar
  },
  methods: {
      getData() {
          console.warn("value:", this.email, this.password);
      },
      change(e) {

          console.warn("changed", e);
      }
  },

}

</script>
