<script lang="ts" generics="MyType">
    import type { Example } from "@repo/utility";

    interface Props {
        prop1: Example<MyType>;
    }
    let { prop1 }: Props = $props();
</script>

<p>Hello World</p>
