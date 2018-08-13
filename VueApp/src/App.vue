<template>
  <div id="app">
    <CommonHeader>

    </CommonHeader>
    <router-view/>
    <CommonFooter></CommonFooter>
  </div>
</template>
import CommonHeader from '@/components/CommonHeader'
<script>
export default {
  components: {
    CommonHeader
   },
};
</script>

