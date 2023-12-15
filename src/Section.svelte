<script>
    export let title
</script>

 <header>
    <slot name="slot_title"><h1>{title}</h1></slot>
 </header>

<section>
    <slot name="slot_section">
    <p>Mensaje por si no se pasa nada mi padre</p>
    </slot>
</section>
