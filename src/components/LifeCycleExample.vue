<template>
    <div>
<h1>Hello simret</h1>
    </div>
</template>

<script>
export default {
    beforeCreate: function (){
        console.log(`hey its not created`)
    },
    created: function ()
    {
        console.log(`hey  it is created`)
    },
    beforeMount: function ()
    {
        console.log(`itsnot mounted`)
    }
,
    mounted: function (){
            console.log(`its mounted`)
    },
    beforeUpdate: function(){
    console.log(`its not updated`);
  },
  updated:function(){
    console.log(`its updated`);
  },
  beforeDestroy: function(){
    console.log(`its not destroyed`);
  },
  destroyed: function(){
    console.log(`its distroyed`);
  },
        
    }
</script>

<style scoped>

</style>