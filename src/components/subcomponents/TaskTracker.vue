<script>
    // TODO: Complete the code
    export default { 
        data() {
            return {
                
            }
        },
        // Hint: insert properties task (Object) and idx (Number)
        props: {
            task: Object,
            idx: Number
        }
    }
</script>

<template>
    <!-- TODO: add your template code here --> 
   <div class="card" style="width: 18rem; display: inline-block">
  <img src="..." class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Deadline: {{ task.deadline }}</h5>
    <p class="card-text">{{ task.desc }}</p>
    <a href="#" class="btn btn-primary" @click="$emit('removeTask', idx)">Done</a>
  </div>
</div>
</template>


