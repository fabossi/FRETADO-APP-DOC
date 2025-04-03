
## **Sobre o que é esse Aplicativo**

Este aplicativo é uma solução abrangente para serviços de fretado corporativo, projetado para otimizar a experiência de transporte dos funcionários. Ele oferece funcionalidades como agendamento de viagens, rastreamento em tempo real dos ônibus, check-in digital, sistema de alertas personalizáveis, incluindo um modo soneca para viagens de retorno, e uma plataforma de achados e perdidos. O app também inclui recursos de carona compartilhada, alternativas de transporte, feedback e avaliação do serviço, além de um painel dedicado para motoristas. Com foco na eficiência e conveniência, o aplicativo visa melhorar a pontualidade, a comunicação e a satisfação geral dos usuários do serviço de fretado.

## **Como será desenvolvido?**

O aplicativo será desenvolvido utilizando Swift para a versão iOS, garantindo uma experiência nativa e otimizada para dispositivos Apple. Para a versão Android, será utilizada a linguagem *A definir*, proporcionando um desempenho robusto e uma interface fluida para usuários de dispositivos Android. Esta abordagem de desenvolvimento nativo para ambas as plataformas assegurará a melhor experiência possível para todos os usuários, independentemente do sistema operacional de seus smartphones.

# **Usuário (Funcionários)**

## **1. Tela de Login/Registro**
📌 **Objetivo:** Autenticar o usuário e permitir novos registros.

🔹 **Componentes:**
- Campos para **e-mail e senha**.
- Opção de **"Lembrar-me"**.
- Botão **"Esqueci minha senha"**.
- Opção para **registro de novo usuário**.
- Login através de **contas corporativas** (SSO).

---

## **2. Tela de Home (Dashboard)**
📌 **Objetivo:** Centralizar as principais informações e acessos rápidos.

🔹 **Componentes:**
- Exibição do **próximo embarque** (linha, ponto, horário).
- **Botão para check-in digital** (se disponível).
- **Mapa interativo** com a localização atual do ônibus.
- **Widget de clima** para o local de embarque.
- Acesso rápido às funcionalidades:
  - **"Agendar Viagem"** → Direciona para tela de Agendamento Semanal.
  - **"Rastrear Ônibus"** → Direciona para tela de Rastreamento em Tempo Real.
  - **"Histórico de Viagens"** → Direciona para tela de Histórico e Estatísticas.
- Notificações e alertas recentes.
- **Contador de créditos** ou viagens disponíveis (se aplicável).

---

## **3. Tela de Seleção do Ponto de Embarque**
📌 **Objetivo:** Permitir ao usuário definir o ponto onde deseja embarcar.

🔹 **Componentes:**
- **Mapa interativo** com os pontos de embarque disponíveis.
- **Sugestão automática** do ponto mais próximo baseado no endereço cadastrado.
- **Lista de pontos disponíveis** na linha selecionada.
- Opção de **selecionar manualmente** um ponto diferente.
- **Botão "Confirmar Ponto"** para salvar a escolha.
- **Informações sobre acessibilidade** de cada ponto.

---

## **4. Tela de Rastreamento em Tempo Real** (Expandida)
📌 **Objetivo:** Permitir ao usuário acompanhar a localização do ônibus e configurar alarmes de proximidade.

🔹 **Componentes:**
- **Mapa com o trajeto do ônibus** e pontos de parada
- **Localização em tempo real** do ônibus
- **Tempo estimado de chegada ao ponto** do usuário
- Botão para alternar entre **modo mapa e lista de paradas**
- **Informações sobre o trânsito** na rota
- **Notificação de atrasos** ou mudanças de rota
- **Configuração de alarmes de proximidade**:
  - Definir distâncias personalizadas para alertas
  - Opção de vibração ou som para cada alerta
- **Visualização da localização do usuário** em relação ao ônibus

---

## **5. Tela de Check-in Digital** (Expandida)
📌 **Objetivo:** Registrar a presença do usuário no embarque e facilitar o uso do modo soneca.

