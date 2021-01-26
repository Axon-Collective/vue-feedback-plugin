<template>
  <div class="max-w-xs rounded-lg border shadow hover:shadow-lg transition duration-150 flex-col mx-8 mt-8 h-full overflow-hidden">
		<div class="grid grid-cols-3 text-center justify-between font-medium bg-blue-500 mb-8">
			<button class="bg-blue-500 hover:bg-white text-white hover:text-blue-500 py-2 px-3">Question</button>
			<button class="bg-blue-500 hover:bg-white text-white hover:text-blue-500 py-2 px-3">Request</button>
			<button class="bg-blue-500 hover:bg-white text-white hover:text-blue-500 py-2 px-3">Support</button>
		</div>
		<form action="" class="mb-8">
			<button class="mx-6 mb-2 rounded-full py-1 px-2 bg-blue-500 hover:bg-blue-500 text-white text-sm shadow hover:shadow-lg transition duration-150">Can't find what you're looking for?</button>
			<button class="mx-6 mb-2 rounded-full py-1 px-2 bg-blue-500 hover:bg-blue-500 text-white text-sm shadow hover:shadow-lg transition duration-150">Common question #2</button>
			<button class="mx-6 mb-2 rounded-full py-1 px-2 bg-blue-500 hover:bg-blue-500 text-white text-sm shadow hover:shadow-lg transition duration-150">Common question #3</button>
		</form>
	</div>
</template>

<script>
export default {
  name: "VueFeedbackPopup",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="postcss" scoped>

h1 {
  @apply text-white text-3xl;
}
</style>
