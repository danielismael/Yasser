<h1 align="left">Sobre o projeto</h1>

<p align="left">Rest API para criar usuário e autenticação de login com JWT</p>
<br>
<h3 align="left">COMO RODAR O PROJETO BAIXADO</h3>
<hr>

<p align="left">Instalar todas as dependencias indicada pelo package.json <br>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
  <pre>$ <span class="pl-s1">npm install</span></pre>
</div>

Rodar o projeto<br>

<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
  <pre>$ <span class="pl-s1">npm start</span></pre>
</div>

Rodar o projeto usando o nodemon <br>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
  <pre>$ <span class="pl-s1">nodemon index.js</span></pre>
</div>
</p>

<br>

<h3 align="left">ROTAS</h3>
<hr>
<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030"><i>POST </i> |</span>  Login com retorno de token<br><br><strong style="font-size: 13px;">http://localhost:3000/admin/users/login</strong><br>
  <div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
    <pre><span class="pl-s1">{ "MAIL" : "", "PASSWORD" : "" }</span></pre>
  </div>
</p>
<br>
<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030"><i>GET</i> |</span> Buscar usuários<br><br><strong style="font-size: 13px;">http://localhost:3000/admin/users/</strong><br>
  <div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
    <pre><span class="pl-s1">{ "id" : "" }</span></pre>
  </div>
</p>
<br>
<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030"><i>POST</i> |</span> Cadastrar usuário<br><br><strong style="font-size: 13px;">http://localhost:3000/admin/users/</strong><br>
  <div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
    <pre><span class="pl-s1">{ "NAME" : "", "MAIL" : "", "PASSWORD" : "" }</span></pre>
  </div>
</p>
<br>
<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030"><i>PUT</i> |</span> Alterar usuário<br><br><strong style="font-size: 13px;">http://localhost:3000/admin/users/</strong><br>
  <div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
    <pre><span class="pl-s1">{ "ID" : "", "NAME" : "", "MAIL" : "", "PASSWORD" : "" }</span></pre>
  </div>
</p>
<br>
<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030"><i>DELETE</i> |</span> Deletar usuário usuário<br><br><strong style="font-size: 13px;">http://localhost:3000/admin/users/<strong><br>
  <div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto">
    <pre><span class="pl-s1">{ "ID" : "" }</span></pre>
  </div>
</p>
<br>
<h2 align="left">Techs</h2>

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" width="52" alt="nodejs logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" width="52" alt="express logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" height="40" width="52" alt="mysql logo"  />
  <img src="https://jwt.io/img/logo.svg" height="40" width="52" alt="mysql logo"  />
</div>
