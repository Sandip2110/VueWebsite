<template>
  <div>
    <div v-for="blog of blogs" v-bind:key="blog.id">
      <h2>{{blog.title}}</h2>
      <p>{{blog.subtext}}</p>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      blogs: [
        {
          id: 1,
          title: 'I am a blog title',
          subtext: 'chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata.',
        },
        {
          id: 2,
          title: 'Emnei ekta blog',
          subtext: 'damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn .'
        },
        {
          id: 3,
          title: 'Something interesting yeah',
          subtext: 'some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here.'
        },
        {
          id: 4,
          title: 'I am a blog title',
          subtext: 'chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata chatamata.'
        },
        {
          id: 5,
          title: 'Emnei ekta blog',
          subtext: 'damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn damn .'
        },
        {
          id: 6,
          title: 'Something interesting yeah',
          subtext: 'some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here some shit here.'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>
