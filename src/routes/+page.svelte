<script lang="ts">
	import { toast } from 'svelte-sonner';
</script>

<button onclick={() => toast.success('This is a toast!')}> Show toast </button>