🔹 **Componentes:**
- **Botão "Realizar Check-in"**, disponível apenas no local e horário correto
- **Confirmação visual e sonora** de check-in realizado
- **Histórico de check-ins anteriores**
- Aviso caso o usuário tente fazer check-in fora do horário
- **QR Code** para confirmação pelo motorista, se necessário
- **Opção de check-in antecipado** (com confirmação no embarque)
- **Ativação do Modo Soneca**:
  - Botão para ativar o modo soneca após o check-in
  - Seleção rápida do ponto de desembarque desejado
  - Configuração do alarme (tempo ou distância antes do destino)

---

## **6. Tela de Alertas e Notificações** (Expandida)
📌 **Objetivo:** Configurar alertas personalizados sobre embarque, viagem e proximidade do ônibus.

🔹 **Componentes:**
- Lista de **alertas configuráveis**:
  - "Me avise X minutos antes do embarque"
  - **Alarmes de distância do ônibus** (ex.: quando o ônibus estiver a 500m, 1km, etc.)
  - Notificações de **proximidade do ônibus** (15, 10 e 5 minutos)
- **Modo Soneca**:
  - Configuração de alarme para despertar próximo ao destino
  - Opções de vibração, som e intensidade do alarme
  - Possibilidade de definir múltiplos pontos de alerta
- Notificações sobre **mudanças de rota ou atraso**
- Botão para ativar/desativar **notificações push**
- **Opções de notificação por e-mail** ou SMS
- **Alertas de manutenção programada** ou alterações no serviço

---

## **7. Tela de Alertas e Notificações**
📌 **Objetivo:** Configurar alertas personalizados sobre embarque e viagem.

🔹 **Componentes:**
- Lista de **alertas configuráveis** (ex.: "Me avise 10 min antes do embarque").
- Notificações sobre:
  - **Proximidade do ônibus** (15, 10 e 5 minutos).
  - **Mudanças de rota ou atraso**.
- Botão para ativar/desativar **notificações push**.
- **Opções de notificação por e-mail** ou SMS.
- **Alertas de manutenção programada** ou alterações no serviço.

---

## **8. Tela de Alternativas de Transporte**
📌 **Objetivo:** Oferecer opções caso o usuário perca o fretado.

🔹 **Componentes:**
- Lista de **outras opções de transporte público** (horários e rotas).
- **Sugestões de caronas** disponíveis na mesma rota.
- Botão para **direcionamento ao Google Maps/Waze** para opções de transporte público.
- **Integração com serviços de ride-sharing** (Uber, 99, etc.).
- **Informações sobre estações de bicicletas compartilhadas** próximas.

---

## **9. Tela de Carona Compartilhada**
📌 **Objetivo:** Facilitar caronas até o ponto de embarque.

🔹 **Componentes:**
- Botões para **"Oferecer Carona"** ou **"Procurar Carona"**.
- Lista de **usuários disponíveis para carona** (nome, local e horário).
- Opção para **enviar solicitação de carona**.
- Chat rápido para combinar detalhes.
- **Sistema de avaliação** para motoristas e passageiros da carona.
- **Mapa de rota** para caronas.

---

## **10. Tela de Histórico e Estatísticas**
📌 **Objetivo:** Exibir dados sobre frequência de uso do fretado.

🔹 **Componentes:**
- Lista de **viagens passadas** com datas e horários.
- Gráfico de **frequência de uso** semanal/mensal.
- Estatísticas sobre **pontualidade e check-ins**.
- **Cálculo de economia** (tempo e dinheiro) comparado a outras opções de transporte.
- **Impacto ambiental positivo** do uso do fretado.

---

## **11. Tela de Feedback e Avaliação**
📌 **Objetivo:** Permitir que o usuário avalie o serviço.

🔹 **Componentes:**
- **Nota do serviço** (1 a 5 estrelas).
- Campo de **comentários** para sugestões e reclamações.
- Botão para **enviar feedback**.
- **Avaliação específica** para motorista, veículo e pontualidade.
- **Opção de feedback anônimo**.

---

## **12. Tela de Perfil e Configurações**
📌 **Objetivo:** Permitir a personalização da conta.

🔹 **Componentes:**
- Dados do usuário (**nome, e-mail, empresa, linha do fretado**).
- **Opção para alterar ponto de embarque**.
- Configurações de **tema, idioma e notificações**.
- Integração com **Google Calendar/Outlook**.
- **Preferências de assento** (se aplicável).
- **Gerenciamento de métodos de pagamento** (se o serviço for pago).

