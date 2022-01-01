<template>
  <div class="flex bg-light-gray h-screen" role="main">
    <div class="m-auto rounded-xl max-w-screen-sm p-8 sm:p-0">
      <div class="shadow-lg">
        <div class="rounded-t-lg sm:p-10 p-6 bg-white">
          <h1 class="text-cyan font-bold tracking-tight text-2xl">
            Join our community
          </h1>
          <h2
            class="pt-4 pb-2 text-bright-yellow font-bold text-lg tracking-tight"
          >
            30-day, hassle-free money back guarantee
          </h2>
          <p class="text-grayish-blue text-base">
            Gain access to our full library of tutorials along with expert code
            reviews. <br />
            Perfect for any developers who are serious about honing their
            skills.
          </p>
        </div>
        <div class="grid sm:grid-cols-2 grid-cols-1">
          <div class="sm:p-10 p-6 bg-cyan sm:rounded-bl-lg">
            <h2 class="text-white text-lg mb-4">Monthly Subscription</h2>
            <div class="inline-flex mb-2">
              <div class="text-white text-3xl font-bold mr-3">$29</div>
              <div class="text-light-gray my-auto opacity-50">per month</div>
            </div>
            <p class="text-light-gray mb-3">
              Full access for less than &dollar;1 a day
            </p>
            <button
              class="w-full shadow-lg mt-4 bg-bright-yellow text-white py-3 rounded-md"
            >
              Sign Up
            </button>
          </div>
          <div
            class="sm:p-10 p-6 bg-lighter-cyan sm:rounded-br-lg sm:rounded-b-none rounded-b-lg"
          >
            <h2 class="text-white text-lg mb-4">Why Us</h2>
            <p class="text-sm text-light-gray opacity-75">
              Tutorials by industry experts <br />
              Peer &amp; expert code review <br />
              Coding exercises <br />
              Access to our GitHub repos <br />
              Community forum <br />
              Flashcard decks <br />
              New videos every week <br />
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css?family=Karla:400,700");

#app {
  font-family: "Karla", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
