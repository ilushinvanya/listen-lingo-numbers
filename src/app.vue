<template>
	<router-view/>
</template>

<script setup lang="ts">
import { useQuasar } from 'quasar';

const $q = useQuasar()
$q.dark.set('auto')
</script>
