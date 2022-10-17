<script>
import Post from './Post.vue'
export default {
    components: {
        Post
    },
    data() { 
        return {
            posts: [
                {   
                    id: 1,
                    title: 'Dicas para sua carreira profissional',
                    description: 'Confira algumas dicas que podem ajudar a alavancar sua carreira como desenvolvedor front-end'
                },
                {   
                    id: 2,
                    title: 'Dicas para sua carreira profissional',
                    description: 'Confira algumas dicas que podem ajudar a alavancar sua carreira como desenvolvedor front-end'
                },
                {   
                    id: 3,
                    title: 'Dicas para sua carreira profissional',
                    description: 'Confira algumas dicas que podem ajudar a alavancar sua carreira como desenvolvedor front-end'
                },
            ]
        }
    }
}
</script>

<template>
  <div>
    <h3>Últimas do blog</h3>
  </div>

  <div className='posts'>
    <Post 
    v-for="post in posts" 
    :key="post.id"
    :title="post.title"
    :description="post.description"
    ></Post>
    
    <a href="#">Ver Tudo</a>
  </div>
</template>

<style scoped>
div {
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    padding-top: 10px;
}

a {
    text-decoration: none;
    font-weight: bolder;
    color: #2F568D;
}
</style>
