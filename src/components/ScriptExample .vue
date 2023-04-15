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
            logged_in: false,

        }
    },
    methods: {
        show_info: function (){
            let main = document.querySelector( `.main` );
            for ( let i = 0; i < this.Tweets.length; i++ ) {
                main.insertAdjacentHTML(`beforeend`,
                        `<h1>${this.Tweets[i]}</h1>`);
            }
            if ( this.logged_in === true ) {
                main.insertAdjacentHTML(`beforeend` ,`<h2> user loged is ${this.logged_in}</h2>`)

            } else
            {
                main.insertAdjacentHTML(`beforeend` ,`<h2> user loged is ${this.logged_in}</h2>`)

            }
            for ( let i = 0; i < this.num_friends.length; i++ ) {
                main.insertAdjacentHTML(`beforeend`,
                        `<h1>${this.num_friends[i]}</h1>`);
            }
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