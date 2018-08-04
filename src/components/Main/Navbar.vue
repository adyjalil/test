<template>
    <div>
        <nav>
            <ul>
                <li>ABOUT ME</li>
                <li>BACKGROUND</li>
                <li>PROJECTS</li>
                <li>CONTACTS</li>                
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    div {
        background-color: var(--green);
        margin: 0;
    }
    ul {
        margin: 0;
        list-style-type: none;
        display: flex;
        padding: 0;
    }

    li {
        padding: 10px;
        flex: 1;
        background-color: var(--white);
        text-align: center;
        font-family: 'Asap', sans-serif;
    }

    li:hover {
        cursor: pointer;
    }
</style>
