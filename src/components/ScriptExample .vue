<template>
    <div class=" main">
 <h1> Variables</h1>
 
    </div>
</template>

<script>
export default {
    data(){
        return {
            Tweets: [`Pokemon types`, `Pokemon power`, `Pokemon funs`],
            name: [`Absol`, `Aipom`, `Alakazam`],
            num_friends: [1023, 10897, 46678],
            logged_in: true,

        }
    },
    methods: {
        show_info: function (){
            let main = document.querySelector(`.main`)
            for ( let i = 0; i < this.Tweets.length; i++ ) {
                main.insertAdjacentHTML(`afterbegin`,
`<h1>${this.Tweets[i]}</h1>`);
            }
            main.insertAdjacentHTML(`beforebegin` ,`<h2>${this.logged_in}</h2>`)
        }
    },
    mounted()
    {
        this.show_info()
    }
}
    
    
    
</script>

<style lang="scss" scoped>

</style>