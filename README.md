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

LucroMax_Project/
├── app_android/      # Código fonte completo do aplicativo Android
├── backend_python/   # API FastAPI e lógica do motor de cálculo
└── README.md         # Documentação do projeto


📱 Interface & Screenshots

Conheça a interface do LucroMax. O sistema foi desenhado para ser discreto, funcional e informativo, garantindo que o motorista tenha os dados necessários sem perder o foco na condução.

👨‍💻 Sobre Mim
https://github.com/user-attachments/assets/0ccfcd8e-3139-4781-b96d-a102680c3793 
https://github.com/user-attachments/assets/5dcf87f8-264a-4b62-af77-d99566dca022 
https://github.com/user-attachments/assets/27eed3c2-b906-4bb5-be5f-4071c567b235
https://github.com/user-attachments/assets/6125e901-5cb3-453f-bfc3-4214713ac45b
https://github.com/user-attachments/assets/8afdacdd-75cc-4493-8736-f6112cd3924a
https://github.com/user-attachments/assets/46b459e9-4c1a-4b9e-9d5a-d55398eafc9c
https://github.com/user-attachments/assets/6a721780-2cf4-4422-ae9e-181e42d35c03
https://github.com/user-attachments/assets/11ca6b6a-60d2-429e-a7e1-33146cb7a7ee
https://github.com/user-attachments/assets/e04a1157-347a-40f3-ac9d-52b721ce3aa8

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


