<template>
  <button class="middle-xs brdr-none bg-cl-transparent p0 inline-flex cl-secondary">
    <span class="hidden-xs h6">
      {{ $t('Edit') }}
    </span>
    <i class="material-icons h4 p5 pr0">mode_edit</i>
  </button>
</template>

<script>
import editButton from 'core/components/blocks/Microcart/EditButton'

export default {
  mixins: [editButton]
}
</script>
