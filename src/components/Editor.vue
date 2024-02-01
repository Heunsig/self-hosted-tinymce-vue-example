<script setup lang="ts">
import Editor from '@tinymce/tinymce-vue'
</script>

<template>
  <main id="sample">
    <Editor
      api-key="no-api-key"
      :init="{
        plugins: 'lists link image table code help wordcount'
      }"
    />
  </main>
</template>