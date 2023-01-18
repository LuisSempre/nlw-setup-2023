<template>
  <div class="flex max-w-2xl items-center justify-between px-36 pb-16 mx-auto">
    <div class="flex flex-col">
      <TrackerHeaderColors />
      <span class="text-5xl font-extrabold">habits</span>
    </div>
    <button
      class="
        flex
        cursor-pointer
        items-center
        rounded-lg
        border border-violet-500
        px-5
        py-4
        font-semibold
      "
    >
      <IconPlus class="mr-3" />
      <span>New habit</span>
    </button>
  </div>
</template>