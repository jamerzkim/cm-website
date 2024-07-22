<script>
  let menuItems = [
    { label: 'Home', link: '/' },
    { label: 'About', link: '/about' },
    { label: 'Guide', link: '/guide' },
    { label: 'Team', link: '/team' },
    { label: 'Contact', link: '/contact' }
  ];
</script>

<nav class="fixed top-0 left-0 right-0 bg-gray-800 bg-opacity-80 backdrop-blur-sm text-white p-4 z-50">
  <ul class="flex justify-center space-x-6">
    {#each menuItems as item}
      <li class="hover:underline">
        <a href="{item.link}">{item.label}</a>
      </li>
    {/each}
  </ul>
</nav>