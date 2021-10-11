<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Nuevo visitante??</div>

                    <div class="card-body">
                        Para entrar en el sitio, debes <a href="/login">logearte</a><br>
                        Ó <a href="/register">registrate</a>, y se parte de esta comunidad...
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
