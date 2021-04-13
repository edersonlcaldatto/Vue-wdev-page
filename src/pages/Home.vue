<template>
   
   <main>

        <div class="text-top">Vídeos novos todas as <b>Quintas</b></div>
            <a href="https://youtube.com/wdevoficial/wdevoficial" target="_blank">
                <img alt="Inscreva-se" id="subscribe" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg">
            </a>
        <div class="text-bottom">youtube.com/wdevoficial</div>

   </main>

</template>

<script>
    export default {
        name: 'Home'
    }
</script>

<style scoped>

    main{
        background-color: var(--color-background-home);
        justify-content: center;
        align-items: center;
    }

    .text-top{
        color: var(--color-background-ligth);
        font-size: 22px;
        margin-bottom: 20px;
    }

    #subscribe{
        width: 340px;
    }

    .text-bottom{
        color: var(--color-background-light);
        font-size: 20px;
        margin-bottom: 18px;
    }

    @media (min-width:700px){
        #subscribe{
            width: 370px;
        }
    }

</style>

