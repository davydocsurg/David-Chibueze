<template>
  <div id="proficiency" class="container jst-prof p-4 mt-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
      <h1 class="text-bold" v-scrollAnime>
        Profi<br class="break" /><span class="text-success">ciency</span>
      </h1>
      <div class="card bg-card col-md-12 col-lg-4 shadow-sm" v-scrollAnime>
        <span class="p-1">My areas of expertise...</span>
      </div>

      <!-- <div class="row"> -->
      <div class="col-lg-8 col-md-12 col-sm-12 col-xs-12 mt-4">
        <div class="" v-scrollAnime>
          <h5 class="text-success prof_head">Front-end Design</h5>
          <p class="lh-lg">
            I have extensive experience in developing web pages and single-page
            applications using a wide range of UI frameworks and libraries.
            These include popular options such as
            <code class="text-success">
              Bootstrap, Tailwind CSS, ReactJS, NextJS, VueJS, NuxtJS,
              VuetifyJS, ViteJS, and MaterialUI</code
            >. Leveraging my expertise in these tools, I am able to create
            highly responsive and visually appealing user interfaces that
            enhance the user experience and drive engagement.
          </p>
        </div>
        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Back-end Development</h5>
          <p class="lh-lg">
            I build scalable and secure web applications with robust and
            efficient APIs. My expertise lies in
            <code class="text-success">PHP</code>,
            <code class="text-success">Laravel</code>, and
            <code class="text-success">NodeJS</code>.
          </p>
        </div>
        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Database Development</h5>
          <p class="lh-lg font-monospace">
            I design and implement normalized relational database schemas using
            <code class="text-success">MySQL</code> and
            <code class="text-success">PostgreSQL</code>, ensuring data
            integrity, scalability, and efficiency. I also work with NoSQL
            databases such as <code class="text-success">MongoDB</code> for
            unstructured or flexible data storage requirements.
          </p>
        </div>

        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Full-Stack Integration</h5>
          <p class="lh-lg font-monospace">
            I excel at bridging front-end and back-end development, ensuring
            smooth communication between client-side interfaces and server-side
            logic. By leveraging
            <code class="text-success">RESTful APIs</code>,
            <code class="text-success">GraphQL</code>, and efficient state
            management libraries, I deliver cohesive full-stack solutions.
          </p>
        </div>

        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">DevOps & Deployment</h5>
          <p class="lh-lg font-monospace">
            I streamline deployment workflows and ensure robust CI/CD pipelines
            using tools like <code class="text-success">Docker</code>,
            <code class="text-success">Kubernetes</code>,
            <code class="text-success">Jenkins</code>, and
            <code class="text-success">GitHub Actions</code>. I also have
            experience with cloud platforms such as
            <code class="text-success">AWS</code>,
            <code class="text-success">Google Cloud</code>, and
            <code class="text-success">Heroku</code>.
          </p>
        </div>

        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">
            Version Control & Collaboration
          </h5>
          <p class="lh-lg font-monospace">
            I use <code class="text-success">Git</code> and
            <code class="text-success">GitHub</code> for version control and
            collaboration, ensuring seamless teamwork and efficient project
            management. I am also familiar with
            <code class="text-success">Jira</code> and
            <code class="text-success">Trello</code> for task tracking and
            management.
          </p>
        </div>

        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Other Tools & Technologies</h5>
          <p class="lh-lg font-monospace">
            I have experience with <code class="text-success">TypeScript</code>,
            <code class="text-success">JavaScript (ES6+)</code>,
            <code class="text-success">NGINX</code>,
            <code class="text-success">Webpack</code>, and
            <code class="text-success">Babel</code>, enhancing my ability to
            tailor solutions to meet diverse project requirements.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="css" scoped>
.text-bold {
  font-weight: 300;
  font-size: 3.5rem !important;
}

.prof_head {
  text-decoration: underline;
}

.break {
  display: none !important;
}

p {
  line-height: 30px !important;
  font-size: 19px !important;
}

@media screen and (max-width: 992px) {
  /* .jst-prof {
    text-align: center !important;
  } */

  .text-bold {
    font-weight: 400;
    font-size: 2.5rem !important;
    /* text-align: center !important; */
  }
}

@media screen and (max-width: 300px) {
  .break {
    display: block !important;
  }
}

/* animes */
.before-enter {
  opacity: 0;
  transform: translateX(-80px);
  transition: all 1.4s ease-out;
}

.enter {
  opacity: 1;
  transform: translateX(0px);
}
</style>
