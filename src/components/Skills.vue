<template>
    <div>
        <div class='skills-section'>
            <ul>
                <li v-for="skill in skills">{{skill.skillName}}</li>
            </ul>
        </div>
        <div class="features-section">
            <ul>
                <li v-for="skill in features">{{skill.featureName}}</li>
            </ul>
        </div>
        <hr>
    </div>
</template>

<script>
    export default {
        name: 'Skills',
        data() {
            return {
                skills: [
                    {skillName: 'JavaScript'},
                    {skillName: 'HTML5'},
                    {skillName: 'CSS3/SASS'},
                    {skillName: 'Vue.js'},
                    {skillName: 'PHP'},
                    {skillName: 'Python'},
                    {skillName: 'SQL'},
                    {skillName: 'Wordpress'},
                ],
                features: [
                    {featureName: 'Reliability'},
                    {featureName: 'Agile Methodologies'},
                    {featureName: 'Web Development'},
                    {featureName: 'Project Management'},
                    {featureName: 'Time Management'},
                ]
            }
        }
    }
</script>
<style scoped>
    .skills-section li, .features-section li {
        display: inline-block;
        margin: 5px;
        padding: 10px;
        border-radius: 15px;
        font-family: monospace;
        background: #267adb;
        font-size: 15px;
        color: #ffffff;
        padding-top: 5px;
        padding-bottom: 5px;
    }

    .skills-section ul, .features-section ul {
        margin: 0;
        padding: 0;
    }

    .features-section li {
        background: darkgreen;
        font-family: 'Cambria';
    }

    .features-section {
        margin-bottom: 30px;
    }
</style>
