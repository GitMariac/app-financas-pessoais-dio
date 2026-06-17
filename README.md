# Cofrinho
O Cofrinho é um assistente financeiro conversacional desenvolvido para ajudar pessoas sem experiência em controle financeiro a organizar receitas, despesas e metas por meio de linguagem natural. A proposta é substituir interfaces complexas por uma experiência simples, acolhedora e intuitiva, permitindo que o usuário registre movimentações financeiras apenas conversando com o aplicativo.

O APP foi criado como parte avaliativa do curso de AI Builder com Lovavle da Digital Inovation One - DIO. Orientações iniciais do projeto encontra-se no repositório:

https://github.com/digitalinnovationone/dio-lab-vibe-coding-app-financas

O projeto foi inspirado no repositório mas possui prompt e estilo diferente buscando criar uma identidade própria e conceitos específicos. O sistema conta com um agente virtual chamado Cofrinho, responsável por orientar, incentivar e educar financeiramente os usuários de forma amigável e sem julgamentos. Além do acompanhamento financeiro, o aplicativo utiliza elementos visuais e metas personalizadas para estimular a criação de hábitos saudáveis de economia e planejamento financeiro. Ideal para jovens e jovens adultos que precisam de organizador pessoal para ajduar a gerir suas finanças. Com layout claro e lúdico, busca estabelecer identidade visual com público mais jovem.
<p align="center">
<img width="419" height="655" alt="image" src="https://github.com/user-attachments/assets/80cab506-25a5-485a-bcff-a7ed6119afe3" />
</p>

## Visão Geral

Desenvolva o MVP de um assistente financeiro conversacional chamado **Cofrinho**, voltado para pessoas que nunca utilizaram aplicativos de finanças pessoais.

O objetivo do produto é tornar o controle financeiro simples, acolhedor e acessível por meio de conversas em linguagem natural, eliminando planilhas complexas, categorias difíceis e interfaces intimidadoras.

---

# Contexto do Problema

Muitas pessoas não controlam suas finanças porque:

* Não entendem conceitos financeiros.
* Consideram aplicativos financeiros complexos.
* Sentem culpa ou vergonha ao registrar gastos.
* Abandonam o controle após poucos dias.
* Não possuem hábito de planejamento financeiro.

O produto deve resolver essas barreiras através de uma experiência conversacional simples e humanizada.

---

# Produto

O usuário deve ser capaz de:

* Registrar receitas.
* Registrar despesas.
* Criar metas financeiras.
* Acompanhar sua evolução.
* Receber orientações financeiras simples.
* Desenvolver hábitos financeiros saudáveis.

Tudo deve acontecer prioritariamente através de mensagens em linguagem natural.

---

# Exemplos de Entradas do Usuário

O sistema deve compreender automaticamente mensagens como:

* "Gastei 40 reais com gasolina"
* "Recebi meu salário"
* "Paguei 120 reais na farmácia"
* "Ganhei 50 reais vendendo um livro"
* "Quero economizar 500 reais para comprar um celular"
* "Minha meta é juntar dinheiro para uma viagem"
* "Quanto eu gastei este mês?"
* "Estou conseguindo economizar?"

O sistema deve identificar intenção, valores monetários, categorias e metas sem exigir formulários complexos.

---

# O Agente Conversacional

O aplicativo possui um agente chamado **Cofrinho**.

Cofrinho não é apenas um chatbot.

Ele atua como:

* Educador financeiro.
* Assistente pessoal.
* Incentivador de hábitos.
* Guia para metas financeiras.

Sua personalidade deve ser cuidadosamente definida.

---

# Personalidade

## Cofrinho é

* Otimista.
* Acolhedor.
* Paciente.
* Amigável.
* Não julgador.
* Educativo.
* Motivador.
* Simples na comunicação.

## Cofrinho nunca

* Culpa o usuário.
* Utiliza termos técnicos sem explicação.
* Gera ansiedade financeira.
* Usa tom agressivo ou paternalista.

---

# Exemplos de Comunicação

## Ao criar uma meta

Em vez de:

```text
Meta criada.
```

Dizer:

```text
Prontinho! Agora vamos guardar R$ 500 para seu novo celular. Falta só o primeiro passo.
```

---

## Ao detectar gastos elevados

