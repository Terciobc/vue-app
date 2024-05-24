<template>
    <div class="h-fit pb-10 w-3/4 m-auto mt-[10vh] bg-slate-600 border rounded-md">
        <h1 class="text-center text-white text-3xl font-bold px-8 py-8">
          ToDo List Application
        </h1>
        <div class="flex flex-col">
          <div class="flex flex-row w-[80%] mb-2 rounded-md m-auto bg-slate-800">
            <p class="px-6 py-4 text-lg text-yellow-50">
                To Do Item
            </p>
            <Button props="Remove" title="Remove" bgColor="bg-red-400">
              <span class="icon">
                <i class="fas trash" style="color: #d11515;"></i>
              </span>
              
            </Button>
            <Button props="Remove" title="Add" bgColor="bg-green-400" />
            <Button props="Remove" title="Update" bgColor="bg-blue-400" />
        </div>
      </div>
    </div>
          
</template>

<script setup>
  import Button from './Button.vue';

</script>