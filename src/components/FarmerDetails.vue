<template>
  <div class="flex flex-col gap-3 border bg-white shadow-lg m-6 p-6 rounded-md">
    <div class="flex items-center">
      <div class="grow text-emerald-700 text-lg font-medium">
        Farmer Details
      </div>
    </div>
    <div class="flex p-3">
      <div class="flex-none gap-4">
        <div class="bg-blue-50 p-2 rounded-lg gap-3">
          <img
            src="https://pngset.com/images/profile-icon-svg-free-download-from-pixlokcom-for-adult-sleeve-clothing-person-face-transparent-png-2884841.png"
            class="rotate-0 rounded-lg w-10"
          />
        </div>
      </div>
      <div class="flex-1 w-24">
        <h1 class="text-lg text-zinc-600 font-bold">Sunil Kumar</h1>
        <span class="text-base text-gray-500">Kanpur,Uttar Pradesh</span>
      </div>
      <div class="flex-1 w-24 ...">
        <h5 class="text-base text-gray-500">Area</h5>
        <h1 class="text-lg text-zinc-600 font-bold">1.37 Acres</h1>
      </div>
      <div class="flex-1 w-24 ...">
        <h5 class="text-base text-gray-500">Sowing date</h5>
        <h1 class="text-lg text-zinc-600 font-bold">3rd Oct 2021</h1>
      </div>
      <div class="flex-1 w-24 ...">
        <h5 class="text-base text-gray-500">Crops</h5>
        <h1 class="text-lg text-zinc-600 font-bold">Moong, Gehu</h1>
      </div>
    </div>
    <h1 class="text-zinc-400 font-semibold">Bought products</h1>

    <div class="flex flex-wrap align-bottom gap-3">
      <div
        class="py-8 px-6 max-w-sm bg-white rounded-md shadow-lg space-y-2 sm:py-2 sm:space-y-0 sm:space-x-2"
      >
        <img
          class="block mx-auto h-48"
          src="https://5.imimg.com/data5/ANDROID/Default/2021/12/IR/US/YR/5480705/product-jpeg-500x500.jpg"
          alt="City Face"
        />
        <p class="text-gray-500">HYB Okra NS7772</p>
        <p class="text-gray-400">
          255 Grams <span class="text-emerald-600 font-bold">&#x20b9;199</span>
        </p>
      </div>
      <div
        class="py-8 px-6 max-w-sm bg-white rounded-md shadow-lg space-y-2 sm:py-2 sm:space-y-0 sm:space-x-2"
      >
        <img
          class="block mx-auto h-48"
          src="https://cdn.shopify.com/s/files/1/0722/2059/products/Tomato-NS-4266_large.jpg?v=1632806192"
          alt="City Face"
        />
        <p class="text-gray-500">HYB Okra NS7772</p>
        <p class="text-gray-400">
          255 Grams <span class="text-emerald-600 font-bold">&#x20b9; 199</span>
        </p>
      </div>
      <div
        class="py-8 px-6 max-w-sm bg-white rounded-md shadow-lg space-y-2 sm:py-2 sm:space-y-0 sm:space-x-2"
      >
        <img
          class="block mx-auto h-48"
          src="http://5.imimg.com/data5/SELLER/Default/2022/2/HM/VZ/KH/97630159/f1-ankita-chilli-seeds-500x500.jpg"
          alt="City Face"
        />
        <p class="text-gray-500">HYB Okra NS7772</p>
        <p class="text-gray-400">
          255 Grams <span class="text-emerald-600 font-bold">&#x20b9; 199</span>
        </p>
      </div>
      <div class="pl-20">
        <img
          src="https://images-eu.ssl-images-amazon.com/images/I/51yDi3vwH9L._SX198_BO1,204,203,200_QL40_FMwebp_.jpg"
          class="p-1 bg-white border rounded max-w-sm"
          alt="..."
        />
      </div>
    </div>

    <div class="flex gap-3">
      <div class="w-1/2 bg-emerald-100 rounded-md text-center">
        <button type="button" class="text-emerald-400 p-2 font-bold">
          Close
        </button>
      </div>
      <div class="w-1/2 bg-green-600 rounded-md text-center">
        <button type="button" class="font-bold p-2 text-stone-100">
          Send Message
        </button>
      </div>
    </div>
  </div>
</template>
