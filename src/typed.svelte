<script lang="ts">
    import type {Props} from './props';

    export let something: Props['something'] = {};
    export let counter: Props['counter'] = 0;
</script>
{JSON.stringify(something)}
{counter}
