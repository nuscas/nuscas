<!-- LandingPage.svelte -->

<script lang="ts">
  // Define the component
  export let blogPosts: any[] = [
    {
      _id: 1,
      title: "Sample Blog Post 1",
      content: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla nec urna ut est mattis tincidunt."
    },
    {
      _id: 2,
      title: "Sample Blog Post 2",
      content: "Praesent vel lectus nec urna sodales laoreet. Fusce eget urna vel velit interdum tincidunt."
    },
    {
      _id: 3,
      title: "Sample Blog Post 3",
      content: "Vestibulum eget nisl nec turpis convallis vestibulum. Suspendisse sit amet tellus vitae justo iaculis vehicula."
    }
  ];
</script>

<main class="bg-gray-100 min-h-screen flex items-center justify-center">
  <div class="max-w-4xl mx-auto px-4">
    <h1 class="text-5xl font-bold text-center text-gray-800 mb-8">NUSCAS</h1>
    <!-- Display blog posts here -->
    <div class="grid grid-cols-1 gap-8">
      {#each blogPosts as post (post._id)}
        <div class="bg-white shadow-md p-6 rounded-lg">
          <h2 class="text-xl font-bold text-gray-800">{post.title}</h2>
          <p class="text-gray-600 mt-2">{post.content}</p>
        </div>
      {/each}
      <!-- Placeholder for blog posts -->
      {#if blogPosts.length === 0}
        <p class="text-gray-600 text-center">No blog posts found.</p>
      {/if}
    </div>
  </div>
</main>

<style>
  /* Add custom styles here */
</style>
