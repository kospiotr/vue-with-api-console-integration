<template>
  <q-page>
    <api-console no-toolbars :model-location="model_location"></api-console>
  </q-page>
</template>
<script>
/*eslint-disable */
export default {
  name: 'Console',
  data() {
    return {
      model_location: "/statics/amf-model.json"
    }
  }

}
</script>
