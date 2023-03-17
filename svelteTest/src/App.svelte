<script>
  import svelteLogo from "./assets/svelte.svg";
  import viteLogo from "/vite.svg";
  import Counter from "./lib/Counter.svelte";
  import displayPicture from "/dp.jpeg";
  import TailwindCss from "./TailwindCss.svelte";
</script>

<TailwindCss />

<main>
  <div class="navbar text-primary-content rounded-box space-x-1">
    <div class="hidden flex-none md:flex">
      <div class="dropdown">
        <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
        <div tabindex="0">
          <button
            aria-label="drawer component"
            class="btn btn-ghost mask mask-squircle btn-square focus:bg-base-content border-none focus:bg-opacity-50"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              class="inline-block h-6 w-6 stroke-current"
              ><path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16"
              /></svg
            ></button
          >
        </div>
        <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
        <div tabindex="0" class="dropdown-content py-2">
          <div
            class="card compact bg-neutral-focus text-neutral-content rounded-box w-72 shadow-xl"
          >
            <div class="card-body">
              <h2 class="card-title font-extrabold capitalize">
                drawer component
              </h2>
              <p class="text-neutral-content text-sm text-opacity-80">
                Drawer component is useful for opening a sidebar menu
              </p>
              <div class="mt-4 flex justify-end">
                <a
                  href="/components/drawer"
                  class="btn btn-primary btn-sm xl:btn-md">See component</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="mx-2 flex-1 justify-center px-2 md:flex md:justify-start">
      <span class="text-2xl font-bold">Raccoon UI</span>
    </div>
    <div class="hidden flex-1 md:flex md:flex-none">
      <div class="form-control">
        <div class="dropdown">
          <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
          <div tabindex="0">
            <input
              placeholder="Text Input"
              class="input input-ghost input-bordered text-primary-content placeholder-primary-content focus:text-primary-content rounded-full focus:bg-transparent"
            />
          </div>
          <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
          <div tabindex="0" class="dropdown-content py-2">
            <div
              class="card compact bg-neutral-focus text-neutral-content rounded-box w-72 shadow-xl"
            >
              <div class="card-body">
                <h2 class="card-title font-extrabold capitalize">
                  text input component
                </h2>
                <p class="text-neutral-content text-sm text-opacity-80">
                  Text input comes in various sizes and styles
                </p>
                <div class="mt-4 flex justify-end">
                  <a
                    href="/components/input"
                    class="btn btn-primary btn-sm xl:btn-md">See component</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="dropdown dropdown-left">
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <div tabindex="0">
        <button
          aria-label="button component"
          class="btn btn-ghost mask mask-squircle btn-square focus:bg-base-content hidden border-none focus:bg-opacity-50 md:flex"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            class="inline-block h-6 w-6 stroke-current"
            ><path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
            /></svg
          ></button
        >
      </div>
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <div tabindex="0" class="dropdown-content py-2">
        <div
          class="card compact bg-neutral-focus text-neutral-content rounded-box w-72 shadow-xl"
        >
          <div class="card-body">
            <h2 class="card-title font-extrabold capitalize">
              navbar component
            </h2>
            <p class="text-neutral-content text-sm text-opacity-80">
              You'll need a navbar on top of your page
            </p>
            <div class="mt-4 flex justify-end">
              <a
                href="/components/navbar"
                class="btn btn-primary btn-sm xl:btn-md">See component</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="dropdown dropdown-left">
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <div tabindex="0">
        <button
          aria-label="button component"
          class="btn btn-ghost mask mask-squircle btn-square focus:bg-base-content hidden border-none focus:bg-opacity-50 md:flex"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            class="inline-block h-6 w-6 stroke-current"
            ><path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
            /></svg
          ></button
        >
      </div>
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <div tabindex="0" class="dropdown-content py-2">
        <div
          class="card compact bg-neutral-focus text-neutral-content rounded-box w-72 shadow-xl"
        >
          <div class="card-body">
            <h2 class="card-title font-extrabold capitalize">
              navbar component
            </h2>
            <p class="text-neutral-content text-sm text-opacity-80">
              You'll need a navbar on top of your page
            </p>
            <div class="mt-4 flex justify-end">
              <a
                href="/components/navbar"
                class="btn btn-primary btn-sm xl:btn-md">See component</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="dropdown dropdown-left">
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <div tabindex="0">
        <button
          aria-label="navbar component"
          class="btn btn-ghost mask mask-squircle btn-square focus:bg-base-content hidden border-none focus:bg-opacity-50 md:flex"
          ><div class="avatar">
            <div class="mask mask-squircle h-10 w-10">
              <img
                src={displayPicture}
                alt="Avatar Tailwind CSS Component"
              />
            </div>
          </div></button
        >
      </div>
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <div tabindex="0" class="dropdown-content py-2">
        <div
          class="card compact bg-neutral-focus text-neutral-content rounded-box w-72 shadow-xl"
        >
          <div class="card-body">
            <h2 class="card-title font-extrabold capitalize">
              avatar component
            </h2>
            <p class="text-neutral-content text-sm text-opacity-80">
              Use avatar component with any size
            </p>
            <div class="mt-4 flex justify-end">
              <a
                href="/components/avatar"
                class="btn btn-primary btn-sm xl:btn-md">See component</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="card w-100 bg-base-100 shadow-xl image-full">
    <figure>
      <img
        src="https://hips.hearstapps.com/hmg-prod/images/2023-mclaren-artura-101-1655218102.jpg"
        alt="Amazing Car"
      />
    </figure>
    <div class="card-body">
      <h2 class="card-title justify-center text-2xl font-bold">Raccoon Is Now A Vite + Svelte</h2>
      <h2 class="flex justify-center text-1x2 font-bold">Developer</h2>

      <div class="flex justify-center">
        <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
          <img src={viteLogo} class="logo" alt="Vite Logo" />
        </a>
        <a href="https://svelte.dev" target="_blank" rel="noreferrer">
          <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
        </a>
      </div>

      <div class="card-actions justify-center">
        <button class="btn glass">Message Now</button>
      </div>

      <div class="stats shadow glass bg-opacity-0 mt-10 border border-sky-500">
  
        <div class="stat bg-opacity-0">
          <div class="stat-figure text-success">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-8 h-8 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path></svg>
          </div>
          <div class="stat-title">Total Likes</div>
          <div class="stat-value text-success">25.6K</div>
          <div class="stat-desc">21% more than last month</div>
        </div>
        
        <div class="stat">
          <div class="stat-figure text-success">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-8 h-8 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
          </div>
          <div class="stat-title">Page Views</div>
          <div class="stat-value text-success">2.6M</div>
          <div class="stat-desc">21% more than last month</div>
        </div>
        
        <div class="stat">
          <div class="stat-figure text-secondary">
            <div class="avatar online">
              <div class="w-16 rounded-full">
                <!-- svelte-ignore a11y-missing-attribute -->
                <img src={displayPicture} />
              </div>
            </div>
          </div>
          <div class="stat-value text-warning">86%</div>
          <div class="stat-warning">Tasks done</div>
          <div class="stat-desc text-danger">31 tasks remaining</div>
        </div>
        
      </div>            
            <h2 class="card-title justify-center text-2xl font-bold mt-5">Vite is Damn Fast :: But Raccoon Is Faster <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block text-warning  w-8 h-8 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg></h2>
    </div>
  </div>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a
      href="https://github.com/sveltejs/kit#readme"
      target="_blank"
      rel="noreferrer">SvelteKit</a
    >, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">Click on the Vite and Svelte logos to learn more</p>
</main>
