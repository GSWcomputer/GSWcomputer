🚀 LucroMax: Copiloto Inteligente para Motoristas

O LucroMax é uma solução completa de engenharia de software desenhada para resolver um problema real do dia a dia: a falta de clareza sobre o lucro líquido imediato em corridas de aplicativo. Utilizando OCR (Reconhecimento Óptico de Caracteres) e um motor de cálculo em nuvem, o sistema processa dados em tempo real para entregar métricas financeiras precisas.


🛠️ Arquitetura do Sistema (Monorepo)

O projeto é estruturado como um monorepo, garantindo a sincronia entre a captura de dados no dispositivo e o processamento pesado no servidor.


📱 Mobile (Kotlin & Android Nativo)

Reconhecimento de Texto: Implementação do Google ML Kit para extração de dados diretamente da tela, otimizada para baixo consumo de bateria.

Interface Flutuante (Overlay): Desenvolvido com WindowManager para exibir resultados sem interromper o fluxo de trabalho do motorista.

Feedback Humanizado: Integração com TextToSpeech para que o motorista receba as métricas por voz, mantendo o foco na segurança do trânsito.


⚙️ Backend (Python & FastAPI)

Motor de Cálculo: API de alta performance desenvolvida em FastAPI e hospedada no Render.

Lógica de Negócio: Algoritmos avançados que consideram:

Tipo de combustível (GNV, Gasolina, Etanol).

Consumo específico por modelo de veículo (ex: Renault Logan 1.0 SCe).

Custos fixos de manutenção e depreciação.

Soma inteligente de corridas duplas/emendadas via Regex avançada.


🛡️ Foco em Segurança e Performance

Segurança de Dados: Comunicação via Headers de Autenticação privada entre o App e a API.

Otimização: Filtros de auto-leitura para impedir loops de processamento e garantir precisão nos cálculos.


📂 Estrutura do Repositório

Plaintext

LucroMax_Project/

├── app_android/ # Código fonte completo do aplicativo Android

├── backend_python/ # API FastAPI e lógica do motor de cálculo

└── README.md # Documentação do projeto

👨‍💻 Sobre Mim

---
<table>
  <tr>
    <td width="150px"><img src="https://github.com/GSWcomputer.png" width="100px;" alt="Gilliardson"/></td>
    <td>
      <strong>Gilliardson</strong><br>
      Administrador de Redes & Desenvolvedor Python. <br>
      Sou um desenvolvedor focado em transformar desafios complexos em ferramentas produtivas. Com background em Administração de Redes e Cybersecurity, aplico rigor técnico e boas práticas de arquitetura em cada linha de código.
      
      📫 Conecte-se comigo:

LinkedIn: www.linkedin.com/in/gilliardson-swy
Email: gilliardson.swy@gmail.com

"Transformando linhas de código em produtividade financeira."
    </td>
  </tr>
</table>


