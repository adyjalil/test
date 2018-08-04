<template>
    <header>
        <section id="sec1">
            <h1>Welcome, Visitor!</h1>
            <h2>I'M ADY JALIL</h2>
        </section>
        
    </header>
</template>

<script>
export default {
    data (){
        return {
            red: 'red'
        }
    },
    methods: {
        changeColor() {
            this.red = '#d2ba48';
        }
    }
}
</script>

<style scoped>
    header{
        min-height: 100%;
        background-image: url("../assets/plant.jpg");
        background-position: 50% 70%; 
        display: flex;
        justify-content: center;
        align-items: center;
    }

    header > section {
        text-align: center;
        flex: 1;
    }

     
    h1 {
        margin-top: 0;
        font-size: 100px;
        font-family: 'Playfair Display', serif;
        color: var(--white);
        text-shadow: 1px 1px 7px var(--black), -1px -1px 2px var(--black);
        
    }

    h2 {
        font-size: 80px;
        font-family: 'Asap', sans-serif;
        color: var(--white);
        text-shadow: 1px 1px 7px var(--black), -1px -1px 2px var(--black);
        margin-top: 40px;
    }

    
</style>


