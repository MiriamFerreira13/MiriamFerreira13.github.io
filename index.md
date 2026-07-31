---
layout: default
---

<style>
  /* Importação de Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Inter:wght@400;600&display=swap');

  body { 
    font-family: 'Inter', sans-serif; 
    color: #1a2b3c; 
    line-height: 1.6;
  }

  h1 { 
    font-family: 'Montserrat', sans-serif;
    color: #00a896; 
    border-bottom: 3px solid #00a896; 
    padding-bottom: 15px;
    letter-spacing: -1px;
  }

  h2 {
    font-family: 'Montserrat', sans-serif;
    color: #1a2b3c;
    margin-top: 30px;
  }

  .highlight-box {
    background-color: #f0f7f6;
    border-left: 5px solid #00a896;
    padding: 20px;
    margin: 20px 0;
    border-radius: 4px;
  }

  /* SECÇÃO DE DESTAQUES COM IMAGENS DE FUNDO */
  .seccao-destaques {
    display: flex;
    flex-direction: column;
    gap: 30px;
    margin: 40px 0;
  }

  .item-destaque {
    display: flex;
    align-items: center;
    gap: 25px;
    background-color: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 12px;
    padding: 24px;
  }

  /* Caixa reservada para a imagem */
  .caixa-imagem {
    width: 250px;
    height: 180px;
    border-radius: 8px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    flex-shrink: 0;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
  }

  /* Apontando para os teus ficheiros de imagem */
  .bg-imagem-1 {
    background-image: url('{{ site.baseurl }}/imagem-1.jpg.jpeg');
  }

  .bg-imagem-2 {
    background-image: url('{{ site.baseurl }}/imagem-2.jpg.jpeg');
  }

  .destaque-texto {
    flex: 1;
  }

  .destaque-texto h2 {
    margin-top: 0;
    color: #00a896;
  }

  /* ESTILOS DOS CARDS (O que vais aprender) */
  .cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }

  .card {
    background-color: #f0f7f6;
    padding: 20px;
    border-radius: 8px;
    border-top: 4px solid #00a896;
  }

  .card h3 {
    margin-top: 0;
    color: #1a2b3c;
  }

  /* Responsividade para Telemóveis */
  @media (max-width: 650px) {
    .item-destaque {
      flex-direction: column !important;
      text-align: center;
    }
    .caixa-imagem {
      width: 100%;
      height: 200px;
    }
  }

  /* Ocultar elementos padrão do Jekyll */
  a[href*="github.com"], 
  header ul, 
  header p.view, 
  footer { 
    display: none !important; 
  }
</style>

# Hey, chamo-me Miriam e não sou um AI.

<div class="highlight-box">
  <strong>É urgente:</strong> "Último" momento para dizer <strong>o que te vem à cabeça</strong>.
</div>

<p>
  <a href="contact.html">Contactos</a> &nbsp; 
  <a href="https://www.linkedin.com/in/miriamiferreira/" class="btn-linkedin">Vê o meu LinkedIn Perfil</a>
</p>

<!-- SECÇÃO DE IMAGENS DE FUNDO NAS LATERAIS -->
<div class="seccao-destaques">
  
  <!-- 1. Imagem na Esquerda, Texto na Direita -->
  <div class="item-destaque">
    <div class="caixa-imagem bg-imagem-1"></div>
    <div class="destaque-texto">
      <h2>Da Ideia à Estrutura</h2>
      <p>Desenhar projetos sem te perderes em teorias complexas. Definimos objetivos claros, atividades e um cronograma prático para tirares as tuas ideias da cabeça e as colocares no papel.</p>
    </div>
  </div>

  <!-- 2. Texto na Esquerda, Imagem na Direita -->
  <div class="item-destaque">
    <div class="destaque-texto">
      <h2>Avançar com Autonomia</h2>
      <p>Aprende a prever custos, encontrar parceiros e fontes de financiamento. Um plano passo a passo concebido para começares a implementar imediatamente, sem depender de mais ninguém.</p>
    </div>
    <div class="caixa-imagem bg-imagem-2"></div>
  </div>

</div>

# Ser criativo também se aprende
A prática para desenhar projetos, prever custos e avançar sem medo.

### Eliminar as fontes de distração, liberta um espaço necessário para que possamos produzir grandes coisas. 

## O que vais aprender

<div class="cards-grid">
  <div class="card">
    <h3>Desenhar o Projeto</h3>
    <p>Da ideia à estrutura: objetivos, atividades, cronograma e indicadores — sem te perderes em teoria.</p>
  </div>
  <div class="card">
    <h3>Prever o Orçamento</h3>
    <p>Aprende a construir e justificar o teu próprio orçamento, com uma base realista e credível.</p>
  </div>
  <div class="card">
    <h3>Encontrar Recursos</h3>
    <p>Sabe onde procurar financiamento, parceiros e ferramentas — sem depender de mais ninguém.</p>
  </div>
  <div class="card">
    <h3>Avançar Sem Medo</h3>
    <p>Um plano passo a passo para começares a implementar já, mesmo sem experiência prévia.</p>
  </div>
</div>

---

### Para quem é

- **Formação Individual:** acompanhamento 1-para-1, ao teu ritmo, focado no teu projeto real.
- **Formação para Organizações:** workshops e programas à medida para equipas, associações e ONGs.

---

### Metodologia

- Prática desde a primeira sessão — aprende-se a fazer, fazendo.
- Passo a passo, sem teoria desnecessária.
- Disponível em Português (PT/BR), Italiano e Inglês.

---

## Formatos e Preços

| Formato                   | Duração      | Investimento         |
| ------------------------- | ------------ | -------------------- |
| 5 sessões                 | 2 horas      | €100                 |
| Sessão individual         | 1 hora       | €5                   |
| Workshop para organizações | meio-dia/dia | Sob consulta         |

---

### Próximos Passos

Tens um projeto em mente e não sabes por onde começar? 
Marca uma chamada gratuita de 15 minutos 
[Envia email](contact.html)
para perceber qual o formato de formação mais adequado a ti ou à tua organização.

**Disponibilidade atual:** Vagas abertas para o próximo trimestre. Turmas a partir de setembro.
