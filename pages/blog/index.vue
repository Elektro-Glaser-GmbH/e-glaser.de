<script setup lang="ts">
useSeoMeta({
  title: 'Blog – Elektro-Glaser',
  description: 'Tipps, Einblicke und Neuigkeiten rund um Erneuerbare Energien, Smart Home und Elektrotechnik von Elektro-Glaser.',
})

const { data: posts } = await useAsyncData('blog-posts', () =>
  queryContent('blog')
    .sort({ date: -1, $numeric: true })
    .find()
)
</script>

<template>
  <div class="section container">
    <p class="section-label">Blog</p>
    <h1>Neuigkeiten &amp; Einblicke</h1>
    <p>Tipps, Erfahrungsberichte und Neuigkeiten rund um Erneuerbare Energien, Smart Home und Elektrotechnik.</p>
    <hr />

    <div class="blog-list">
      <article v-for="post in posts" :key="post._path" class="blog-card">
        <div class="blog-meta">
          <time :datetime="post.date">{{ new Date(post.date).toLocaleDateString('de-DE', { year: 'numeric', month: 'long', day: 'numeric' }) }}</time>
          <span v-if="post.categories" class="blog-categories">
            <span v-for="cat in post.categories" :key="cat" class="blog-tag">{{ cat }}</span>
          </span>
        </div>
        <h2>
          <NuxtLink :to="post._path">{{ post.title }}</NuxtLink>
        </h2>
        <p>{{ post.description }}</p>
        <NuxtLink :to="post._path" class="btn btn-outline">Weiterlesen →</NuxtLink>
      </article>
    </div>
  </div>
</template>
