<template>
    <div>
   <h1>{{ blog_title }}</h1>
 <img :src="blog_image_url" alt="">


    </div>
</template>

<script>
export default {
    data() {
        return {

            blog_content:[`this shshjkshfkjhskjf jdhfvkjskjfdhkjs`,`vhjkdkjvkjdkjxvbkjbkjdbvjbv`],
            blog_title: `this is the title`,
            blog_image_url :`https://images.pexels.com/photos/16161517/pexels-photo-16161517.jpeg?auto=compress&cs=tinysrgb&w=1600&lazy=load`
        }
    },
        
        
    }
</script>

<style scoped>

</style>