<script>
    import Nav from "./lib/components/Nav.svelte";
    import UseFormula from "./lib/components/UseFormula.svelte";
    import FormulaInput from "./lib/components/FormulaInput.svelte";
</script>

<div class="h-full flex flex-col">
    <ul class="flex-1 p-4">
        <UseFormula />
    </ul>
    <Nav />
</div>

<FormulaInput />
