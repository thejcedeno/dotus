<svelte:head>
  <script async defer src="https://buttons.github.io/buttons.js"></script>
</svelte:head>

<div
  class="h-screen bg-gradient-to-b from-gray-900 to-slate-800 flex flex-col text-white"
>
  <header class="py-16">
    <h1 class="text-4xl font-bold text-center mb-1">JCEDENO.US 😂</h1>
  </header>

  <body>
    <p class="text-center mb-6 text-neutral-300">
      The, soon to be, best website in the world 🌎.
    </p>
    <div class="flex flex-row justify-center items-center gap-4 mb-4">
      <!---TODO Add branding socials. -->
      <ul
        class="menu bg-base-100 w-56 p-2 rounded-box flex justify-center items-center"
      >
        <li>
          <a
            href="https://jcedeno.us/twitch"
            target="_blank"
            class="font-bold text-twitch"
          >
            <div class="text-twitch">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-twitch"
                viewBox="0 0 16 16"
              >
                <path
                  d="M3.857 0 1 2.857v10.286h3.429V16l2.857-2.857H9.57L14.714 8V0H3.857zm9.714 7.429-2.285 2.285H9l-2 2v-2H4.429V1.143h9.142v6.286z"
                />
                <path
                  d="M11.857 3.143h-1.143V6.57h1.143V3.143zm-3.143 0H7.571V6.57h1.143V3.143z"
                />
              </svg>
            </div>
            realjcedeno</a
          >
        </li>
        <!-- Twitch logo svg. TODO Pull out out here to external asset. -->

        <li>
          <!-- Twitter logo svg. TODO Pull out out here to external asset. -->
          <a
            href="https://jcedeno.us/twitter"
            target="_blank"
            class="text-twitter font-bold"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="18"
              height="18"
              viewBox="0 0 24 24"
              class="fill-current"
              ><path
                d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"
              /></svg
            >
            thejcedeno
          </a>
        </li>

        <li>
          <a
            href="https://www.youtube.com/@thejcedeno"
            target="_blank"
            class="font-bold text-youtube"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="fill-current"
              ><path
                d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"
              /></svg
            >
            jcedeno
          </a>
        </li>
      </ul>
    </div>

    <div class="w-screen h-fit flex items-center justify-center">
      <div
        class="flex h-full sm:flex-row w-screen flex-col items-center justify-center gap-5 text-white m-5 font-mono"
      >
        <div class="h-fit w-[90%] rounded-b-lg bg-slate-700">
          <img
            class="h-[80%] w-full object-cover"
            src="https://pbs.twimg.com/profile_banners/805640604583686144/1501192280/1500x500"
          />
          <div class="flex flex-col p-5">
            <div
              class="flex items-center justify-between w-full border-b-[1px] border-gray-500 pb-5"
            >
              <h1 class="font-bold text-2xl">Noobsters</h1>
              <button class="rounded bg-violet-400 p-2">Press me</button>
            </div>
            <p class="font-semibold text-gray-300 mt-5">
              NoobstersMC is a Minecraft Network that has successfully
              cultivated a dedicated and engaged player base, peaking at 16K
              followers. This achievement speaks to the brand's strong appeal
              and popularity within the Minecraft community.
            </p>
            <br>
            <br>
          </div>
        </div>
        <div class="h-fit w-[90%] rounded-b-lg bg-slate-700">
          <img
            class="h-[80%] w-full object-cover"
            src="https://pbs.twimg.com/profile_banners/805640604583686144/1501192280/1500x500"
          />
          <div class="flex flex-col p-5">
            <div
              class="flex items-center justify-between w-full border-b-[1px] border-gray-500 pb-5"
            >
              <h1 class="font-bold text-2xl">Noobsters</h1>
              <button class="rounded bg-violet-400 p-2">Press me</button>
            </div>
            <p class="font-semibold text-gray-300 mt-5">
              NoobstersMC's ongoing commitment to providing quality content and
              fostering a positive and supportive community has driven its
              success and attracted new players to its network. The brand
              leverages its following to expand its reach and influence within
              the community, promoting new updates and features and
              collaborating with other content creators to further grow its
              audience.
            </p>
          </div>
        </div>
        <div class="h-fit w-[90%] rounded-b-lg bg-slate-700">
          <img
            class="h-[80%] w-full object-cover"
            src="https://pbs.twimg.com/profile_banners/805640604583686144/1501192280/1500x500"
          />
          <div class="flex flex-col p-5">
            <div
              class="flex items-center justify-between w-full border-b-[1px] border-gray-500 pb-5"
            >
              <h1 class="font-bold text-2xl">Noobsters</h1>
              <button class="rounded bg-violet-400 p-2">Press me</button>
            </div>
            <p class="font-semibold text-gray-300 mt-5">
              Large descriptionNoobstersMC has always been at the forefront of
              technology within the Minecraft community, developing innovative
              tech solutions to enhance the gameplay experience for its players.
              The brand has implemented custom-built server infrastructure
              designed to handle high traffic and ensure a seamless gameplay
              experience.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="flex flex-col justify-center items-center gap-4 mt-12 mb-1">
      <!-- The button to open modal -->
      <label for="my-modal-4" class="btn">don't push the button</label>

      <!-- Put this part before </body> tag -->
      <input type="checkbox" id="my-modal-4" class="modal-toggle" />
      <label for="my-modal-4" class="modal cursor-pointer">
        <label class="modal-box relative" for="">
          <h3 class="text-lg font-bold">
            Congratulations random Internet user!
          </h3>
          <p class="py-4">
            uwu, you found a secret button. I'm proud of you. You're a good. I
            luv you, xoxo ❤
          </p>
        </label>
      </label>
    </div>
  </body>

  <footer
    class="footer flex-grow footer-center p-10 bg-base-200 text-base-content rounded"
  >
    <div class="grid grid-flow-col gap-4">
      <a class="link link-hover" href="https://jcedeno.us/realjcedeno"
        >About me</a
      >
      <a
        class="link link-hover"
        href="https://www.linkedin.com/in/realjcedeno"
        target="_blank">Work with me</a
      >
      <a class="link link-hover" href="mailto:jcedeno@panicsoda.com">Contact</a>
    </div>
    <div>
      <p>Copyright © 2023 - All rights reserved by Hynix LLC.</p>
    </div>
  </footer>
</div>
