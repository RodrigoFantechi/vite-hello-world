<script>
export default{
    name: AppHero
}
</script>

<template>
    <div class="jumbotron">
        <div class="text">
            <h1>My Jumbotron</h1>
            <p>the best developer in my house</p>
            <div class="btn">Send</div>
        </div>
    </div>
</template>

<style scoped>
.jumbotron {
    height: 350px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    padding-left: 2rem;
    background-color: #eeeeeea1;
    color: black
}

p {
    color: black;
    font-weight: bold;
    margin: 0.5rem 0;
}

.btn {
   display: inline-block;
    color: black;
    font-weight: bold;
    padding: 0.4rem 0.75rem;
    border-radius: 10px;
    border: 1px solid black;
    transition: 0.3s;
}
.btn:hover{
    cursor: pointer;
    transform: scale(1.2);
}
</style>