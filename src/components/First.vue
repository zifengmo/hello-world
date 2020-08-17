<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <p>
            想你，是最美好的心事
            <br>
<!--            <a href="https://www.google.com" target="_blank" rel="noopener">Google 一下</a>.-->
        </p>
        <h3>烟波虽小，一叶障目</h3>
        <ul>
            <li><a href="https://music.163.com/#/user/home?id=107884665" target="_blank" rel="noopener">江畔何人初见月</a></li>
            <li><a href="https://i.y.qq.com/n2/m/share/details/taoge.html?platform=11&appshare=android_qq&appversion=10020507&hosteuin=oKvF7e4z7eosoc**&id=3978042607&ADTAG=wxfshare&from=singlemessage" target="_blank" rel="noopener">江月何年初照人</a></li>
        </ul>
        <h3>如果有电脑</h3>
        <ul>
            <li><a href="http://3country.xyz/music/" target="_blank" rel="noopener">随便听听吧</a></li>
        </ul>
        <h3>如果没电脑</h3>
        <ul>
            <li><a href="http://3country.xyz/music/qq" target="_blank" rel="noopener">随机听听</a></li>
        </ul>
        <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=820356&auto=1&height=66"></iframe>
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
    img{
        display: block;
    height: auto;
        max-width: 100%;
    }
</style>
