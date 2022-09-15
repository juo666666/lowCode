<template>
  <ElDesignForm @send-savejson='handleSendJson' />
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'ElDesignPage',
  setup() {
    const handleSendJson = (data:any) => {
      console.log(data)
    }
    return {
      handleSendJson
    }
  }
})
</script>
