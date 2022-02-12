<template lang="pug">
.w-full.relative.mt-4.shadow-2xl.rounded.my-24.overflow-hidden
  .top.h-64.w-full.bg-blue-600.overflow-hidden.relative
    img.bg.w-full.h-full.object-cover.object-center.absolute.z-0(src="https://wallpaperaccess.com/full/1867142.jpg" alt="")
    .flex.flex-col.justify-center.relative.h-full.bg-black.bg-opacity-50.text-white.pl-6
      img.h-36.w-60.object-cover.rounded-lg.border-2(src="https://scontent.fbkk5-1.fna.fbcdn.net/v/t1.15752-9/259401406_410260017522388_1456658837909761865_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=ae9488&_nc_ohc=LvB6UeN7faMAX8EM-AL&_nc_ht=scontent.fbkk5-1.fna&oh=03_AVJNnOZo-mdMKSFBbjdOxeMjGDZQCDkjlfTgx0Kg8jrBmA&oe=622F2CD2")
      h1.text-2xl.font-bold-500.uppercase.pt-4.fo Verayutt Pakpume


  .grid.grid-cols-12.bg-white
    .col-span-12.w-full.px-3.py-6.justify-center.flex.space-x-4.border-b.border-solid(class="md:space-x-0 md:space-y-4 md:flex-col md:col-span-2 md:justify-start")
      nuxt-link.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(to="/" class="hover:bg-black hover:text-gray-200") Basic Information
      nuxt-link.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(to="/Information" class="hover:bg-black hover:text-gray-200") Another Information
      nuxt-link.text-sm.p-2.bg-black.text-white.text-center.rounded.font-bold(to="/Something" class="hover:bg-black hover:text-gray-200") Another Something

    .col-span-12.h-full.pb-12(class="md:border-solid md:border-l md:border-black md:border-opacity-25 md:col-span-10")
      .px-4.pt-4
        form.flex.flex-col.space-y-8(action="#")
            div
                h3.text-2xl.font-bold Another Something
                hr
            label.text-xl.font-semibold Project

        .grid.grid-cols-1.gap-2.max-w-6xl(class="xl:grid-cols-4 md:grid-cols-2")
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-fill.rounded-md(src="https://jattapol456.github.io/Portfolio/_nuxt/img/madoobaan.1dabffb.jpg" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Projects Madoobaan :
                      a.pl-3.text-red-700(href="https://gitlab.com/onedee/madoobaan-frontend") Link
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-fill.rounded-md(src="https://scontent.fbkk5-3.fna.fbcdn.net/v/t1.15752-9/273664836_964102737544091_562987527596445108_n.jpg?_nc_cat=105&ccb=1-5&_nc_sid=ae9488&_nc_ohc=Vwcg108wLdkAX_8Fmd6&_nc_ht=scontent.fbkk5-3.fna&oh=03_AVJQYLSQmQBmYNoEB6CiU9k7gahPZVxqllxX9BAzt59VRw&oe=622C2353" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Projects Library Website :
                      a.pl-3.text-red-700(href="https://gitlab.com/owutnr/jsbook") Link
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-fill.rounded-md(src="https://scontent.fbkk5-4.fna.fbcdn.net/v/t1.15752-9/272691381_686640869010869_7666844713785319937_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=ae9488&_nc_ohc=Raof2cXobfYAX8jF5-F&tn=KHdqdJKXO194LRMW&_nc_ht=scontent.fbkk5-4.fna&oh=03_AVJ2py_qYzagBTdvMxA1-ODDusEhUFGTWKaSZy_YjUpwVg&oe=622D236E" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Projects Movie-i App :
                      a.pl-3.text-red-700(href="https://gitlab.com/overact150/movie-i") Link
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-fill.rounded-md(src="https://scontent.fbkk5-1.fna.fbcdn.net/v/t1.15752-9/273751112_478358173742402_4562816550610345950_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=ae9488&_nc_ohc=M5M0SuAIEK4AX-bRnC0&_nc_ht=scontent.fbkk5-1.fna&oh=03_AVItK5wbKI1DRdNjSgeBou4yE9Zjk16HOSgY-MsRBszdoA&oe=622F9841" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Projects Pet Restaurant
        .grid.grid-cols-1.gap-2.max-w-6xl(class="xl:grid-cols-4 md:grid-cols-2")
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-fill.rounded-md(src="https://scontent.fbkk5-4.fna.fbcdn.net/v/t1.15752-9/272780387_369176741715645_7260600957291413887_n.jpg?_nc_cat=110&ccb=1-5&_nc_sid=ae9488&_nc_ohc=rV_Mjr3W_rEAX-4kClN&_nc_ht=scontent.fbkk5-4.fna&oh=03_AVJ1wW6ijfKKKHLIMrNfj0hUUaOFZZn61if3DLsKi_D2bg&oe=622DFF25" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Trained by OneDee.Solution
            .flex.flex-col.bg-gray-200.rounded-lg.p-4.m-2
                img.h-36.w-50.object-fill.rounded-md(src="https://scontent.fbkk5-4.fna.fbcdn.net/v/t1.15752-9/259283815_497400961997508_3300098881960112603_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=ae9488&_nc_ohc=9uwrG-lLzBoAX-AZOpw&_nc_ht=scontent.fbkk5-4.fna&oh=03_AVJqJSildxVoo0_UENdrMmDIQN3x05n-buQi6UeK8lYXbw&oe=622D5858" alt="")
                .flex.flex-col.items-start.mt-4
                    h4.text-.font-semibold Restaurant Website Project



</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Rammetto+One&family=Rowdies:wght@700&display=swap');

.fo {
  font-family: 'Rammetto One', cursive;
  font-size: 18px;
}
</style>
