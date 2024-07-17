<script>
  import Header from './components/Header.svelte';
  import Section from './components/Section.svelte';
</script>

<header>
  <Header />
</header>

<main class="font-sans bg-gray-100 text-gray-900 pt-16">
  <section class="py-8">
    <Section id="home" title="Home" content="Welcome to the homepage." />
    <Section id="about" title="About Bien Doan" content="Detailed information about Council Member Bien Doan..." />
    <Section id="roles" title="Roles and Responsibilities" content="Explanation of various roles and responsibilities in the council..." />
    <Section id="guide" title="How to Become a Council Member" content="Step-by-step guide on how to become a council member..." />
    <Section id="team" title="Meet the Team" content="Introduction to the team members..." />
    <Section id="contact" title="Contact" content="How to get in touch with us..." />
  </section>
</main>

<style>

</style>