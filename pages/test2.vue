<template lang="pug">
.w-full.relative.mt-4.shadow-2xl.rounded.my-24.overflow-hidden
  .top.h-64.w-full.bg-blue-600.overflow-hidden.relative
    img.bg.w-full.h-full.object-cover.object-center.absolute.z-0(src="https://wallpaperaccess.com/full/1867142.jpg" alt="")
    .flex.flex-col.justify-center.items-center.relative.h-full.bg-black.bg-opacity-50.text-white
      img.h-36.w-36.object-cover.rounded-md(src="https://scontent.fbkk5-7.fna.fbcdn.net/v/t1.6435-9/76751398_785168335238949_1226211805798334464_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=174925&_nc_eui2=AeGjaKM1dfR62xRgN_cemLNbx3cmh4pwtWbHdyaHinC1ZqbtXNKV_yj69Fu6QdN2KJ5uZE-p7NjMm9kMrBcMNQvH&_nc_ohc=GEsc-9xxoo4AX-bgqMn&_nc_ht=scontent.fbkk5-7.fna&oh=00_AT8rdCtkox5161d5EzZr72tDp1p-JDrH1nwBCsxy2P-IUQ&oe=622DEAB3")
      h1.text-2xl.font-semibold.uppercase.pt-4 Verayutt Pakpume

  .grid.grid-cols-12.bg-white
    .col-span-12.w-full.px-3.py-6.justify-center.flex.space-x-4.border-b.border-solid(class="md:space-x-0 md:space-y-4 md:flex-col md:col-span-2 md:justify-start")
      a.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(href="/" class="hover:bg-black hover:text-gray-200") Basic Information
      a.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(href="test" class="hover:bg-black hover:text-gray-200") Another Information
      a.text-sm.p-2.bg-black.text-white.text-center.rounded.font-bold(href="test2" class="hover:bg-black hover:text-gray-200") Another Something

    .col-span-12.h-full.pb-12(class="md:border-solid md:border-l md:border-black md:border-opacity-25 md:col-span-10")
      .px-4.pt-4
        form.flex.flex-col.space-y-8(action="#")
            div
                h3.text-2xl.font-bold Another Something
                hr
            label.text-xl.font-semibold Project

        .grid.grid-cols-1.gap-2.max-w-6xl(class="xl:grid-cols-4 md:grid-cols-2")
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-cover.rounded-md(src="https://jattapol456.github.io/Portfolio/_nuxt/img/madoobaan.1dabffb.jpg" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Projects Madoobaan
                      a.pl-3.text-red-700(href="https://gitlab.com/onedee/madoobaan-frontend") Link
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-cover.rounded-md(src="https://scontent.fbkk5-3.fna.fbcdn.net/v/t1.15752-9/273664836_964102737544091_562987527596445108_n.jpg?_nc_cat=105&ccb=1-5&_nc_sid=ae9488&_nc_ohc=Vwcg108wLdkAX_8Fmd6&_nc_ht=scontent.fbkk5-3.fna&oh=03_AVJQYLSQmQBmYNoEB6CiU9k7gahPZVxqllxX9BAzt59VRw&oe=622C2353" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Projects Library Website
                      a.pl-3.text-red-700(href="https://gitlab.com/owutnr/jsbook") Link
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-cover.rounded-md(src="https://scontent.fbkk5-4.fna.fbcdn.net/v/t1.15752-9/272691381_686640869010869_7666844713785319937_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=ae9488&_nc_ohc=Raof2cXobfYAX8jF5-F&tn=KHdqdJKXO194LRMW&_nc_ht=scontent.fbkk5-4.fna&oh=03_AVJ2py_qYzagBTdvMxA1-ODDusEhUFGTWKaSZy_YjUpwVg&oe=622D236E" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Projects Movie-i
                      a.pl-3.text-red-700(href="https://gitlab.com/overact150/movie-i") Link

</template>
