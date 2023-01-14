<template>
    <div>
      <section id="projects">
        <h2 class="display-2 m-auto">Projects</h2>
        <div class="container">
          <div class="row">
            <div class="col-4" v-for="project in projects" :key="project.id">
              <div class="card mx-auto" style="width: 18rem;">
                <img :src="project.image" class="card-img-top" alt="project image">
                <div class="card-body">
                  <h5 class="card-title text-center">{{ project.name }}</h5>
                  <div class="text-center">
                    <a :href="project.github" target="blank">GitHub</a>
                    <a :href="project.netlify" target="blank">Netlify</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        projects: [
          {
            name: "Portfolio",
            image: "https://i.postimg.cc/1zc27LLK/8e7a31e9d4a2df84bc7599151b08436c.gif",
            github: "https://github.com/Reece1109/Reece-sPortfolio.git",
            netlify: "https://dashing-bublanina-080d8c.netlify.app"
        },
        
        {
            name: "Ecommerce Website",
        image: "https://i.postimg.cc/1zc27LLK/8e7a31e9d4a2df84bc7599151b08436c.gif",
        github: "https://github.com/Reece1109/EcommerceWebsite.git",
        netlify: "https://iridescent-bunny-c9b063.netlify.app"
    },
    
    {
        name: "My flipcard",
    image: "https://i.postimg.cc/1zc27LLK/8e7a31e9d4a2df84bc7599151b08436c.gif",
    github: "https://github.com/Reece1109/myflipcard.git",
    netlify: "https://gregarious-swan-125dad.netlify.app"
}
]
}
}
  }
</script>
  