<template>
  <div>
    <h3>Basic!</h3>
    <basic-example />

    <h3>isError prop</h3>
    <error-prop-example />

    <h3>isDisabled prop</h3>
    <disabled-prop-example />

  </div>
</template>

<script>
  import BasicExample from './_Basic'
  import ErrorPropExample from './_ErrorProp'
  import DisabledPropExample from './_DisabledProp'

  export default {
    components: {
      BasicExample,
      ErrorPropExample,
      DisabledPropExample
    }
  }
</script>