---

## **13. Tela de Suporte e Emergência**
📌 **Objetivo:** Prover assistência rápida em caso de problemas.

🔹 **Componentes:**
- **Botão de emergência** para suporte imediato.
- Lista de **contatos úteis** (RH, segurança, central de transporte).
- FAQ com **respostas para dúvidas comuns**.
- **Chat ao vivo** com suporte (durante horários de operação).
- **Formulário para relatar problemas** específicos.

---

## **14. Tela de Comunidade e Fórum**
📌 **Objetivo:** Criar um espaço para interação entre usuários.

🔹 **Componentes:**
- **Fórum de discussão** para usuários da mesma linha ou empresa.
- **Quadro de avisos** para informações importantes.
- **Seção de dicas** para novos usuários.
- **Espaço para organização de eventos** ou encontros.

---

## **15. Tela de Achados e Perdidos**
📌 **Objetivo:** Facilitar a recuperação de itens perdidos durante as viagens.

🔹 **Componentes:**
- **Lista de itens encontrados** nos ônibus, com descrições e fotos
- **Formulário para registrar um item perdido**:
  - Descrição do item
  - Data e horário aproximados da perda
  - Linha do ônibus onde o item foi perdido
- **Sistema de correspondência** entre itens perdidos e encontrados
- **Chat ou mensagens** para comunicação entre quem perdeu e quem encontrou o item
- **Informações de contato** do setor responsável pelos achados e perdidos
- **Histórico de itens** reclamados pelo usuário

---

# **Motorista**

## **1. Tela de Home do Motorista**
📌 **Objetivo:** Centralizar as principais funções do motorista.

🔹 **Componentes:**
- Lista das **próximas viagens** do dia.
- Acesso rápido a funcionalidades:
  - **Ver passageiros confirmados**.
  - **Iniciar rastreamento da viagem**.
  - **Visualizar rota e paradas**.
- **Resumo do dia** (total de passageiros, quilômetros percorridos).
- **Alertas de manutenção** do veículo.

---

## **2. Tela de Passageiros Confirmados**
📌 **Objetivo:** Monitorar os passageiros que devem embarcar.

🔹 **Componentes:**
- Lista de **passageiros que confirmaram embarque**.
- Indicação de **quem já fez check-in**.
- Botão para **confirmar embarque manualmente**, se necessário.
- **Contagem de assentos** disponíveis/ocupados.
- **Notificações de alterações** de última hora.

---

## **3. Tela de Rastreamento e Rota**
📌 **Objetivo:** Guiar o motorista pelo trajeto correto.

🔹 **Componentes:**
- **Mapa interativo** com a rota e pontos de parada.
- **Ajuste automático de rota** em caso de problemas.
- Notificação sobre **atrasos ou mudanças**.
- **Informações sobre o trânsito** em tempo real.
- **Comunicação direta** com a central de operações.

---

## **4. Tela de Notificações e Alertas**
📌 **Objetivo:** Informar o motorista sobre mudanças na viagem.

🔹 **Componentes:**
- Alertas sobre **alterações de rota**.
- Notificações de **atrasos ou eventos inesperados**.
- **Avisos de segurança** ou condições climáticas.
- **Lembretes de procedimentos** específicos para cada viagem.

---

## **5. Tela de Confirmação de Embarque**
📌 **Objetivo:** Garantir que todos os passageiros embarquem corretamente.

🔹 **Componentes:**
- Lista de **passageiros embarcados**.
- Opção para **marcar ausentes**.
- Botão para **relatar imprevistos**.
- **Scanner de QR Code** para confirmação rápida.
- **Registro de objetos perdidos**.

---

## **6. Tela de Relatórios e Desempenho**
📌 **Objetivo:** Fornecer feedback sobre o desempenho do motorista.

🔹 **Componentes:**
- **Estatísticas de pontualidade**.
- **Avaliações dos passageiros**.
- **Consumo de combustível** e eficiência da rota.
- **Histórico de viagens** realizadas.
- **Sugestões de melhoria** baseadas nos dados coletados.
