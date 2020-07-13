


<template>



  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Portfolio
      </h1>

 <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="lg:text-center">
      <p class="text-base leading-6 text-indigo-600 font-semibold tracking-wide uppercase"></p>
      <h3 class="mt-2 text-2xl leading-8 font-extrabold tracking-tight text-green-500 sm:text-4xl sm:leading-10">
       Hi there,


      </h3>
      <p class="mt-4 max-w-2xl text-xl leading-7 text-gray-500 lg:mx-auto">
       I’m HELMAR, a self-taught Front End Webdeveloper who is addicted to learning new web techniques and loves open source.</p>
       <p class="mt-4 max-w-2xl text-xl leading-7 text-gray-500 lg:mx-auto">I live by the motto</p>

      <ul class="mt-3 max-w-3xl text-xl leading-7 text-green-900 lg:mx-auto">
        <li>Learn</li>
        <li>Built</li>
        <li>Deploy</li>
      </ul>


      </p>
    </div>
    </div>


      <div class="links">
        <a
          href="portfolio/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          check it out
        </a>



      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0.5rem;
  min-height: 20vh;
  max-height: 70vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}


.li {
   font-family: arial;
   font-size: 1rem;



}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
