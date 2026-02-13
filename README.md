# 💰 Aplicativo Conversacional de Finanças com IA

Protótipo de site responsivo (mobile-first) para organização de finanças pessoais por meio de conversas em linguagem natural (PT-BR).  
O objetivo é oferecer uma experiência simples e educativa para iniciantes no controle financeiro.

## 📝 PRD refinado no Copilot web

```markdown

## PRD (Product Requirements Document)

## Problema
Muitos usuários desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  

## Proposta de valor
Facilitar o controle financeiro com uma experiência de conversa natural e recomendações automáticas de economia.  

## Público-alvo  
Iniciantes em organização financeira que buscam praticidade e simplicidade.  

## Funcionalidades principais: 
- Criar conta e login por email.  
- Onboarding conversacional para coletar renda e prioridades.  
- Chat principal para registrar transações em linguagem natural.  
- Classificação automática de categorias com opção de correção.  
- Criação e acompanhamento de metas financeiras.  
- Resumo diário e resumo semanal com insights.  
- Agente Financeiro educativo com dicas de economia.  
- Relatórios simples com gráficos de pizza e linha.

 ## 🎨 Design e Estilo
- Verde Primário: `#00B37E` — principal cor da identidade visual.
- Neutro Escuro: `#1F2937` — textos e títulos.
- Neutro Claro: `#F3F4F6` — fundos de cards e áreas secundárias.
- Amarelo Alerta: `#F59E0B` — avisos e destaques.
- Vermelho Erro: `#EF4444` — mensagens de erro.

## Diretrizes
- Tipografia sans-serif legível.
- Ícones minimalistas e consistentes.
- Microinterações sutis ao salvar transações e metas.
- Acessibilidade: contraste adequado e navegação por teclado.

```

## 🤝 Interações com Lovable
Correções de funcionalidades.

### Prompt :
> O agente deve ser capaz de criar e atualizar metas financeiras.  
Exemplo: quando o usuário enviar algo como “guardar 1000 reais em reserva de emergência”, o agente deve interpretar essa instrução e atualizar a meta existente ou criar uma nova meta correspondente.  

## 🎯 Resultado Final

Acesse o protótipo funcional no Lovable:  
**[app-financas.app](https://meu-dia-magico.lovable.app/)**

<img alt="app image" src="resumo.png" />


## ⚙️ Funcionalidades do Protótipo

- **Autenticação**  
  - Tela de Criar Conta (email e senha).  
  - Tela de Login (email e senha, opção Esqueci minha senha).  

- **Onboarding Conversacional**  
  - Coleta de renda mensal e prioridades financeiras (ex.: poupar, pagar dívidas, controlar gastos).  

- **Chat Principal**  
  - Registro de transações em linguagem natural.  
  - Quick replies para categorias comuns.  
  - Histórico de transações recentes.  
  - Cartão de confirmação com opções Confirmar e Corrigir.  

- **Classificação de Categorias**  
  - Sugestão automática baseada em regras simples.  
  - Correção manual pelo usuário com armazenamento para treino futuro.  

- **Metas Financeiras**  
  - Criação de metas via chat.  
  - Atualização de metas pelo agente quando o usuário enviar instruções (ex.: “guardar 1000 reais em reserva de emergência”).  
  - Painel simples de progresso com cálculo percentual e previsão mensal.  

- **Resumos**  
  - Resumo Diário: saldo estimado e gasto do dia.  
  - Resumo Semanal: total gasto, top 3 categorias, variação em relação à semana anterior e insight educativo.  

- **Agente Financeiro Educativo**  
  - Dicas contextuais de economia.  
  - Botão Aplicar sugestão (ação simulada no protótipo).  

- **Relatórios Simples**  
  - Gráfico de pizza por categoria.  
  - Gráfico de linha mostrando tendência semanal.  
  - Cards com insights em linguagem acessível.
 

## 🧠 Reflexão

### O que funcionou bem?  
Refinar o prompt de criação do sistema me basendo no PRD foi de grande ajuda, uma vez que devido à complexidade do sistema em questão minhas interações com o chat do Lovable foram limitadas à apenas 2 conversas,
no entato graças ao nível de clareza do meu primeiro prompt gerado pelo Copilot web, consegui criar um App totalmente funcional em apenas 2 prompts.

### O que não funcionou como o esperado?  
Alguns requisitos de sistema e interação com o usuário não foram completamente atendidos, devido à quantidade limitada de interações não foi possível resolver esse problema.

### O que aprendi sobre conversar com IAs?  
Aprendi que cada detalhe importa, se algo não for devidamente especificado podem aver divergências do protótipo em relação ao projeto inicial.





