<template>
	<v-container grid-list-xs>
		<div>
			<p class="pink lighten-4 red--text text--darken-3">
				Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolor
				doloribus minima quos voluptatibus eaque. Magnam aut saepe maiores iure
				vero officia aliquid nam est. Odio quibusdam incidunt officiis tenetur
				reprehenderit.
			</p>
			<h1>home page</h1>
			<h1 class="display-4">main text</h1>
			<h1 class="display-1">main text</h1>
			<p class="headline">headeline</p>
			<p class="subheading">subheading</p>
			<p class="caption">caption</p>
			<v-btn class="blue brown--text text--darken-4">button</v-btn>
			<v-btn flat dark depressed class="blue">button</v-btn>
			<v-btn color="primary" elevation="2" text>
				button without background</v-btn
			>
			<v-btn color="red" elevation="2" plain>zz</v-btn>
			<v-btn dark depressed class="red">
				<v-icon left>mdi-email</v-icon>
				<span>email me</span>
			</v-btn>
			<v-btn depressed class="success">
				<v-icon>mdi-rocket</v-icon>
			</v-btn>
		</div>
	</v-container>
</template>

<script>
/*  import HelloWorld from '../components/HelloWorld' */

export default {
	name: "Home",

	components: {},
};
</script>
