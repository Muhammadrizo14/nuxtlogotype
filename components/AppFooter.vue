<template>
  <footer class="bg-brand-dark py-6 text-white hidden lg:block">
    <div class="container">
      <div class="nav flex items-start justify-between border-b-brand-blue border-b-2 pb-6">
        <img class="w-[186.73px] self-center" src="../public/img/about.png" alt="logo">
        <div>
          <h3 class="text-xl pb-3">НАВИГАЦИЯ</h3>
          <ul>
            <li>
              <NuxtLink href="/" class="text-xl font-medium hover:underline hover:text-brand-blue">Главная</NuxtLink>
            </li>
            <li>
              <NuxtLink href="/catalog" class="text-xl font-medium hover:underline hover:text-brand-blue">Каталог</NuxtLink>
            </li>
            <li>
              <NuxtLink href="/" class="text-xl font-medium hover:underline hover:text-brand-blue">Новости</NuxtLink>
            </li>
            <li>
              <NuxtLink href="/" class="text-xl font-medium hover:underline hover:text-brand-blue">О сервисе</NuxtLink>
            </li>
            <li>
              <NuxtLink href="/" class="text-xl font-medium hover:underline hover:text-brand-blue">Контакты</NuxtLink>
            </li>

          </ul>
        </div>
        <div>
          <h2 class="text-xl pb-3">ИНФОРМАЦИЯ</h2>
          <ul>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Политика Cookie-файлов</a>
            </li>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Пользовательское соглашение</a>
            </li>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Ценовая политика</a>
            </li>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Политика закрытой базы</a>
            </li>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Политика конфиденциальности</a>
            </li>
          </ul>
        </div>
        <div>
          <h2 class="text-xl pb-3">НАШИ КАНАЛЫ</h2>
          <ul>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Телеграм-бот</a>
            </li>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Телеграм-канал</a>
            </li>
            <li>
              <a  class="text-xl font-medium hover:underline hover:text-brand-blue" href="#">Закрытое сообщество</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="pt-3 flex justify-between pt-6">
        <div>
          <p  class="font-medium text-lg">Портал для поиска коммерческой недвижимости</p>
          <div class="flex items-center gap-3">
            <h2><span>ARENDA</span><span class="text-brand-green">BC</span></h2>
            <p class="text-sm">2016-2024</p>
          </div>
        </div>
        <div class="flex items-center gap-2">
          <div class="text-right">
            <p  class="font-medium text-lg">Сайт разработала и обслуживает веб-студия</p>
            <a  class="font-extrabold" href="#">CYBERMINE.STUDIO</a>
          </div>
          <img src="../public/img/cybermine.png" alt="">
        </div>
      </div>
    </div>
  </footer>
</template>