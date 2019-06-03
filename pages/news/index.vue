<template>
  <div>
    <h1>new</h1>
    <a href="/news/new1">new1</a>
    <nuxt-link :to="{name:'news-string',params:{string:'new2'}}">
      new2
    </nuxt-link>
  </div>
</template>
