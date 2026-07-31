---
layout: default
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Inter:wght@400;600&display=swap');

  /* --- IMAGEM DE FUNDO GLOBAL --- */
  body { 
    font-family: 'Inter', sans-serif; 
    color: #1a2b3c; 
    line-height: 1.6;
    background-image: url('{{ site.baseurl }}/imagem-1.jpg.jpeg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    margin: 0;
    padding: 20px 0;
  }

  /* Container Principal com Fundo Translúcido para Leitura Perfeita */
  .site-container {
    max-width: 800px;
    margin: 0 auto;
    background: rgba(255, 255, 255, 0.94);
    padding: 40px;
    border-radius: 16px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
    backdrop-filter: blur(5px);
  }

  h1 { 
    font-family: 'Montserrat', sans-serif;
    color: #00a896; 
    border-bottom: 3px solid #00a896; 
    padding-bottom: 12px;
    margin-top: 0;
  }

  h2 {
    font-family: 'Montserrat', sans-serif;
    color: #1a2b3c;
    margin-top: 35px;
  }

  .highlight-box {
    background-color: #f0f7f6;
    border-left: 5px solid #00a896;
    padding: 18px;
    margin: 20px 0;
    border-radius: 6px;
  }

  .cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  .card {
    background-color: #ffffff;
    padding: 18px;
    border-radius: 8px;
    border-top: 4px solid #00a896;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }

  .card h3 {
    margin-top: 0;
    color: #1a2b3c;
    font-size: 1.1rem;
  }

  .btn-action {
    display: inline-block;
    background-color: #00a896;
    color: white !important;
    padding: 12px 24px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
    margin-top: 10px;
  }

  /* Ocultar elementos padrão do Jekyll */
  a[href*="github.com"], header ul, header p.view, footer { 
    display: none !important; 
  }
</style>

<div class="site-container">

  <!-- 1. PERFIL / QUEM SOU -->
  # Hey, chamo-me Miriam e não sou um AI.

  <p>
    Ser criativo também se aprende. A minha missão é dar-te a prática para desenhares projetos, preveres custos e avançares sem medo.
  </p>

  <p>
    <a href="https://www.linkedin.com/in/miriamiferreira/" target="_blank">Vê o meu perfil no LinkedIn</a>
  </p>

  <hr>

  <!-- 2. EXPECTATIVAS: O QUE TRAZEMOS / O QUE TRAZES -->
  <h2>Expectativas: O que alinhamos juntos?</h2>

  <div class="highlight-box">
    <strong>É urgente:</strong> Este é o momento para dizeres <em>o que te vem à cabeça</em> e começarmos a construir.
  </div>

  <h3>O que a nossa escola traz para ti:</h3>
  <ul>
    <li>Método 100% prático desde a primeira sessão (aprende-se a fazer, fazendo).</li>
    <li>Passo a passo estruturado, sem teorias complexas nem perda de tempo.</li>
    <li>Eliminação de distrações para libertar o espaço necessário para produzires grandes coisas.</li>
  </ul>

  <h3>E tu, o que trazes para a escola?</h3>
  <ul>
    <li>Vontade de tirar as tuas ideias da cabeça e colocá-las no papel.</li>
    <li>Abertura para aprender a prever custos e gerir recursos.</li>
    <li>Compromisso em dar o primeiro passo com autonomia.</li>
  </ul>

  <hr>

  <!-- 3. MODALIDADE / O QUE VAIS APRENDER -->
  <h2>O que vais aprender</h2>

  <div class="cards-grid">
    <div class="card">
      <h3>Da Ideia à Estrutura</h3>
      <p>Desenhar o projeto: objetivos claros, atividades, cronograma e indicadores.</p>
    </div>
    <div class="card">
      <h3>Prever o Orçamento</h3>
      <p>Aprende a construir e justificar o teu próprio orçamento realista.</p>
    </div>
    <div class="card">
      <h3>Encontrar Recursos</h3>
      <p>Onde procurar financiamento, parceiros e ferramentas essenciais.</p>
    </div>
    <div class="card">
      <h3>Avançar Sem Medo</h3>
      <p>Um plano prático para começares a implementar imediatamente.</p>
    </div>
  </div>

  <br>

  <h3>Modalidades e Metodologia</h3>
  <ul>
    <li><strong>Formação Individual:</strong> acompanhamento 1-para-1, ao teu ritmo, focado no teu projeto real.</li>
    <li><strong>Formação para Organizações:</strong> workshops e programas à medida para equipas, associações e ONGs.</li>
    <li><strong>Idiomas disponíveis:</strong> Português (PT/BR), Italiano e Inglês.</li>
  </ul>

  <hr>

  <!-- 4. PREÇOS -->
  <h2>Formatos e Preços</h2>

  | Formato | Duração | Investimento |
  | :--- | :--- | :--- |
  | **Sessão individual** | 1 hora | €5 |
  | **Programa Completo (5 sessões)** | 2 horas cada | €100 |
  | **Workshop Organizações** | Meio-dia / Dia | Sob consulta |

  <hr>

  <!-- 5. COMO AGENDAR -->
  <h2>Como Agendar</h2>

  <p>Tens um projeto em mente e não sabes por onde começar?</p>
  <p>Marca uma chamada inicial para percebermos qual o formato ideal para ti ou para a tua organização.</p>

  <p>
    <a href="contact.html" class="btn-action">Agendar / Enviar Email</a>
  </p>

  <p><small><strong>Disponibilidade atual:</strong> Vagas abertas para o próximo trimestre. Turmas a partir de setembro.</small></p>

</div>
