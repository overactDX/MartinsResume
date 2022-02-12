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
      a.text-sm.p-2.bg-black.text-white.text-center.rounded.font-bold(href="/test" class="hover:bg-black hover:text-gray-200") Another Information
      a.text-sm.p-2.bg-indigo-200.text-center.rounded.font-semibold(href="/test2" class="hover:bg-black hover:text-gray-200") Another Something

    .col-span-12.h-full.pb-12(class="md:border-solid md:border-l md:border-black md:border-opacity-25 md:col-span-10")
      .px-4.pt-4
        form.flex.flex-col.space-y-8(action="#")
            div
                h3.text-2xl.font-bold Another Information
                hr
            label.text-xl.font-semibold Experience

        .p-2.space-x-2
            span.inline-flex.bg-pink-600.text-white.rounded-full.h-6.px-3.justify-center.items-center 04-05/2021
            .inline-flex.items-center.bg-white.leading-none.text-pink-600.rounded-full.p-2.shadow.text-teal.text-sm
                span.inline-flex.bg-pink-600.text-white.rounded-full.h-6.px-3.justify-center.items-center OneDee Solution Co., Ltd.,
                span.inline-flex.px-2 Front-end Developer (Internship)

        .p-2.space-x-2
            span.inline-flex.bg-red-600.text-white.rounded-full.h-6.px-3.justify-center.items-center 03/2021
            .inline-flex.items-center.bg-white.leading-none.text-red-600.rounded-full.p-2.shadow.text-teal.text-sm
                span.inline-flex.bg-red-600.text-white.rounded-full.h-6.px-3.justify-center.items-center 20Scoops CNX Co., Ltd.,
                span.inline-flex.px-2 Hackathon Boot Camp (Attend)

        p.text-lg.font-bold Technical Skills

        div.grid.grid-cols-2
          div
              p.text-lg.font-semibold.pt-5.pl-12 Programming Languages
          div
              p.text-lg.font-semibold.pt-5.pl-12 Framework

        div.grid.grid-cols-2
          .pt-8.pl-20.space-y-6
            .flex.space-x-4
              img(src="https://cdn-icons-png.flaticon.com/512/136/136528.png" width="48px" height="48px")
              a.text-lg Html
            .flex.pt-2.space-x-4
              img(src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="48px" height="48px")
              a.text-lg JavaScrip
            .flex.pt-2.space-x-4
              img(src="https://cdn-icons-png.flaticon.com/512/5968/5968242.png" width="48px" height="48px")
              a.text-lg css
            .flex.pt-2.space-x-4
              img(src="https://cdn-icons.flaticon.com/png/512/3098/premium/3098090.png?token=exp=1644663343~hmac=13a9c2a5adc6538ffd373bbe49f6c317" width="48px" height="48px")
              a.text-lg Python
            .flex.pt-2.space-x-4
              img(src="https://cdn-icons.flaticon.com/png/512/5433/premium/5433712.png?token=exp=1644663370~hmac=9f07e504ef68f1af1d7b7fc4ba97b8e3" width="48px" height="48px")
              a.text-lg Java

          .pt-8.pl-20.space-y-6
            .flex.space-x-4
              img(src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRzAp6ZUXWH0sSEaRfs0NVrSa7KGD2BrUgZsgQBdpn0Q7DYiwLBQ5-ipHS2shWJO8eafQ8&usqp=CAU" width="48px" height="48px")
              a.text-lg Vue.Js
            .flex.pt-2.space-x-4
              img(src="https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FdyOFod%2FbtqB3WPfexr%2FRqvsyoHC2HGcFKTNQCgjc1%2Fimg.png" width="48px" height="48px")
              a.text-lg Nuxt.Js
            .flex.pt-2.space-x-4
              img(src="https://play-lh.googleusercontent.com/5e7z5YCt7fplN4qndpYzpJjYmuzM2WSrfs35KxnEw-Ku1sClHRWHoIDSw3a3YS5WpGcI" width="48px" height="48px")
              a.text-lg Flutter

        div.grid.grid-cols-2
          div.pt-10
              p.text-lg.font-semibold.pt-5.pl-12 Databescs
          div.pt-10
              p.text-lg.font-semibold.pt-5.pl-12 Tools
        div.grid.grid-cols-2
          .pt-8.pl-20.space-y-6
            .flex.space-x-4
              img(src="https://www.albaconsulting.it/sites/default/files/2017-03/mongodb.png" width="48px" height="48px")
              a.text-lg MongoDB
            .flex.pt-2.space-x-4
              img(src="https://zixzax.net/wp-content/uploads/2020/05/MySQL-%E0%B8%84%E0%B8%B7%E0%B8%AD%E0%B8%AD%E0%B8%B0%E0%B9%84%E0%B8%A3.png" width="48px" height="48px")
              a.text-lg MySQL
          .pt-8.pl-20.space-y-6
            .flex.space-x-4
              img(src="https://miro.medium.com/max/800/1*T2RAqkxxv4cJiveBBmGcfA.png" width="48px" height="48px")
              a.text-lg Figma
            .flex.pt-2.space-x-4
              img(src="https://sites.google.com/site/rfgnmipjnhiop/_/rsrc/1512027061571/3-1khwam-hmay-khxng-porkaerm-adobe-photoshop/Adobe_Photoshop_CS6_icon.svg.png?height=314&width=320" width="48px" height="48px")
              a.text-lg PhotoShop
            .flex.pt-2.space-x-4
              img(src="https://www.4x-treme.com/wp-content/uploads/2019/09/postman.png" width="48px" height="48px")
              a.text-lg Postman
        div.pt-10
            p.text-lg.font-semibold.pt-5.pl-12 Version Control
        div
          .pt-8.pl-20.space-y-6
            .flex.space-x-4
              img(src="https://pbs.twimg.com/profile_images/1414990564408262661/r6YemvF9_400x400.jpg" width="48px" height="48px")
              a.text-lg GitHub
            .flex.pt-2.space-x-4
              img(src="https://blog.pjjop.org/content/images/2020/04/gitlab.png" width="48px" height="48px")
              a.text-lg GitLab

</template>
