<script lang="ts">
	export let className: string = 'size-5';
	export let color: string = 'currentColor';
</script>

<div class="flex justify-center items-center self-start pt-1">
	<svg class={className} viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<style>
			.checkmark {
				stroke-dasharray: 22;
				stroke-dashoffset: 22;
				animation: draw 0.5s forwards;
			}
			@keyframes draw {
				to {
					stroke-dashoffset: 0;
				}
			}
		</style>
		<path class="checkmark" fill="none" stroke={color} stroke-width="3" d="M5 13l4 4L19 7" />
	</svg>
</div>
