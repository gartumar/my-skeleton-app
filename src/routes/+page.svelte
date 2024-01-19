<script lang="ts">
	import { getModalStore } from '@skeletonlabs/skeleton';
	import type { ModalSettings, ModalComponent } from '@skeletonlabs/skeleton';

	import FormComponent from '$lib/components/form_component.svelte';

	const modalStore = getModalStore();

	function modalComponentForm(): void {
		const c: ModalComponent = { ref: FormComponent };
		const modal: ModalSettings = {
			type: 'component',
			component: c
		};
		modalStore.trigger(modal);
	}
</script>

<div class="mt-16 flex flex-col gap-12">
	<p>
		Click on the elements on this screen and look at their visual appearance. Then click on "View in
		Modal" button and notice some differences.
	</p>
	<hr />
	<FormComponent />
	<hr />
	<button type="button" class="btn variant-filled-warning" on:click={modalComponentForm}
		>View in Modal</button
	>
</div>
