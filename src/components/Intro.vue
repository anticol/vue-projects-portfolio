<template>
    <div class='intro'>
        <div class='intro-header'>
            <img src='https://media.licdn.com/dms/image/C4D03AQFopD8rynZBCw/profile-displayphoto-shrink_200_200/0?e=1578528000&v=beta&t=49XRKBhdqyrK-C6ah56CgZE-ROkOqBiXAzaZxNJxnkU'
                 v-on:click='greet'>
            <h1>{{user.firstName}} {{user.lastName}}</h1>
            <h3 v-text='intro'></h3>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Intro',
        data() {
            return {
                title: 'David Horov',
                user: {
                    firstName: 'David',
                    lastName: 'Horov'
                },
                intro: 'Remote Web Application Developer'
            }
        }
    }
</script>

<style scoped>
    h1 {
        font-family: 'Ubuntu', sans-serif;
    }

    h3 {
        margin-bottom: 35px;
        font-family: 'Ubuntu', sans-serif;

    }

    .intro-header img {
        max-width: 250px;
        border-radius: 250px;
        box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.7);
    }

    .intro-header img:hover {
        box-shadow: 0px 0px 5px rgba(0, 0, 0, 1);
    }

</style>
