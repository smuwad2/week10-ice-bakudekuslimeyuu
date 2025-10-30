<script>
    export default { 
        data() {
            return {
                soundEmojis: ['🔇', '🔈', '🔉', '🔊']
            }
        },
        // TODO: add code to define a necessary prop

        props:{
                Level: Number ,
            }
        // props : ['Level', 'msg']
    }
</script>

<template>
    <!-- TODO: add your template code here. Use span element. --> 
     <span> {{this.soundEmojis[Level]}} </span> 

</template>