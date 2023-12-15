<script>
  import Section from './Section.svelte';
  import svg from './assets/svelte.svg'
</script>

<main>
  <img src={svg} alt="svelte_logo">

   <Section title="Menu of the day">
    <p slot="slot_section">Soup</p>
    <p>Rice</p>
    <p>Pizza</p>
    <p>salad</p>
    <p>tea</p>
   </Section>

   <Section title="coffees">
      <svelte:fragment slot="slot_section">
        <p>Coffe whit milk</p>
        <p>Cold coffe</p>
      </svelte:fragment>
   </Section>
</main>
  
