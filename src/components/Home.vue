<template>
  <div class="content">
    <div class="home-desc">
      <h1>Andean Travel Company</h1>
      <div id="logo" />
      <p>
        Sistema de asignación diaria de vehiculos a choferes. 
        En busca de ofrecer el mejor servicio, con sus mejores elementos
        y vehiculos, asignamos diariamente a nuestros choferes para 
        hacia diferentes rutas y diferentes vehiculos.
      </p>
    </div>
  </div>
</template>

<style scoped>
#logo {
  height: 200px;
  width: 200px;
  border-radius: 50%;
  background-image: url("../assets/images/logo.png");
  background-size: 200%;
  background-position: center center;
}
p {
  color: #000;
}

.content {
  display: flex;
  justify-content: center;
}

.home-desc {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
  max-width: 600px;
}

.content h1 {
  font-weight: 600;
}
</style>
