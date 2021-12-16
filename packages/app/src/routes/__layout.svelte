<script>
	import { Amplify } from 'aws-amplify';
	import amplifyConfig from 'aws-exports';
	Amplify.configure(amplifyConfig);
</script>

<slot />
