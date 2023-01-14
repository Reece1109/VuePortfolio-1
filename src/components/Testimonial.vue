<template>
    <section id="testimonials d-flex justify-content-center mx-auto">
        <h1 class="m-auto">Testimonials</h1>
            <div class="row ">
                <div v-for="testimonial in testimonials" :key="testimonial.id" class="col-lg-4 px-0 col-12 ">
                <div class="card mx-auto" style="width: 18rem;">
                    <img :src="testimonial.image" class="card-img-top" alt="...">
                    <div class="card-body">
                <h5 class="card-title">{{ testimonial.name }}</h5>
                <p class="card-text">{{ testimonial.text }}</p>
                    </div>
            </div>
                </div>
        </div>
    </section>
</template>

<script>
export default {
    data() {
    return {
        testimonials: [
        {
            id: 1,
            name: "Maxwill-Isaacs",
            image: "https://i.postimg.cc/vHc8rXXx/IMG-20210901-141818-127-1.webp",
            text: "Reece shows great leadership skills. Always thinks on his feet and a quick learner. Very eager to learn something new and not afraid to explore outside his comfort zone. Very charasmatic and also confident in the work that he presents."
        },
        {
            id: 2,
            name: "Joel",
            image: "https://i.postimg.cc/Ghbvn8KL/Joel-Profile.jpg ",
            text: "Reece is a very creative, and well-behaved student. He does enjoy working with his classmates and works well on his project. He has gained a-lot of knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired."
          },
          {
            id: 3,
            name: "Margo Simon",
            image: "https://i.postimg.cc/zBMn5fhS/64f5c3cac76351c4f71946e2271bee93.jpg",
            text: "Reece is a well articulated young man.  His creative thinking,  reasoning patterns and logic is impressive.  His drive and leadership qualities can only lead to success"
          },
          {
            id: 4,
            name: "Brogan",
            image: "https://i.postimg.cc/m2HXnxkQ/me-1.png ",
            text: "Reece is someone who is always seeking to improve on his skills ,eagerly engaging to find out more . He has great communication skills and team skills a well, he is someone who is always on time so I regard him as a very punctual person."
          },
          {
            id: 5,
            name: "Javier Goodall",
            image: "https://i.postimg.cc/v84sMRmZ/profileme.jpg",
            text: "Reece is a very creative, and well-behaved student. He does enjoy working with his classmates and works well on his project. He has gained a-lot of knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired."
          },
          {
            id: 6,
            name: "Brandon Swinton",
            image: "https://i.postimg.cc/gc3G2Fv8/IMG-20210822-WA0208.jpg",
            text: "Reece is dedicated to his craft and always looking for ways to improve it and has a tremendous amount of productivity. He is always showing love to those around him"
          }
        ]
        }
    }
}
</script>