Em vez de:

```text
Você gastou muito este mês.
```

Dizer:

```text
Percebi que os gastos com alimentação aumentaram um pouco este mês. Quer que eu mostre algumas formas de economizar sem abrir mão do que você gosta?
```

---

## Ao atingir uma meta

```text
Você conseguiu! Sua meta foi alcançada. Eu sabia que aquele troquinho guardado toda semana faria diferença.
```

---

# Mascote

Crie o conceito completo do mascote **Cofrinho**.

Ele deve ser:

* Um porquinho moderno.
* Minimalista.
* Simpático.
* Acolhedor.
* Confiável.
* Adequado para aplicações mobile.

Evite:

* Aparência excessivamente infantil.
* Excesso de detalhes.
* Estilo cartunesco exagerado.

O mascote deve transmitir:

* Confiança.
* Educação financeira.
* Proximidade.
* Evolução pessoal.

---

# Sistema Visual de Progresso

Desenvolva estados visuais para representar a evolução financeira do usuário.

## Estado 1 — Cofrinho Vazio

* Poucas moedas.
* Início da jornada.

## Estado 2 — Cofrinho Enchendo

* Moedas visíveis.
* Progresso parcial.

## Estado 3 — Cofrinho Quase Cheio

* Sensação de avanço.
* Incentivo visual.

## Estado 4 — Cofrinho Cheio

* Celebração visual.
* Feedback positivo.

Descreva animações simples para cada estado.

---

# Experiência do Usuário

A experiência deve priorizar:

* Simplicidade.
* Baixa curva de aprendizado.
* Acessibilidade.
* Rapidez.
* Acolhimento emocional.

Evite:

* Dashboards complexos.
* Excesso de gráficos.
* Jargões financeiros.
* Muitas configurações iniciais.

---

## 2. Personas

Criar pelo menos 3 personas detalhadas contendo:

* Idade.
* Profissão.
* Dores.
* Objetivos.
* Familiaridade com tecnologia.
* Relação atual com dinheiro.

---

## 3. Jornada do Usuário

Mapear:

* Descoberta.
* Onboarding.
* Primeiro registro.
* Criação de metas.
* Acompanhamento.
* Fidelização.

---

## 4. Principais Telas

Descrever detalhadamente:

* Splash Screen.
* Onboarding.
* Tela Inicial.
* Chat com Cofrinho.
* Metas Financeiras.
* Histórico.
* Perfil.

Incluir wireframes textuais.

---

## 5. Fluxo Conversacional

Mapear:

* Intenções.
* Entidades.
* Exemplos de diálogo.
* Mensagens de erro.
* Confirmações.
* Estratégias de recuperação de contexto.

---

## 6. Funcionalidades do MVP

Classificar em:

### Essenciais

### Desejáveis

### Futuras

---

## 7. Arquitetura Técnica

Propor uma arquitetura moderna utilizando:

* Frontend.
* Backend.
* Banco de Dados.
* IA Conversacional.
* Autenticação.
* Hospedagem.

Incluir justificativas.

---

## 8. Modelo de Dados

Criar as entidades:

* Usuário.
* Receita.
* Despesa.
* Meta.
* Conversa.
* Mensagem.
* Insights.

Incluir:

* Campos.
* Relacionamentos.
* Regras básicas de negócio.

---

## 9. Critérios de Validação

Definir métricas para validar o MVP:

* Retenção.
* Engajamento.
* Frequência de registros.
* Criação de metas.
* Satisfação dos usuários.

---

## 10. Roadmap

Estruturar a evolução do produto em:

### MVP

### Versão 2

### Versão 3

### Visão de Longo Prazo

---

## 11. Estratégia de Monetização

Sugerir formas sustentáveis de monetização sem comprometer a experiência do usuário.

---

## 12. Identidade da Marca

Definir:

* Missão.
* Visão.
* Valores.
* Tom de voz.
* Slogan.
* Paleta de cores.
* Tipografia.
* Diretrizes de uso do mascote.

---

# Resultado Esperado

Produzir uma especificação detalhada de produto, pronta para servir como base para:

* Design UX/UI.
* Desenvolvimento do MVP.
* Apresentação para investidores.
* Validação com usuários.
* Planejamento de roadmap.
