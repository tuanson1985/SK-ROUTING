<script>
	import { page } from '$app.stores';
	const greetings = {
		en: 'Hello',
		es: 'Hola',
		fr: 'Bộnur'
	};
	const { lang } = $page.params;
	const greeting = greetings[lang];
</script>

<h1>{greeting}</h1>
