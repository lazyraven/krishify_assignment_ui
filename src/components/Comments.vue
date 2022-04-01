<template>
  <h1>Comments</h1>

  <div
    class="flex flex-col gap-10 border bg-white shadow-lg m-6 p-6 rounded-md"
  >
    <!-- comment header starts -->
    <div class="flex gap-4 items-center">
      <div class="flex-none w-14">
        <button type="button" class="bg-emerald-100 p-2 rounded-lg">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-8 w-8 text-emerald-700"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M11 17l-5-5m0 0l5-5m-5 5h12"
            />
          </svg>
        </button>
      </div>
      <div class="grow text-emerald-700 text-lg font-medium">Comments</div>
    </div>
    <!-- comment header ends -->

    <div class="flex flex-col gap-6">
      <div class="flex gap-2">
        <div class="flex-none w-14 h-14">
          <button type="button" class="rounded-lg">
            <img
              src="https://pngset.com/images/profile-icon-svg-free-download-from-pixlokcom-for-adult-sleeve-clothing-person-face-transparent-png-2884841.png"
              class="rotate-0 rounded-lg w-10"
            />
          </button>
        </div>
        <div class="grow">
          <div class="flex flex-col gap-1">
            <div class="flex">
              <div class="grow">
                <h6 class="text-base">Shashawank Sharma</h6>
              </div>
              <div class="flex-none w-14 text-sm text-slate-600">2d ago</div>
            </div>
            <p class="text-sm">
              Mere crops mein keede padh rahe, kya karein ? Mere crops mein
              keede padh rahe, kya karein ?
            </p>
            <span class="text-xs text-emerald-700 font-medium">1 Reply</span>
          </div>
        </div>
      </div>

      <div class="flex gap-2">
        <div class="flex-none w-14 h-14">
          <button type="button" class="bg-emerald-100 p-2 rounded-lg">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-6 text-emerald-700"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M11 17l-5-5m0 0l5-5m-5 5h12"
              />
            </svg>
          </button>
        </div>
        <div class="grow">
          <div class="flex flex-col gap-1">
            <div class="flex">
              <div class="grow">
                <h6 class="text-base">Vinayak Desai</h6>
              </div>
              <div class="flex-none w-14 text-sm text-slate-600">2d ago</div>
            </div>
            <p class="text-sm">
              Mere crops mein keede padh rahe, kya karein ? Mere crops mein
              keede padh rahe, kya karein ?
            </p>
            <span class="text-xs text-emerald-700 font-medium">1 Reply</span>
          </div>
        </div>
      </div>
      <div class="flex gap-2">
        <div class="flex-none w-14 h-14">
          <!-- <div class="p-3"> -->
          <button type="button" class="bg-emerald-100 p-2 rounded-lg">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-6 text-emerald-700"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M11 17l-5-5m0 0l5-5m-5 5h12"
              />
            </svg>
          </button>
          <!-- </div> -->
        </div>
        <div class="grow">
          <div class="flex flex-col gap-1">
            <div class="flex">
              <div class="grow">
                <h6 class="text-base">Shashawank Sharma</h6>
              </div>
              <div class="flex-none w-14 text-sm text-slate-600">2d ago</div>
            </div>
            <p class="text-sm">
              Mere crops mein keede padh rahe, kya karein ? Mere crops mein
              keede padh rahe, kya karein ?
            </p>
            <span class="text-xs text-emerald-700 font-medium">1 Reply</span>
          </div>
        </div>
      </div>
      <div class="flex gap-2">
        <div class="flex-none w-14 h-14">
          <!-- <div class="p-3"> -->
          <button type="button" class="bg-emerald-100 p-2 rounded-lg">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-6 text-emerald-700"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M11 17l-5-5m0 0l5-5m-5 5h12"
              />
            </svg>
          </button>
          <!-- </div> -->
        </div>
        <div class="grow">
          <div class="flex flex-col gap-1">
            <div class="flex">
              <div class="grow">
                <h6 class="text-base">Vinayak Desai</h6>
              </div>
              <div class="flex-none w-14 text-sm text-slate-600">2d ago</div>
            </div>
            <p class="text-sm">
              Mere crops mein keede padh rahe, kya karein ? Mere crops mein
              keede padh rahe, kya karein ?
            </p>
            <span class="text-xs text-emerald-700 font-medium">1 Reply</span>
          </div>
        </div>
      </div>
    </div>
    <form>
      <label class="relative block">
        <input
          type="text"
          value="Add a comment.."
          disabled
          class="mt-1 block w-full px-3 py-2 bg-white border-slate-300 rounded-md text-sm shadow-sm placeholder-slate-400 focus:outline-none focus:border-sky-500 focus:ring-1 focus:ring-sky-500 disabled:bg-slate-50 disabled:text-slate-400 disabled:border-slate-200 disabled:shadow-none invalid:border-pink-500 invalid:text-pink-600 focus:invalid:border-pink-500 focus:invalid:ring-pink-500 h-14"
        />
        <span
          class="absolute inset-y-0 right-0 flex items-center pl-2 text-slate-400 px-3"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 rotate-45"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"
            />
          </svg>
        </span>
      </label>
    </form>
  </div>
</template>
