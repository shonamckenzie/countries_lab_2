<template lang='html'>
<article v-if="country">
    <p>{{ country.name }}</p>

</article>
  
</template>

<script>
export default {
    name: 'country-detail',
    props: ['country']

}
</script>

<style lang='css'>

</style>