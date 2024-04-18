<script lang="ts">
	export let data: import("./$types").PageData;
</script>

<h1><span>Hello from the edge!</span></h1>

<div class="info">
	{data.city}
	{data.ip}
</div>