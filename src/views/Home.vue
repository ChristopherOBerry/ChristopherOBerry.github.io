<template>
  <div class="home bg-primary text-white">
    <div class="row my-4">
      <div class="col-12" style="height:10vh;">
        <h1 class="text-center">Christopher O'Berry</h1>
      </div>
      <div class="col-12 my-1" style="height:10vh;">
        <h5 class="text-center">Software Developer and Content Manager</h5>
      </div>
    </div>
    <div class="row rounded text-center">
      <div class="row d-flex justify-content-center">
        <div class="col-sm-6 bg-info border">
          <h1 class="align-self-center my-4">About Me</h1>
          <p class="align-self-center">
            I am a recent graduate of the 
            <a
              target="_blank"
              href="https://boisecodeworks.com/"
            >Boise CodeWorks</a> full-stack program for experience and certification on building full-stack web applications. Working with Javascript, HTML, CSS, Bootstrap, Node.js, Vue.js, C#, MySQL, MongoDB, Dapper, Postman, OOP, REST API Design, and Observer Pattern. During my time at CodeWorks, I have worked on several projects, both solo and collaboratively.
          </p>

          <p>
            At present, I am serving the role of Content Manager for
            <a
              target="_blank"
              href="http://www.quietspeculation.com"
            >QuietSpeculation.com</a> where I manage a team of authors, particpate in Marketing and Content Direction strategizing, and utilize WordPress with HTML5 to create and edit content pieces.
          </p>
        </div>
      </div>
    </div>

    <div class="row my-4">
      <div class="col-12 text-center">
        <button
          class="btn btn-info mx-auto border"
          type="button"
          data-toggle="collapse"
          data-target="#collapseExample"
          aria-expanded="false"
          aria-controls="collapseExample"
        >My Tools</button>
      </div>
      <div class="col-12 my-4">
        <skills class="collapse" id="collapseExample"></skills>
      </div>
    </div>
    <div class="row my-4">
      <div class="col-12 text-center">
        <experience id="xp"></experience>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

import Skills from "@/components/Skills";
import Experience from "@/components/Experience";

export default {
  name: "home",
  components: {
    Skills,
    Experience
  }
};
</script>

<style>
</style>

