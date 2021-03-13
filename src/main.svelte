<script lang="ts">
    import ManuallyTyped from './manually-typed.svelte';
    import Typed from './typed.svelte';
</script>
<ManuallyTyped something={{ value: 'something' }}/>
<ManuallyTyped counter={true}/>

<Typed something={{ value: 'something' }}/>
<Typed counter={true}/>
