<template lang="pug">
.w-full.relative.mt-4.shadow-2xl.rounded.my-24.overflow-hidden
  .top.h-64.w-full.bg-blue-600.overflow-hidden.relative
    img.bg.w-full.h-full.object-cover.object-center.absolute.z-0(src="https://wallpaperaccess.com/full/1867142.jpg" alt="")
    .flex.flex-col.justify-center.items-center.relative.h-full.bg-black.bg-opacity-50.text-white
      img.h-36.w-36.object-cover.rounded-md(src="https://scontent.fbkk5-7.fna.fbcdn.net/v/t1.6435-9/76751398_785168335238949_1226211805798334464_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=174925&_nc_ohc=GEsc-9xxoo4AX-bgqMn&_nc_ht=scontent.fbkk5-7.fna&oh=00_AT91KJEj_cDgphWu4XeeVAsxuMY81ykRV1wNEm4RRE6jsQ&oe=622DEAB3")
      h1.text-2xl.font-bold.uppercase.pt-4 Verayutt Pakpume

  .grid.grid-cols-12.bg-white
    .col-span-12.w-full.px-3.py-6.justify-center.flex.space-x-4.border-b.border-solid(class="md:space-x-0 md:space-y-4 md:flex-col md:col-span-2 md:justify-start")
      a.text-sm.p-2.bg-black.text-white.text-center.rounded.font-bold(href="/" class="hover:bg-black hover:text-gray-200") Basic Information
      a.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(href="test" class="hover:bg-black hover:text-gray-200") Another Information
      a.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(href="test2" class="hover:bg-black hover:text-gray-200") Another Something

    .col-span-12.h-full.pb-12(class="md:border-solid md:border-l md:border-black md:border-opacity-25 md:col-span-10")
      .px-4.pt-4
        form.flex.flex-col.space-y-8(action="#")
          div
            h3.text-2xl.font-bold Basic Information
            hr
          .form-item
            label.text-xl Full Name
            input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2(type="text" value="นาย วีรยุทธ ภาคภูมิ" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
          .flex.flex-col.space-y-4(class="md:space-y-0 md:flex-row md:space-x-4")
            .form-item.w-full
              label.text-xl Nickname
              input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(type="text" value="Jame" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
            .form-item.w-full
              label.text-xl Email
              input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(type="text" value="overact150@gmail.com" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
          div
            h3.text-2xl.font-semibold More About Me
            hr
          .form-item.w-full
            label.text-xl Biography
            textarea.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(cols="30" rows="10" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="") Hello my name is James, now I am looking for an internship place for me. to practice new skills and challenges
          div
            h3.text-2xl.font-semibold My Social Media
            hr
          .form-item
            label.text-xl Instagram
            input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(type="text" value="https://instagram.com/emj_______/" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
          .form-item
            label.text-xl Facebook
            input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2.text-opacity-25(type="text" value="https://facebook.com/pinkcooooo/" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
          .form-item
            label.text-xl Gitlab
            input.w-full.appearance-none.text-black.text-opacity-50.rounded.shadow.py-1.px-2.mr-2(type="text" value="https://gitlab.com/overact150" class="focus:outline-none focus:shadow-outline focus:border-blue-200" disabled="")
</template>
