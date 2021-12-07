<template>
  <div>
    <b-button variant="success" v-b-toggle.sidebar-right>Nuestros Platos</b-button>
    <b-sidebar id="sidebar-right" title="Nuestros Platos" right shadow>
      <div class="px-3 py-2">
        <p>
          Nuestros platos, terminados por las mejores manos, te llevarán por una montaña de emociones y sensaciones primeramente al olfato,
          y luego al paladar, al poder degustar lo mejor de nuestra gastronomía mientras te hospedas en nuestro maravilloso Hotel.
        </p>
        <b-img src="https://images.unsplash.com/photo-1601465470925-d6e9eb3c34df?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1450&q=80" fluid thumbnail></b-img>
        <b-img src="https://images.unsplash.com/photo-1577308873518-7fd772788ec6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" fluid thumbnail></b-img>
        <b-img src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" fluid thumbnail></b-img>
      </div>
    </b-sidebar>
  </div>
</template>