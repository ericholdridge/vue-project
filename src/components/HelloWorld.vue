<script setup>
defineProps({
<<<<<<< HEAD
	msg: {
		type: String,
		required: true,
	},
});
</script>

<template>
	<div class="greetings">
		<h1 class="green">{{ msg }}</h1>
		<h3>
			You’ve successfully created a project with
			<a target="_blank" href="https://vitejs.dev/">Vite</a> +
			<a target="_blank" href="https://vuejs.org/">Vue Three</a>.
		</h3>
	</div>
=======
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      You’ve successfully created a project with
      <a target="_blank" href="https://vitejs.dev/">Vite</a> +
      <a target="_blank" href="https://vuejs.org/">Vue 3</a>.
    </h3>
  </div>
>>>>>>> d997133 (First commit in the repository)
</template>

<style scoped>
h1 {
<<<<<<< HEAD
	font-weight: 500;
	font-size: 2.6rem;
	top: -10px;
}

h3 {
	font-size: 1.2rem;
=======
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
>>>>>>> d997133 (First commit in the repository)
}

.greetings h1,
.greetings h3 {
<<<<<<< HEAD
	text-align: center;
}

@media (min-width: 1024px) {
	.greetings h1,
	.greetings h3 {
		text-align: left;
	}
=======
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
>>>>>>> d997133 (First commit in the repository)
}
</style>
