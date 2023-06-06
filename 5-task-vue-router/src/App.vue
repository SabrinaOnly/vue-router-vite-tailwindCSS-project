<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="relative isolate overflow-hidden bg-gray-900 py-24 sm:py-32">
  <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&crop=focalpoint&fp-y=.8&w=2830&h=1500&q=80&blend=111827&sat=-100&exp=15&blend-mode=multiply" alt="" class="absolute inset-0 -z-10 h-full w-full object-cover object-right md:object-center">
  <div class="hidden sm:absolute sm:-top-10 sm:right-1/2 sm:-z-10 sm:mr-10 sm:block sm:transform-gpu sm:blur-3xl" aria-hidden="true">
    <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
  </div>
  <div class="absolute -top-52 left-1/2 -z-10 -translate-x-1/2 transform-gpu blur-3xl sm:top-[-28rem] sm:ml-16 sm:translate-x-0 sm:transform-gpu" aria-hidden="true">
    <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
  </div>
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl lg:mx-0">
      <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Company Oyndasoz</h2>
      <p class="mt-6 text-lg leading-8 text-gray-300">Мы компания ИО - иновация ояндасоз являемся  национальной компанией по разработке инновационных продуктов в сфере логистики и танспорта </p>
    </div>
    <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
      <div class="grid grid-cols-1 gap-x-8 gap-y-6 text-base font-semibold leading-7 text-white sm:grid-cols-2 md:flex lg:gap-x-10">
        <a href="#">Посмотреть главных <span aria-hidden="true">&rarr;</span></a>
        <a href="#">Связаться с компанией<span aria-hidden="true">&rarr;</span></a>
        <a href="#">Что вы у нас найдете <span aria-hidden="true">&rarr;</span></a>
        <a href="#">Фотогаллерея <span aria-hidden="true">&rarr;</span></a>
      </div>
      <dl class="mt-16 grid grid-cols-1 gap-8 sm:mt-20 sm:grid-cols-2 lg:grid-cols-4">
        <div class="flex flex-col-reverse">
          <dt class="text-base leading-7 text-gray-300">Фронтенд и бекенд разрабов <br> вкоючая волонетеров </dt>
          <dd class="text-2xl font-bold leading-9 tracking-tight text-white">20+</dd>
        </div>
        <div class="flex flex-col-reverse">
          <dt class="text-base leading-7 text-gray-300">Вот уже 3 года наша компания процветает </dt>
          <dd class="text-2xl font-bold leading-9 tracking-tight text-white">+3</dd>
        </div>
        <div class="flex flex-col-reverse">
          <dt class="text-base leading-7 text-gray-300">Гибкий график работы </dt>
          <dd class="text-2xl font-bold leading-9 tracking-tight text-white">27/7</dd>
        </div>
        <div class="flex flex-col-reverse">
          <dt class="text-base leading-7 text-gray-300">Hamroh</dt>
          <dd class="text-2xl font-bold leading-9 tracking-tight text-white">TAXI GRAM</dd>
        </div>
      </dl>
    </div>
  </div>
</div>

<!-- section -->
<section class="relative isolate overflow-hidden bg-white px-6 py-24 sm:py-32 lg:px-8">
  <div class="absolute inset-0 -z-10 bg-[radial-gradient(45rem_50rem_at_top,theme(colors.indigo.100),white)] opacity-20"></div>
  <div class="absolute inset-y-0 right-1/2 -z-10 mr-16 w-[200%] origin-bottom-left skew-x-[-30deg] bg-white shadow-xl shadow-indigo-600/10 ring-1 ring-indigo-50 sm:mr-28 lg:mr-0 xl:mr-16 xl:origin-center"></div>
  <div class="mx-auto max-w-2xl lg:max-w-4xl">
    <img class="img rounded-b-full ml-12 mx-auto h-12" src="https://tailwindui.com/img/logos/workcation-logo-indigo-600.svg" alt="">
    <figure class="mt-10">
      <blockquote class="text-center text-xl font-semibold leading-8 text-gray-900 sm:text-2xl sm:leading-9">
        <p>Разрешите представить Рахмаджон Хакимов является нашим главнокоммандующим, а так же направляет нас на верный путь в свои 47 у него имеется огромный опыт и потенциал в сфере айти, Рахмаджон Хакимов владеет семи языками программирования...</p>
      </blockquote>
      <figcaption class="mt-10">
        <img class="hakimov" src="./assets/img/1.jpg" alt="">
        <div class="mt-4 flex items-center justify-center space-x-3 text-base">
          <div class="font-semibold text-gray-900">Rahmatjon Hakimov</div>
          <svg viewBox="0 0 2 2" width="3" height="3" aria-hidden="true" class="fill-gray-900">
            <circle cx="1" cy="1" r="1" />
          </svg>
          <div class="text-gray-600">Главнокомандующий</div>
        </div>
      </figcaption>
    </figure>
  </div>
</section>

<div class="bg-white py-24 sm:py-32">
  <div class="mx-auto grid max-w-7xl gap-x-8 gap-y-20 px-6 lg:px-8 xl:grid-cols-3">
    <div class="max-w-2xl">
      <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Встречайте наш дружный коллектив</h2>
      <p class="mt-6 text-lg leading-8 text-gray-600">Далер Дадочонов является одним из фронтедщиков нашей комманды  <br>  Музаффар Толибов является тимлидером нашей комманды <br> Кобил Абдурахманов волонтер  </p>
    </div>
    <ul role="list" class="grid gap-x-8 gap-y-12 sm:grid-cols-2 sm:gap-y-16 xl:col-span-2">
      <li>
        <div class="flex items-center gap-x-6">
          <img class=" img4 h-16 w-16 rounded-full" src="./assets/img/2.jpg" alt="">
          <div>
            <h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Daler Dadojonov</h3>
            <p class="text-sm font-semibold leading-6 text-indigo-600">Front-end developer</p>
          </div>
        </div>

        <div class="flex items-center gap-x-6">
          <img class="img4  h-16 w-16 rounded-full" src="./assets/img/3.jpg" alt="">
          <div>
            <h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Muzzafar Tolibov</h3>
            <p class="text-sm font-semibold leading-6 text-indigo-600">Front-end developer/Team leader</p>
          </div>
        </div>


        <div class="flex items-center gap-x-6">
          <img class=" h-16 w-16 rounded-full" src="./assets/img/4.jpg" alt="">
          <div>
            <h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Qobil Abddurahmanov</h3>
            <p class="text-sm font-semibold leading-6 text-indigo-600">Front-end developer</p>
          </div>
        </div>
      </li>

    
    
      <!-- More people... -->
    </ul>
  </div>
</div>
      <nav>
        <RouterLink class="more" to="/">Больше </RouterLink>
        <RouterLink class="veiw" to="/about">Откликнуться</RouterLink>
      </nav>

  <RouterView />
</template>

<style scoped>
.img { 
  border-radius: 50px;
  position: relative;
  left: 300px;
}
.hakimov {
  border-radius: 500px;
  margin-left: 100px;
}
.img4 {
  margin-bottom: 30px;
}
.veiw {
  font-weight: 900;
  font-size: 30px;
  margin-left: 900px;
}
.more {
  font-weight: 900;
  font-size: 30px;
  margin-left: 200px;
}
</style>
