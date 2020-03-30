<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <p>
            民之从事，常于几成而败之，慎终如始，则无败事
            <br>
            <a href="https://www.google.com" target="_blank" rel="noopener">Google 一下</a>.
        </p>
        <h3>烟波虽小，一叶障目</h3>
        <ul>
            <li><a href="https://music.163.com/#/user/home?id=107884665" target="_blank" rel="noopener">如果有来生</a></li>
            <li><a href="https://music.163.com/#/my/m/music/playlist?id=2676421808" target="_blank" rel="noopener">不负如来不负卿</a></li>
        </ul>
        <h3>如果有电脑</h3>
        <ul>
            <li><a href="http://3country.xyz/music/" target="_blank" rel="noopener">随便听听吧</a></li>
        </ul>
        <h3>如果没电脑</h3>
        <ul>
            <li><a href="http://3country.xyz" target="_blank" rel="noopener">等我新功能</a></li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'First',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
        margin: 40px 0 0;
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: inline-block;
        margin: 0 10px;
    }
    a {
        color: #42b983;
    }
</style>
