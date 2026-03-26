<template>
    <div>
        <footer>
            <p>Bem vindo, meu Devzinho {{ nome }} Olá Mundo do <b>Vue com CLI</b></p>
        </footer>
    </div>
</template>

<script>
    export default {
        name: "HomeComponent",
        data() {
            return {
                nome: "Gabriel",
            };
        },
    };
</script>