<template>
    <div class="clientes">
        <div class="components">
       <FormularioClientes/>
       <TablaClientes/>
        </div>
    </div>
</template>

<script>
import  FormularioClientes from "@/components/FormularioClientes.vue";
import  TablaClientes from "@/components/TablaClientes.vue";

export default {
name: 'ClientesView',

  components: {
    FormularioClientes,
    TablaClientes
  }
}
</script>

<style >
body {
    font-family: Arial, sans-serif;
    background-color: #073c83;
    margin: 0;
    padding: 0;
}

.components{
    display: grid;
    grid-template-columns: 1fr 2fr;
   grid-auto-rows: 1fr;

}
.container {
   /* max-width: 400px;*/
    margin:1rem;
    padding: 1rem;
    background-color: #0d1c30;
    box-shadow: 0 0 10px rgba(207, 197, 197, 0.2);
    border-radius: 5px;
}

h1 {
    text-align: center;
    margin-bottom: 20px;
}

.form-group {
    margin-bottom: 15px;
}

form{

    padding: 2%;
    
}
label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

input {
    width: 100%;
    padding: 8px;
    border: 1px solid #f0dede;
    border-radius: 3px;
}

button {
    display: block;
    width: 100%;
    padding: 10px;
    background-color: #0b3d74;
    color: #ffffff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #edf6ff;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
    
}

th, td {
    padding: 10px;
    text-align: left;
 /*   border-bottom: 1px solid #ddd;*/
 border-style: solid;
    
}
tr{

    border-style: solid;
}

th {
    background-color: #052649;
    color: #fff0f0;
    border-style: solid;
}

tr:hover {
    background-color: #f5f5f5;
}
</style>