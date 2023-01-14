<template>
  <section class="text text-center">
    <h1>Resume</h1>
    <div>
      <div class="education">
        <h2 class="text text-center">Education</h2>
        <div class="school text-center" v-for="school in schools" :key="school.id">
          <h3>{{ school.name }}</h3>
          <p>Highest Grade: {{ school.grade }}</p>
          <p>Year: {{ school.year }}</p>
        </div>
      </div>
    </div>
    <div>
  
  
      <div class="experience">
        <h2 class="text text-center">Experience</h2>
        <div class="job" v-for="job in jobs" :key="job.id">
          <h3>{{ job.company }} ({{ job.start }} to {{ job.end }})</h3>
          <p>{{ job.position }}</p>
        </div>
      </div>
    </div>
  
  
    <div>
      <div class="skills">
        <h2 class="text text-center">TECHNICAL SKILLS</h2>
        <ul>
          <li v-for="skill in skills" :key="skill.id" class="display-6 text text-center">
            <strong>{{ skill.name }}</strong>
            <div class="progress">
              <div :class="'progress-bar progress-bar-striped progress-bar-animated bg-' + skill.color"
                :aria-valuenow="skill.value"
                role="progressbar" aria-label="Animated striped example" aria-valuemin="0" aria-valuemax="100" :style="{width: skill.value + '%', height: '50px'}"></div>
            </div>
          </li>
        </ul>
      </div>
    </div>

  </section>
</template>

<script>
export default {
  data() {
    return {
      schools: [
        {
          name: "Windsor High School",
          grade: "Matric",
          year: "2018"
        },
        {
          name: "North-link College",
          grade: "National Certificate Plumbing N1-N2",
          year: "2020-2021"
        }
      ], 
      jobs: [
        {
          company: "Teleperformance",
          position: "Call center Agent",
          start: "2021",
          end: "2022"
        },
        {
          company: "Butlers Pizza",
          position: "Delivery Driver",
          start: "2018",
          end: "2021"
        },
        {
          company: "Bazinga",
          position: "Childminder",
          start: "2022",
          end: "current"
        }
      ], 
      skills: [
        {
          name: "HTML",
          value: 75,
          color: "info"
        },
        {
          name: "CSS",
          value: 55,
          color: "success"
        },
        {
          name: "Bootstrap",
          value: 80,
          color: "warning"
        }
      ]
    }
  }
}
</script>


<style>


.education {
  text-align: left;
}

.school {
  margin-top: 20px;
}
.skills {
  text-align: left;
}

.progress {
  margin: 10px 0;
}

.progress-bar {
  height: 20px;
}
</style>
