<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  const script = document.createElement('script')
  script.src = "https://www.goodreads.com/review/grid_widget/173710420.Beatrice's%20bookshelf:%20read?cover_size=small&hide_link=&hide_title=true&num_books=52&order=d&shelf=read&sort=date_read&widget_id=1747668306"
  script.type = "text/javascript"
  script.async = true
  document.getElementById("gr_grid_widget_1747668306")?.appendChild(script)
})
</script>


<template>
    <div class="home">
        <!-- Header Section -->
        <div class="introSection" style="display: flex; align-items: center; margin-bottom: 20px;">
            <img src="../assets/images/Headshot.png" alt="Beatrice's Headshot" class="profile-img" width="25%" height="25%">
            <div class="intro">
                <h2>About Me:</h2>
                <h3>Master of Science in Quantitative and Computational Finance Candidate</h3>
                <p2>
                    Hi, I’m Beatrice! I’m a graduate student in Quantitative and Computational Finance, passionate about solving complex problems through data and finance. When I’m not diving into numbers and code, you’ll find me running on trails, hiking, or enjoying water sports. I also love unwinding with a good book or expressing my creativity through drawing and painting. Whether it’s exploring nature or tackling challenges, I’m always looking for the next opportunity to learn and grow.
                </p2>
                <section class="skills">
                <!-- Skills Section -->
                    <h2>Key Skills</h2>
                    <ul2>
                        <li>Python</li>
                        <li>R</li>
                        <li>SQL</li>
                        <li>Data Visualization</li>
                        <li>Quantitative Finance</li>
                    </ul2>
                </section>
                <section class="contact">
            <h2>Get in Touch</h2>
            <ul>
                <li><a href="https://www.linkedin.com/in/beatrice-k-lee444" target="_blank">LinkedIn</a></li>
                <li><a href="mailto:blee444@gatech.edu">Email</a></li>
            </ul>
            </section>
            </div>
            
        </div>

        <!-- Contact Section -->
        <section class="contact">
            <h2>Get in Touch</h2>
            <ul>
                <li><a href="https://www.linkedin.com/in/beatrice-k-lee444" target="_blank">LinkedIn</a></li>
                <li><a href="mailto:blee444@gatech.edu">Email</a></li>
            </ul>
        </section>

    </div>
</template>