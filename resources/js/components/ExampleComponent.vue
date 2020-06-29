<template>
    <div class="container mt-5 justify-content-center ">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Formulario</div>
                    <div class=" card-body">
                       <form action="/home" method="post">
                           <label for="nameNome"> Nome</label>
                         <input type="text" class="form-control">
                             <label for="nameNome"> Email</label>
                         <input type="text" class="form-control">
                             <label for="nameNome"> Senha</label>
                         <input type="text" class="form-control">
                         <button class="btn btn-success mt-2">Enviar</button>
                       </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
   
    }
</script>
