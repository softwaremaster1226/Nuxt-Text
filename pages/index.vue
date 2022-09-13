<template >
  <div
    class="
      w-full
      h-screen
      flex flex-col
      bg-fixed bg- bg-no-repeat bg-center
      bg-[url('/Group_97.svg')]
      bg-cover
    "
  >
    <header class="w-full flex flex-col justify-center items-center">
      <nav class="w-full flex justify-between items-center max-w-7xl my-5">
        <div class="flex-grow flex justify-center">
          <a class="mx-5 text-white hover:text-gray-900 font-extrabold"
            >MISSION</a
          >
          <a class="mx-5 text-white hover:text-gray-900 font-extrabold"
            >SERVICES</a
          >
          <a class="mx-5 text-white hover:text-gray-900 font-extrabold"
            >PROJECTS</a
          >
        </div>
        <div>
          <img class="w-10 h-10" src="pngwing.png" alt="logo" />
        </div>
        <div class="flex-grow flex justify-center items-center">
          <a class="mx-5 text-white hover:text-gray-900 font-extrabold">TEAM</a>
          <a class="mx-5 text-white hover:text-gray-900 font-extrabold"
            >CARRERS</a
          >
          <button
            class="
              text-black
              font-bold
              bg-yellow-100
              py-1
              px-2
              rounded-sm
              tracking-widest
            "
          >
            GET IN TOUCH
          </button>
        </div>
      </nav>
      <div
        class="
          w-full
          max-w-7xl
          h-2px
          bg-gray-200
          relative
          flex
          justify-center
          items-center
        "
      >
        <div
          class="w-3 h-3 border-2 transform rotate-45 absolute -left-5 -top-1"
        ></div>
        <div
          class="
            w-3
            h-3
            border-r-2 border-t-2
            transform
            rotate-45
            absolute
            -left-3
            -top-1
          "
        ></div>
        <div class="w-32 h-2px bg-yellow-500 relative flex justify-center">
          <div
            class="
              w-3
              h-3
              border-2 border-yellow-500
              transform
              rotate-45
              absolute
              -top-1
              bg-gray-600
            "
          ></div>
        </div>
        <div
          class="
            w-3
            h-3
            border-l-2 border-b-2
            transform
            rotate-45
            absolute
            -right-3
            -top-1
          "
        ></div>
        <div
          class="w-3 h-3 border-2 transform rotate-45 absolute -right-5 -top-1"
        ></div>
      </div>
    </header>

    <div class="w-full flex-grow flex justify-center items-start">
      <div class="flex w-full max-w-7xl h-full flex-grow justify-between">
        <div class="space-y-4 mt-72">
          <img src="/Frame_1.svg" alt="social" />
        </div>
        <div class="w-full text-center flex-grow flex flex-col mt-40">
          <p class="text-gray-300 text-base font-bold tracking-wide">
            Capitalize On Low Hanging Fruit To Indentify A Ballpack Value Added
            Activity To Beta Test
          </p>
          <h2 class="text-white text-5xl mt-5 mb-40 font-bold tracking-widest">
            Bring to the
            <span class="font-bold text-yellow-100">table win</span> win a
            <br />
            <span class="font-bold text-yellow-100">strategies</span> to ensure
          </h2>
          <div class="w-full flex justify-center">
            <img src="cube.png" class="w-72" />
          </div>
          <div class="w-full flex justify-center flex-grow items-end pb-12">
            <img src="Union.svg" />
          </div>
        </div>
        <div class="space-y-4 mt-72">
          <div class="w-4 h-4 bg-gray-600 transform rotate-45"></div>
          <div
            class="
              w-4
              h-4
              border border-yellow-100
              rounded-sm
              transform
              rotate-45
            "
          ></div>
          <div
            class="
              w-4
              h-4
              border border-yellow-100
              rounded-sm
              transform
              rotate-45
            "
          ></div>
          <div
            class="
              w-4
              h-4
              border border-yellow-100
              rounded-sm
              transform
              rotate-45
            "
          ></div>
          <div
            class="
              w-4
              h-4
              border border-yellow-100
              rounded-sm
              transform
              rotate-45
            "
          ></div>
          <div
            class="
              w-4
              h-4
              border border-yellow-100
              rounded-sm
              transform
              rotate-45
            "
          ></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
