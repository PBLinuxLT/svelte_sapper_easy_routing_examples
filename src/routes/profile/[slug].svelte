<script context="module">
    let userName ='unknown';
    let queryString = {};
	export async function preload({ params, query }) {
        console.log({'params':params, 'qs':query});
        userName = params.slug;
        if(query) {
            queryString = JSON.stringify(query)
        }
        
    }
    
</script>
<h1>Single User Profile Page ([slug].svelte)</h1>
UserName: {userName}<br>
Query Strings {queryString}