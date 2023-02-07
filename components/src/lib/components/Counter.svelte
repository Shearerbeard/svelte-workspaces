<script lang="ts">
    export let initial: number;

    let count = initial;

    const increment = () => count++;
</script>

<div>
    <p>Your number is { count }</p>
    <button on:click={ increment }>Increment</button>
</div>