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
    <div>
        <section class="bookshelf">
            <h2>
                <a style="text-decoration: none;" rel="nofollow"
                href="https://www.goodreads.com/review/list/173710420-beatrice-lee?shelf=read&utm_medium=api&utm_source=grid_widget">
                What I’m Reading
                </a>
            </h2>
            <div id="gr_grid_widget_1747668306" class="gr_grid_container"></div>
        </section>
    </div>
</template>      