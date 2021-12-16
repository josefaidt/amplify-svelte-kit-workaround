<script>
	import { Amplify } from '@aws-amplify/core';
	import amplifyConfig from 'aws-exports';
	Amplify.configure(amplifyConfig);
</script>

<slot />
