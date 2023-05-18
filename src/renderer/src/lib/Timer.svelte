<script>


	export let events;
	export let handleDeleteEvent;
</script>

<div>
			<button on:click={() => handleDeleteEvent()}>START</button>
            <button on:click={() => handleDeleteEvent()}>RESET</button>

		</div>
		<!-- <Item title={item} index={index} onEdit={onEdit} onRemove={onRemove} /> -->

<style>
	div {
		border-top: 3px solid lightcoral;
        display: flex;
	}
</style>