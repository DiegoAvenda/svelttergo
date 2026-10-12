<script >
	import { enhance } from '$app/forms';
</script>

<h1>Login</h1>
<form method="post" action="?/signInSocial" use:enhance>
	<input type="hidden" name="provider" value="google" />
	<input type="hidden" name="callbackURL" value="/better-auth" />
	<button class="bg-blue-600 text-white px-4 py-2 rounded-md hover:bg-blue-700 transition">Sign in with Google</button>
</form>
