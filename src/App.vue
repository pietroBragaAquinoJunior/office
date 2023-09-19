<script setup>

</script>

<template>
  <header class="header-container segoeui">
    <div class="menu-left">
      <div class="first-menu">
        <img style="cursor:pointer" width="100" src="./assets/logo.png" alt="logotipo"/>
        <div style="color: black; font-weight: bold;transform: scale(150%)">|</div>
        <div style="font-weight: 500; font-size: 20px;">Office</div>
      </div>
      <nav class="second-menu">
        <ul>
          <li>Produtos</li>
          <li>Recursos</li>
          <li>Modelos</li>
          <li>Suporte</li>
          <li>Minha conta</li>
          <li>Comprar agora</li>
        </ul>
      </nav>
    </div>
    <div class="menu-right">
      <div>Toda Microsoft</div>
      <div>Entrar</div>
    </div>
  </header>
  <section class="segoeui">
    <div class="blue-row">
      <p style="color: white; border-bottom: 1px solid transparent;">Apresentando Microsoft 365 Copilot, seu copiloto
        para o trabalho.</p>
      <p class="texto-saiba-mais">Saiba mais ></p>
    </div>
  </section>
  <section class="segoeui">
    <div class="principal-section">
      <div style="display: flex; justify-content: center; flex-direction: column; align-items: center;">
        <img src="../public/microsoft-icon.svg" alt="svg-logo"/>
        <h1 style="padding-top: 40px; font-size: 50px; font-weight: 500" class="texto-especial">Office é agora Microsoft 365</h1>
        <p style="padding-top: 20px; font-size: 20px">O novo Microsoft 365 permite que você crie, compartilhe e <br/> colabore em um só lugar com seus aplicativos
          favoritos</p>
        <div style="display: flex; gap:30px; padding-top: 30px;">
          <button class="primary-button">Entrar</button>
          <button class="secondary-button">Comprar o Microsoft 365</button>
        </div>
        <p class="aviso-azul">Inscreva-se para obter a versão gratuita do Microsoft 365 ></p>
      </div>
      <div style="display: flex; justify-content: center">
        <img style="border-radius: 20px" width="100%" src="./assets/imagem-principal.png" alt="Imagem Principal" />
      </div>
    </div>
  </section>
</template>

<style scoped>
.segoeui {
  font-family: "Segoe UI", serif;
}

.header-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 60px;
}

.first-menu {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
}

.menu-left {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
}

.second-menu ul {
  display: flex;
  list-style: none;
  gap: 20px;
  align-items: end;
}

.second-menu ul li {
  list-style: none;
  cursor: pointer;
  color: #262626;
  border-bottom: 2px solid white;
}

.second-menu ul li:last-child {
  border: 1px solid black;
  border-radius: 2px;
  padding: 5px;
}

.second-menu ul li:last-child:hover {
  border-bottom: 1px solid black;
}

.second-menu ul li:hover {
  border-bottom: 2px solid black;
}

.menu-right {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}

.blue-row {
  background: #464FEB;
  height: 64px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.texto-saiba-mais {
  color: white;
  cursor: pointer;
  margin-left: 20px;
  border-bottom: 1px solid transparent;
  font-weight: 500;
}

.texto-saiba-mais:hover {
  border-bottom: 1px solid white;
}

.principal-section {

  background: linear-gradient(0deg, white, #E3E9FC );
  display: flex;
  flex-direction: column;
  gap: 50px;
  align-items: center;
  padding: 50px;
}

.texto-especial {
  background: linear-gradient(96.2deg, #ED6419 -3.08%, #9629E7 14.74%, #0860C7 72.12%); /* Substitua as cores pelo seu degradê desejado */
  -webkit-background-clip: text; /* Para navegadores WebKit, como o Chrome e o Safari */
  background-clip: text;
  color: transparent; /* Torna o texto invisível */
  font-weight: bold; /* Aplica o negrito ao texto */
}

.primary-button{
  background: #464FEB;
  color: white;
  width: 205px;
  border: none;
  border-radius: 3px;
  cursor: pointer;
  transition: all .5s;
  height: 40px;
  font-size: 15px;
}
.primary-button:hover{
  background: #353cb2;
}
.secondary-button{
  background: white;
  color: #464FEB;
  width: 205px;
  border-radius: 3px;
  cursor: pointer;
  transition: all .5s;
  height: 40px;
  border: 2px solid #464FEB;
  font-size: 15px;
}
.secondary-button:hover{
  background: #d4d5ff;
}
.aviso-azul{
  margin-top: 25px;
  color: #464FEB;
  cursor: pointer;
  border-bottom: 2px solid transparent;
}
.aviso-azul:hover{
  border-bottom: 2px solid #464FEB;
}
</style>
