# Projeto de certificação 1 – Agência de Viagem

### Resumo do projeto

Crie uma página web que contenha um banner de um vilarejo europeu ou que remeta a uma cidade qualquer. A página deve ter no mínimo três seções, chamadas TripMe, MeetUs, Advice ou MinhaViagem, NosEncontre, Conselhos.

### Introdução

Inicialmente, quando queremos colocar um website no ar para realizar alguma venda, criamos uma landing page. Ela seria uma página "catch the fish", no sentido literal, "pegue o peixe" ou fisgar o cliente!

Os requisitos mínimos para avaliar a sua página seriam:

Deve ter um banner dentro do <main>;
Deve existir uma navegação mínima <nav>;
Deve existir navegação das seções criadas direcionadas ao topo! Ou seja, de volta ao "Home" ou ao seu <nav>;

### Resolução
Primeiramente foi criado o menu da página com os links de navegação.
```html
<header>
  <nav id="navbar">
      <ul>
          <li><a href="#banner">Home</a></li>
          <li><a href="#tripme">TripMe</a></li>
          <li><a href="#meetus">MeetUs</a></li>
          <li><a href="#advice">Advice</a></li>
      </ul>
  </nav> 
</header>
```

Em seguida, foi criada a seção para definir o banner, conforme foi especificado nos requisitos do projeto dentro das tag <main>.
```html
<section id="banner">
  <h1>Explore Lugares Incríveis!</h1>
</section>
```

Depois disso, foram criadas três seções de conteúdo, para a navegação na página.
```html
<section id="tripme">
  <h2>TripMe</h2>
  <p>Descubra destinos maravilhosos e planeje sua próxima aventura conosco.</p>
</section>

<section id="meetus">
  <h2>MeetUs</h2>
  <p>Saiba mais sobre nós e como podemos ajudar a tornar sua viagem inesquecível.</p>
</section>

<section id="advice">
  <h2>Advice</h2>
  <p>Dicas valiosas para uma experiência de viagem incrível e sem preocupações.</p>
</section>
```

Após a criação do conteúdo da página, foi criado o rodapé da landing page embora não tenha sido especificado foi feito.
```html
<footer>
  <p>&copy; 2025 Viagens - Todos os direitos reservados.</p>
</footer>
```

### execução do código

faça o download do repositorio em sua máquina acesse o diretorio **'viagens--landing-page'** e execute o arquivo **'index.html'** com seu navegador de preferência.