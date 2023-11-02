<template>
  <!-- Header start -->

  <header ref="header" class="">
    <div class="container flex justify-between items-center py-1">
      <button @click="navToggler" class="flex lg:hidden">
        <Icon size="24px" name="bx:menu-alt-left" />
      </button>
      <a href="" class="brend">
        <img class="w-[150px] h-[36.068px]" src="~/assets/images/logo.svg" alt="logotip" />
      </a>
      <nav class="absolute hidden lg:flex lg:relative top-0 left-0 w-[100%] lg:w-auto bg-[#00000054] lg:bg-transparent">
        <ul class="flex gap-4 flex-col lg:flex-row w-[300px] h-[100vh] lg:h-auto lg:w-auto p-5 lg:p-0 bg-white">
          <li class="flex justify-end lg:hidden">
            <button @click="navToggler" class="bg-stone-200 rounded-md p-1 cursor-pointer hover:opacity-70">
              <Icon size="24px" name="carbon:close" />
            </button>
          </li>
          <li><a href="#" class="nav-a">О нас </a></li>
          <li><a href="#" class="nav-a">Edu Coozin </a></li>
          <li><a href="#" class="nav-a">Почему Coozin? </a></li>
          <li><a href="#" class="nav-a">Мероприятия </a></li>
        </ul>
      </nav>
      <div class="flex gap-1 btn-group">
        <a href="" class="btn bg-stone-200">uz</a>
        <a href="" class="hidden lg:inline btn bg-orange-500 text-white">Присоединиться</a>
      </div>
    </div>
  </header>

  <!-- header end -->

  <!-- Home start -->
  <section>
    <div class="container flex gap-y-12 gap-x-5 flex-wrap justify-center xl:justify-between">
      <div class="w-[100%] xl:max-w-[597px] min-h-[70vh] flex flex-col justify-around ">
        <div class="flex flex-col items-start justify-start gap-5">
          <h1 class="font-bold sm:text-4xl max-w-[597px] text-xl">Раскрой свой потенциал вместе с Coozin!</h1>
          <p class="text-stone-500">
            Универсальная платформа Coozin предоставляют множество возможностей
            для самозанятых женщин. На платформе можно продавать товары и услуги,
            а также учиться новым навыкам и развивать свой бизнес
          </p>
          <a href=""
            class="inline-block btn bg-orange-500 text-white w-[100%] sm:w-auto text-center sm:text-start">Присоединиться</a>
        </div>
        <div class="flex flex-wrap gap-5 justify-around md:justify-start mt-12">
          <b class="w-[100%]">Достижения</b>
          <div class="flex flex-col gap-3 max-w-[164px] text-center md:text-start">
            <h1 class="text-4xl font-bold">1K</h1>
            <p>женщин прошли обучение</p>
          </div>
          <div class="flex flex-col gap-3 max-w-[164px] text-center md:text-start">
            <h1 class="text-4xl font-bold">130K</h1>
            <p>присоединились в платформу</p>
          </div>
          <div class="flex flex-col gap-3 max-w-[164px] text-center md:text-start">
            <h1 class="text-4xl font-bold">1K</h1>
            <p>пользователей платформы</p>
          </div>
        </div>
      </div>
      <div class="-order-1 xl:order-1">
        <div class="flex flex-col justify-center items-center gap-7 max-w-[600px]">
          <div class="flex gap-7 flex-wrap">
            <img class="" src="~/assets/images/image-1.svg" alt="">
            <img class="" src="~/assets/images/image-2.svg" alt="">
          </div>
          <div class="flex gap-7 flex-wrap">
            <img src="~/assets/images/image-3.svg" alt="">
            <img src="~/assets/images/image-4.svg" alt="">
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Home end -->


  <!-- Best seller start -->
  <section>
    <div class="container flex flex-wrap justify-center xl:justify-between gap-6 mt-[30px]">
      <img class="" src="~/assets/images/selller.svg" alt="">
      <div class="max-w-[569.5px]">
        <h2 class="text-3xl font-bold">EDU COOZIN</h2>
        <p class="text-stone-500 mt-[20px]">Онлайн-академия Coozin предоставляет обучение и помощь в <br> развитии
          бизнеса.
        </p>
        <div class="flex flex-col gap-12 mt-12">
          <div class="">
            <h1 class="flex gap-2 justify-start items-center">
              <Icon size="54px" name="ph:check-fat-fill" />
              <b class="text-xl">Курсы и мастер-классы</b>
            </h1>
            <p class="text-stone-500">На платформе доступны онлайн-курсы и мастер-классы по различным темам, связанным с
              бизнесом, такими как
              управление продажами, маркетинг, финансы и другие.</p>
          </div>
          <div class="">
            <h1 class="flex gap-2 justify-start items-center">
              <Icon size="54px" name="ph:check-fat-fill" />
              <b class="text-xl">Курсы и мастер-классы</b>
            </h1>
            <p class="text-stone-500">На платформе доступны онлайн-курсы и мастер-классы по различным темам, связанным с
              бизнесом, такими как
              управление продажами, маркетинг, финансы и другие.</p>
          </div>
          <div class="">
            <h1 class="flex gap-2 justify-start items-center">
              <Icon size="54px" name="ph:check-fat-fill" />
              <b class="text-xl">Курсы и мастер-классы</b>
            </h1>
            <p class="text-stone-500">На платформе доступны онлайн-курсы и мастер-классы по различным темам, связанным с
              бизнесом, такими как
              управление продажами, маркетинг, финансы и другие.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Best seller end -->

  <!-- contact start -->
  <section>
    <div class="container flex flex-wrap items-center justify-center xl:justify-between gap-6 mt-[30px]">
      <div class="max-w-[659px]">
        <h1 class="font-bold text-xl sm:text-4xl max-w-[597px]">Готовы присоединиться и развиваться вместе с
          нами?</h1>
        <p class="text-stone-500 mt-8">Заполните форму, и мы свяжемся с вами!</p>
        <form class="flex flex-wrap gap-4 mt-8 " action="">
          <label class="w-[100%] sm:w-[45%]" for="">
            <p>Имя</p>
            <input class=" w-[100%] border-2 border-stone-200 rounded-md p-1" type="text" name="" id="">
          </label>
          <label class="w-[100%] sm:w-[45%]" for="">
            <p>Фамилия</p>
            <input class=" w-[100%] border-2 border-stone-200 rounded-md p-1" type="text" name="" id="">
          </label>
          <label class="w-[100%] sm:w-[45%]" for="">
            <p>Номер телефона</p>
            <input class=" w-[100%] border-2 border-stone-200 rounded-md p-1" placeholder="+998" type="text" name=""
              id="">
          </label>
          <label class="w-[100%] sm:w-[45%]" for="">
            <p>Направление</p>
            <select name="w-[100%] border-2 border-stone-200 rounded-md p-1" id="">
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
            </select>
          </label>
          <label class="w-[100%] sm:w-[45%]" for="">
            <p>Город</p>
            <select name="w-[100%] border-2 border-stone-200 rounded-md p-1" id="">
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
            </select>
          </label>
          <label class="w-[100%] sm:w-[45%]" for="">
            <p>Район</p>
            <select name="w-[100%] border-2 border-stone-200 rounded-md p-1" id="">
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
              <option class="w-[100%] border-2 border-stone-200 rounded-md p-1" value="">----------</option>
            </select>
          </label>

          <div class="flex justify-center w-[100%]">
            <a href="" class="btn w-[100%] sm:w-[345px] bg-orange-500 text-white text-center">Отправить</a>

          </div>
        </form>
      </div>
      <img class="" src="~/assets/images/seller.svg" alt="">
    </div>
  </section>
  <!-- contact end -->

  <!-- footer start -->
  <footer class="py-12">
    <div class="container flex flex-col justify-center items-center gap-12 py-10">
      <img src="~/assets/images/footer-logo.svg" alt="">
      <ul class="flex gap-4 flex-wrap">
        <li><a href="#" class="nav-a">О нас </a></li>
        <li><a href="#" class="nav-a">Edu Coozin </a></li>
        <li><a href="#" class="nav-a">Почему Coozin? </a></li>
        <li><a href="#" class="nav-a">Мероприятия </a></li>
      </ul>
      <ul class="flex gap-4 flex-wrap">
        <p>При поддержке </p>
        <img src="~/assets/images/cola.svg" alt="">
        <img src="~/assets/images/osce.svg" alt="">
      </ul>
      <div class="flex flex-wrap flex-col md:flex-row gap-12">
        <p>ПОДПИСЫВАЙТЕСЬ НА НАС</p>
        <img src="~/assets/images/line.svg" alt="">
        <div class="flex flex-wrap gap-12">
          <div class="flex justify-center items-center border-black border-2 rounded-full w-[35px] h-[35px]">
            <Icon size="24px" name="teenyicons:instagram-outline" />
          </div>
          <div class="flex justify-center items-center border-black border-2 rounded-full w-[35px] h-[35px]">
            <Icon size="24px" name="ph:facebook-logo-fill" />
          </div>
          <div class="flex justify-center items-center border-black border-2 rounded-full w-[35px] h-[35px]">
            <Icon size="24px" name="uil:youtube" />
          </div>
        </div>
      </div>
    </div>
  </footer>
  <!-- footer end -->
</template>


<script lang="js">
export default {
  data() {
    return {
    }
  },
  methods: {
    navToggler() {
      const header = this.$refs.header
      header.classList.toggle('active')
    }
  }
};
</script>
<style>
header.active nav {
  display: flex;
}
</style>
