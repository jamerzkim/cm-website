<script>
    // Sample data for the team members
    let people = [
      {
        name: 'Alice Johnson',
        email: 'alice.johnson@example.com',
        imageUrl: 'https://via.placeholder.com/150?text=Alice+Johnson',
      },
      {
        name: 'Bob Smith',
        email: 'bob.smith@example.com',
        imageUrl: 'https://via.placeholder.com/150?text=Bob+Smith',
      },
      {
        name: 'Charlie Brown',
        email: 'charlie.brown@example.com',
        imageUrl: 'https://via.placeholder.com/150?text=Charlie+Brown',
      },
      {
        name: 'Diana Prince',
        email: 'diana.prince@example.com',
        imageUrl: 'https://via.placeholder.com/150?text=Diana+Prince',
      },
      {
        name: 'Edward Norton',
        email: 'edward.norton@example.com',
        imageUrl: 'https://via.placeholder.com/150?text=Edward+Norton',
      },
      {
        name: 'Fiona Green',
        email: 'fiona.green@example.com',
        imageUrl: 'https://via.placeholder.com/150?text=Fiona+Green',
      },
      {
        name: 'George Miller',
        email: 'george.miller@example.com',
        imageUrl: 'https://via.placeholder.com/150?text=George+Miller',
      },
    ];
  </script>
  
  <main class="p-6 bg-gray-50 min-h-screen py-16">
    <h1 class="text-3xl font-semibold text-gray-800 mb-6">Meet Our Team</h1>
    <ul role="list" class="divide-y divide-slate-300">
      {#each people as person}
        <li class="flex py-4 first:pt-0 last:pb-0">
          <img class="h-14 w-14 rounded-full" src="{person.imageUrl}" alt="{person.name}" />
          <div class="ml-4 overflow-hidden">
            <p class="text-lg font-medium text-gray-900">{person.name}</p>
            <p class="text-sm text-gray-600">{person.email}</p>
          </div>
        </li>
      {/each}
    </ul>
  </main>