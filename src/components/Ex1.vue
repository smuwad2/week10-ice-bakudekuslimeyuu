<script>
    //import component
    import SoundIcon from './subcomponents/SoundIcon.vue'
    
    export default { 
        components: {
            SoundIcon, 
        },
        data() {
            return {
                soundLevel: 0,
                // message: "",
            }
        }, 
    }
</script>

<template>
    <input type="text" v-model="message">
   Sound level
    <input type="number" min="0" max="3" v-model="soundLevel"> 
    <!-- TODO: Add Code Here to make use of the component -->
    <!-- <SoundIcon v-bind:Level ="soundLevel"></SoundIcon> -->
     <SoundIcon :Level="soundLevel" ></SoundIcon>
    <!-- v-bind sound level is refeering   -->
    <!-- "soundLevel" is referring to the parent  -->
</template>

