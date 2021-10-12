<script>
	import ContactCard from "./ContactCard.svelte"

	let name = ''
	let jobTitle, description, imgUrl = '';
	//https://images.unsplash.com/photo-1526297003708-f5a1c2c9c6e7?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1740&q=80
	
</script>

<style>


	.cards{
		display: flex;
	}
</style>


<input type='text' placeholder="Name" bind:value='{name}' />
<input type='text' placeholder="Job Title" bind:value='{jobTitle}' />
<input type='text' placeholder="Description" bind:value='{description}' />
<input type='text' placeholder="Image URL" bind:value='{imgUrl}' />
<div class='cards'>
	<ContactCard userName="{name}" jobTitle="{jobTitle}" description="{description}" imgUrl='{imgUrl}' />
</div>

