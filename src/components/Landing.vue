<template>
  <div style="scroll-behavior: smooth">
    <div class="bg-alles-bg h-screen bg-contain bg-no-repeat">
      <div id="home" class="w-full h-100px flex justify-center items-center pt-9">
        <a
          href="#home"
          class="text-blue-gray-600 text-sm font-medium px-10 hover:text-rose-500 transiton duration-500 ease-in-out"
          >HOME</a
        >
        <a
          href="#about"
          class="text-blue-gray-600 text-sm font-medium px-10 pr-16 hover:text-rose-500 transiton duration-500 ease-in-out"
          >ABOUT</a
        >

        <img
          src="../assets/logo.png"
          alt=""
          class="w-100px h-auto rounded-full antialiased sticky"
        />

        <a
          href=""
          class="text-blue-gray-600 text-sm font-medium px-10 pl-16 hover:text-rose-500 transiton duration-500 ease-in-out"
          >SKILLS</a
        >
        <a
          href=""
          class="text-blue-gray-600 text-sm font-medium px-10 hover:text-rose-500 transiton duration-500 ease-in-out"
          >CONTACT</a
        >
      </div>

      <div class="absolute text-blue-gray-600" style="left: 35vw; top: 25vh">
        <p class="text-base">HELLO!</p>
        <p class="font-bold text-6xl">I AM ALLAN OLIVEIRA</p>
        <p class="text-2xl">FULL STACK WEB DEVELOPER</p>
      </div>

      <div class="text-blue-gray-500 absolute" style="left: 42vw; top: 42vh">
        <a
          class="shadow-2xl"
          target="__blank"
          href="https://www.linkedin.com/in/alle-oliveira/"
          ><i
            style="font-size: 1.823vw"
            class="ri-linkedin-box-line text-transparent bg-clip-text bg-gradient-to-r from-blue-gray-500 to-blue-gray-500 hover:from-rose-500 hover:to-indigo-500"
          ></i
        ></a>
        <a target="__blank" href="https://www.facebook.com/allan.gui.7">
          <i
            style="font-size: 1.823vw; padding-left: 1.563vw; padding-right: 1.563vw"
            class="ri-facebook-circle-line text-transparent bg-clip-text bg-gradient-to-r from-blue-gray-500 to-blue-gray-500 hover:from-rose-500 hover:to-indigo-500"
          ></i
        ></a>
        <a target="__blank" href="https://www.instagram.com/allan.g.oliveira/">
          <i
            style="font-size: 1.823vw; padding-right: 1.563vw"
            class="ri-instagram-line text-transparent bg-clip-text bg-gradient-to-r from-blue-gray-500 to-blue-gray-500 hover:from-rose-500 hover:to-indigo-500"
          ></i
        ></a>
        <a target="__blank" href="https://twitter.com/Allan_alle">
          <i
            style="font-size: 1.823vw"
            class="ri-twitter-line text-transparent bg-clip-text bg-gradient-to-r from-blue-gray-500 to-blue-gray-500 hover:from-rose-500 hover:to-indigo-500"
          ></i
        ></a>
      </div>
    </div>
    <div id="about" class="bg-alles-bg-flipped h-screen bg-contain bg-no-repeat relative">
      <div class="w-full h-100px flex justify-center items-center">
        <a
          href="#home"
          class="text-white text-sm font-bold px-10 opacity-60 hover:opacity-100 transiton duration-500 ease-in-out"
          >HOME</a
        >
        <a
          href="#about"
          class="text-white text-sm font-bold px-10 pr-16 opacity-60 hover:opacity-100 transiton duration-500 ease-in-out"
          >ABOUT</a
        >

        <a
          href=""
          class="text-white text-sm font-bold px-10 pl-16 opacity-60 hover:opacity-100 transiton duration-500 ease-in-out"
          >SKILLS</a
        >
        <a
          href=""
          class="text-white text-sm font-bold px-10 opacity-60 hover:opacity-100 transiton duration-500 ease-in-out"
          >CONTACT</a
        >
      </div>

      <div class="text-blue-gray-600 flex justify-center items-center w-full h-full">
        <div class="w-3/12">
          <p class="text-sm pb-4">ABOUT ME</p>
          <p class="text-3xl font-bold pb-4">Full Stack Web Developer And Web Designer</p>
          <p class="text-sm pb-4">
            I am 22 years old and I studied 3 years of computer science at the State
            University of the Midwest and I have a huge love for IT and its areas. I
            intend to expand my knowledge to Desktop and Mobile Development.
          </p>

          <a
            href="../assets/curriculo.docx"
            class="px-4 py-2 border-2 border-rose-500 rounded-md text-rose-500 font-bold hover:border-transparent hover:text-white hover:bg-indigo-500 transition duration-500 ease-in-out"
            download="">DOWNLOAD CV</a
          >
        </div>
        <img
          src="../assets/alle.jpg"
          class="rounded-full absolute right-20"
          style="height: 50vh"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
import "remixicon/fonts/remixicon.css";
export default {
  name: "Landing",

  // data() {
  //   return {
  //     scroll: "",
  //   };
  // },

  // created() {
  //  this.scroll = window.addEventListener("scroll", this.handleScroll);
  // },
  // // unmounted() {
  // //   window.removeEventListener("scroll", this.handleScroll);
  // // },
  // methods: {
  //   handleScroll(event) {
  //     let header = document.getElementById("header");

  //     header.classList.add("shadow-lg");

  //     alert(event);
  //   },
  // },
};
</script>
