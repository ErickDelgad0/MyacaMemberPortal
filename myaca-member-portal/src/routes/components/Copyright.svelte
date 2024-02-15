<script>
	import { onMount } from 'svelte';
	
	let now = new Date(), month, day, year;
	let dateString;
	
	onMount(()=> {
        year = now.getFullYear();

    dateString = [year];
	})
</script>

<aside>
    <p>Copyright © {dateString} - All right reserved by Hexso LLC</p>
</aside>