<template>
<div>
    <p>Nome: {{ nome }}</p>
    <p>E-mail: {{ email }}</p>
</div>    
</template>

<script>

    export default {
        name: "UsuarioComponent",
        data(){
            return {
                nome : "Maycon",
                email : "maycon.almeida@alloha.com"
            }
        }
    }


</script>