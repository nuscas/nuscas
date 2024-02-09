<script>
    function goToSignUp() {
      // @ts-ignore
      window.open("https://linktr.ee/nuscas", '_blank').focus();
      document.title = "NUSCAS | About Us";
    }
  </script>
  
  <div class="bg-gray-100 min-h-screen py-8">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex flex-col items-center space-y-8">
  
        <img src="/logo.svg" alt="Logo" class="block w-64 h-auto" />
  
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src="/photo.jpg" alt="Photo" class="block rounded-lg shadow-xl w-full max-w-lg" />
  
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="space-y-4">
              <h1 class="text-3xl font-bold">About Us</h1>
              <p class="text-gray-700">
                We are a group of friends passionate about all sorts of Japanese Animation,
                Comics, Events and Games. From a small club founded in 1999, we now possess
                hundreds of members, a dedicated committee, robust alumni network and a 
                budding social media presence.
                <br><br>
                Here, you can find like-minded people of
                culture partaking in all sorts of exciting events and activities every week!
                Excited? Why not take a look at what our 3 Departments have to offer:
              </p>
            </div>
          
            <div class="space-y-4 text-right"> <!-- Added 'text-right' class for right alignment -->
              <h1 class="text-3xl font-bold">Schedule</h1>
              <p class="text-gray-700">Every Friday <br>6.30pm - 8.30pm</p>
              <div class="flex justify-end"> <!-- Added 'justify-end' class for right alignment -->
                <button class="px-4 py-2 bg-orange-500 text-white rounded hover:bg-orange-600" on:click={goToSignUp}>Sign Up</button>
              </div>
            </div>
          </div>
          
  
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-gray-800 rounded-lg p-6 text-white">
            <h1 class="text-2xl font-bold">CASuals</h1>
            <p>Foster a vibrant and entertaining community through activities such as cosplay.</p>
          </div>
  
          <div class="bg-gray-800 rounded-lg p-6 text-white">
            <h1 class="text-2xl font-bold">Topics</h1>
            <p>Explore the finer points in writing and storytelling, or, build our club website and social media presence.</p>
          </div>
  
          <div class="bg-gray-800 rounded-lg p-6 text-white">
            <h1 class="text-2xl font-bold">Palette</h1>
            <p>Nurture your artistic flair with lessons on art and graphic design. We are always proud of our artists who produce many breathtaking pieces.</p>
          </div>
        </div>
  
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div class="space-y-4">
            <h1 class="text-3xl font-bold">Contact Information</h1>
            <p class="text-gray-700">
              Address: Yusof Ishak House, Level 3 <br>
              31 Lower Kent Ridge Road <br>
              119078 <br>
              Contact Email: nuscomicssoc@gmail.com
            </p>
          </div>
  
          <div>
            <a href="https://www.instagram.com/nuscomicsoc/" target="_blank" rel="noopener noreferrer" class="block bg-pink-600 text-white px-4 py-2 rounded-md text-center font-semibold hover:bg-pink-700">
              <i class="fab fa-instagram"></i> Follow on Instagram
            </a>
          </div>
        </div>
        
      </div>
    </div>
  </div>
  