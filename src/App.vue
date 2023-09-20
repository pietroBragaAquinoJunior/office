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
        <h1 style="padding-top: 40px; font-size: 50px; font-weight: 500" class="texto-especial">Office é agora Microsoft
          365</h1>
        <p style="padding-top: 20px; font-size: 20px">O novo Microsoft 365 permite que você crie, compartilhe e <br/>
          colabore em um só lugar com seus aplicativos
          favoritos</p>
        <div style="display: flex; gap:30px; padding-top: 30px;">
          <button class="primary-button">Entrar</button>
          <button class="secondary-button">Comprar o Microsoft 365</button>
        </div>
        <p class="aviso-azul">Inscreva-se para obter a versão gratuita do Microsoft 365 ></p>
      </div>
      <div style="display: flex; justify-content: center">
        <img style="border-radius: 20px" width="100%" src="./assets/imagem-principal.png" alt="Imagem Principal"/>
      </div>
    </div>
  </section>
  <section class="segoeui">
    <div class="secondary-section">
      <div class="secondary-section-menu">
        <div class="card-button active">Para Página Inicial</div>
        <div class="card-button">Para Organizações</div>
        <div class="card-button">Para Educadores</div>
      </div>
      <div class="secondary-section-principal">
        <div
            style="display: flex; justify-content: center; flex-direction: column; align-items: center; text-align: center; gap: 30px">
          <h2 class="h2-secondary-section">Gratuito ou premium: <br/>
            o Microsoft 365 está com você</h2>
          <p class="p-secondary-section">Todos obtém armazenamento em nuvem e aplicativos essenciais do <br/> Microsoft
            365 na Web, gratuitamente</p>
        </div>
        <div>
          <img src="./assets/first-secondary-section.png" alt="office image"/>
        </div>
        <div
            style="display: flex; align-items: center; justify-content: space-between; width: 100%; padding-left: 100px; padding-right: 100px">
          <div style="width: 500px; display: flex; flex-direction: column">
            <img src="../public/plusicon.svg" alt="plus-icon" style="width: 50px"/>
            <h2 class="h2-secondary-section">Criar algo inspirador</h2>
            <p class="p-secondary-section" style="padding-top: 30px">Crie rapidamente qualquer coisa para você e sua
              família. Cartões de aniversário, folhetos escolares, orçamentos, postagens sociais, vídeos e mais. nenhuma
              experiência de design gráfico necessária.</p>
            <p class="aviso-laranja">Inscreva-se para obter a versão gratuita do Microsoft 365 ></p>
          </div>
          <div>
            <img alt="office image2" src="./assets/second-secondary-section.png"/>
          </div>
        </div>
        <div
            style="display: flex; align-items: center; justify-content: space-between; width: 100%; padding-left: 100px; padding-right: 100px">
          <div>
            <img alt="office image2" src="./assets/third-secondary-section.png"/>
          </div>
          <div style="width: 500px; display: flex; flex-direction: column">
            <img src="../public/cloud-icon.svg" alt="plus-icon" style="width: 50px"/>
            <h2 class="h2-secondary-section">Armazenar com confiança</h2>
            <p class="p-secondary-section" style="padding-top: 30px">Seus arquivos e memórias permanecem seguros na
              nuvem, com 5 GB gratuitos e mais de 1 TB se você se tornar premium.</p>
          </div>
        </div>
        <div
            style="display: flex; align-items: center; justify-content: space-between; width: 100%; padding-left: 100px; padding-right: 100px">
          <div style="width: 500px; display: flex; flex-direction: column">
            <img src="../public/arrow-icon.svg" alt="plus-icon" style="width: 50px"/>
            <h2 class="h2-secondary-section">Compartilhar com <br/> amigos...</h2>
            <p class="p-secondary-section" style="padding-top: 30px">... mesmo que eles não tenham o Microsoft 365.
              Colabore e crie arquivos perfeitamente com seus amigos e familiares</p>
          </div>
          <div>
            <img alt="office image2" src="./assets/five-secondary-section.png"/>
          </div>
        </div>
        <div style="display: flex; align-items: center; justify-content: space-between; width: 100%; padding-left: 100px; padding-right: 100px">
          <div>
            <img alt="office image2" src="./assets/six-secondary-section.png"/>
          </div>
          <div style="width: 500px; display: flex; flex-direction: column">
            <img src="../public/heart-icon.svg" alt="plus-icon" style="width: 50px"/>
            <h2 class="h2-secondary-section">Proteja seus entes queridos</h2>
            <p class="p-secondary-section" style="padding-top: 30px">Proteja seus entes queridos com recursos de
              segurança digital e física e o aplicativo Proteção para a Família</p>
          </div>
        </div>
        <div
            style="display: flex; align-items: center; justify-content: space-between; width: 100%; padding-left: 100px;">
          <div style="width: 500px; display: flex; flex-direction: column">
            <h2 class="h2-secondary-section">Mais aplicativos em menos locais</h2>
            <p class="p-secondary-section" style="padding-top: 30px">O novo Microsoft 365 reúne seus aplicativos Microsoft favoritos em uma única plataforma intuitiva</p>
          </div>
          <div>
            <img alt="office image2" src="./assets/seven-secondary-section.png"/>
          </div>
        </div>
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

  background: linear-gradient(0deg, white, #E3E9FC);
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

.primary-button {
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

.primary-button:hover {
  background: #353cb2;
}

.secondary-button {
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

.secondary-button:hover {
  background: #d4d5ff;
}

.aviso-azul {
  margin-top: 25px;
  color: #464FEB;
  cursor: pointer;
  border-bottom: 2px solid transparent;
}

.aviso-azul:hover {
  border-bottom: 2px solid #464FEB;
}

.secondary-section {
  background: #FFF4ED;
  min-height: 2000px;
  display: flex;
  flex-direction: column;
  justify-content: start;
  align-items: center;
  padding-top: 45px;
  padding-bottom: 45px;
}

.secondary-section-menu {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  width: 92%;
}

.card-button {
  height: 130px;
  flex: 1;
  font-weight: 500;
  font-size: 20px;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #792000;
  background: #F9DBD0;
  box-shadow: #fff 0 8px 0, rgba(0, 0, 0, .14) 0 0 8px;
}

.card-button.active {
  background: white;
  color: #D83B01;
}

.secondary-section-principal {
  min-height: 1000px;
  background: white;
  width: 92%;
  display: flex;
  flex-direction: column;
  justify-content: start;
  align-items: center;
  padding-top: 50px;
  padding-bottom: 50px;
  gap: 100px;
}

.h2-secondary-section {
  font-size: 37px;
  color: #242424;
  font-weight: 500;
}

.p-secondary-section {
  font-size: 18px
}

.aviso-laranja {
  margin-top: 25px;
  color: #D83B01;
  cursor: pointer;
  border-bottom: 2px solid transparent;
}

.aviso-laranja:hover {
  border-bottom: 2px solid #D83B01;
}
</style>
