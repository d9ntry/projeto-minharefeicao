# Projeto de Software - Minha Refeição (N1 - Entrega 1)

**Universidade Presbiteriana Mackenzie**  
**Disciplina:** Projeto de Software  
**Professora:** Ana Claudia Rossi  
**Aluno:** Lucas Oliveira | **RA:** 10736078  

---

## 1. Distribuição de Responsabilidades
- **Lucas Oliveira (RA: 10736078):** Análise de requisitos, protótipo Desktop e Mobile, identificação das classes candidatas de domínio, documentação do storyboard e gravação do vídeo explicativo.

---

## 2. Vídeo Explicativo
[Insira aqui o link do seu vídeo do YouTube ou Google Drive]

---

## 3. Storyboard e Sequência de Navegação
<img width="1599" height="835" alt="{01FED9C5-6F5F-4603-B0E2-98C883FE29A2}" src="https://github.com/user-attachments/assets/e2429ac0-d49d-4306-ad0d-82981137d1c4" />
<img width="1600" height="832" alt="{8F9B8330-9A09-4929-84C2-E4262D1FA2FD}" src="https://github.com/user-attachments/assets/e8150f53-2cfc-41e3-b20b-dc34fda28c7c" />
<img width="1596" height="833" alt="{4F2E11D0-155F-4F26-B730-979EA17B9EC0}" src="https://github.com/user-attachments/assets/25fa0c91-0a64-4afc-8111-104c1916fc60" />
<img width="1596" height="831" alt="{DDC56536-2F17-404A-AC3A-231054F64EA2}" src="https://github.com/user-attachments/assets/8b0a7be5-49c9-4c4c-a8d9-6cb3dc1cc0ea" />
<img width="1596" height="827" alt="{F05F4E7C-2EE8-4DC1-9D08-41198B0F438D}" src="https://github.com/user-attachments/assets/a35a603c-6174-46f8-b37f-9105e8f08b17" />
<img width="1594" height="830" alt="{586BB472-8B6B-4448-94EF-FBA56D8DC32E}" src="https://github.com/user-attachments/assets/9d2ae8e4-ca2e-42a7-a507-1f467de1e15d" />
<img width="1593" height="831" alt="{83BC5CE8-8D09-436E-B9D9-E7FACB99178F}" src="https://github.com/user-attachments/assets/942f3561-869d-4015-a68c-d0ed9a1f5860" />
<img width="1591" height="830" alt="{61D1359A-ACF6-451E-B305-38B9D71F01DD}" src="https://github.com/user-attachments/assets/cc51cf89-267d-41c2-9b51-9a8436a57ea1" />
<img width="1594" height="828" alt="{0DC85F82-3461-4FC0-BC47-B73361AFABDD}" src="https://github.com/user-attachments/assets/0614be12-8677-41d1-9b8b-31cc36f6507a" />



---

## 4. Lista de Classes Candidatas Identificadas

| Classe | Responsabilidade / Descrição |
| :--- | :--- |
| **Assinante** | Armazena os dados do cliente (celular, código de verificação SMS). |
| **PlanoAssinatura** | Define os planos (Semanal, 15 dias, 20 dias, valores e limites de refeições). |
| **PreferenciaAlimentar** | Guarda as restrições selecionadas (Tradicional, Vegetariana, Sem Lactose). |
| **Refeicao** | Representa os pratos, acompanhamentos e sobremesas do cardápio. |
| **PedidoPlano** | Controla os itens selecionados e valida a quantidade limite do plano contratado. |
| **EnderecoEntrega** | Dados do local de entrega (Rua, Número, CEP, Bairro). |
| **PagamentoCartao** | Dados da transação (Número do cartão, validade, CVV). |
| **Assinatura** | Gerencia o status do serviço ("Ativa" ou "Aguardando Pagamento") e guarda o número do protocolo gerado. |
