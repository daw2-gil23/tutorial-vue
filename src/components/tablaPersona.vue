<template>
    <div id="tabla-personas">
      <table class="table">
        <thead>
          <tr>
            <th>Nombre</th>
            <th>Apellido</th>
            <th>Email</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Jon</td>
            <td>Nieve</td>
            <td>jon@email.com</td>
          </tr>
          <tr>
            <td>Tyrion</td>
            <td>Lannister</td>
            <td>tyrion@email.com</td>
          </tr>
          <tr>
            <td>A</td>
            <td>Daenerys</td>
            <td>daenerys@email.com</td>
          </tr>
        </tbody>
      </table>
    </div>
  </template>
  
  <script>
    export default {
      name: 'tabla-persona',
      props: {
        persona: Array,
      },
    }
  </script>
  
  <style scoped></style>