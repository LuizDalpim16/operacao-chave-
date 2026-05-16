# 🔑 KeyCash

Painel financeiro pessoal para controle de investimentos, metas, gastos e vencimentos.
Desenvolvido como aplicativo web único (single-page), sem dependências de servidor.

**🌐 Acesso online:** [luizdalpim16.github.io/operacao-chave-](https://luizdalpim16.github.io/operacao-chave-)

---

## 👤 Contas disponíveis

### 🔒 Conta Pessoal — Luiz Dalpim
Conta privada com dados reais. Acesso restrito ao titular.

---

### 🧪 Conta de Demonstração — Usuário Teste

Conta pública com dados de exemplo para explorar todas as funcionalidades do app.

| Campo | Valor |
|-------|-------|
| **Usuário** | Usuário Teste |
| **Senha** | `Teste@2025` |
| **Salário exemplo** | R$ 4.500,00 |
| **Aporte mensal** | R$ 800,00 |

#### Dados pré-carregados:

**💼 Investimentos**
| Fundo | Valor |
|-------|-------|
| CDB 100% CDI | R$ 3.200,00 |
| Fundo Ouro | R$ 1.850,00 |
| Multimercado | R$ 1.150,00 |
| **Total** | **R$ 6.200,00** |

**📈 Histórico (6 meses)**
| Mês | Aporte | Total |
|-----|--------|-------|
| Nov/2024 | R$ 600 | R$ 3.200 |
| Dez/2024 | R$ 700 | R$ 3.850 |
| Jan/2025 | R$ 800 | R$ 4.620 |
| Fev/2025 | R$ 800 | R$ 5.240 |
| Mar/2025 | R$ 800 | R$ 5.760 |
| Abr/2025 | R$ 800 | R$ 6.200 |

**💸 Gastos de maio/2025**
| Descrição | Categoria | Valor |
|-----------|-----------|-------|
| Supermercado | 🍔 Alimentação | R$ 380,00 |
| Restaurante | 🍔 Alimentação | R$ 95,00 |
| Combustível | 🚗 Transporte | R$ 180,00 |
| Netflix | 🎮 Lazer | R$ 55,90 |
| Farmácia | 🏥 Saúde | R$ 67,50 |
| Curso online | 📚 Educação | R$ 120,00 |

**📅 Contas cadastradas**
| Conta | Valor | Dia | Status |
|-------|-------|-----|--------|
| Internet | R$ 99,90 | Dia 10 | Pendente |
| Energia | R$ 210,00 | Dia 12 | Pendente |
| Academia | R$ 89,90 | Dia 5 | ✓ Pago |
| Seguro carro | R$ 185,00 | Dia 20 | Pendente |

---

## 🚀 Funcionalidades

| # | Feature | Descrição |
|---|---------|-----------|
| 1 | **📊 Painel** | Patrimônio, investimentos, orçamento e metas |
| 2 | **🎯 Metas** | Prioridade por drag-and-drop, simulador de aporte e aposentadoria |
| 3 | **📈 Histórico** | Gráfico CDB + projeção, gráfico comparativo mês a mês, relatório PDF |
| 4 | **💸 Gastos** | Registro por categoria com gráfico de rosca e resumo do mês |
| 5 | **📅 Vencimentos** | Calendário de contas com alertas visuais de prazo |
| 6 | **✅ Regras** | Checklist de disciplina financeira personalizada |
| 7 | **👁️ Privacidade** | Botão para borrar todos os valores monetários |
| 8 | **☁️ Sincronização** | Firebase Realtime Database — dados sincronizados entre dispositivos |
| 9 | **👥 Multiusuário** | Suporte a múltiplas contas com dados isolados por usuário |
| 10 | **🎨 Temas** | 8 temas visuais: Escuro, Claro, Oceano, Floresta, Roxo, Rosa, Rubi e Grafite |

---

## 🎨 Temas disponíveis

| Tema | Estilo |
|------|--------|
| **Escuro** | Padrão — fundo preto, destaque laranja |
| **Claro** | Modo dia — fundo claro, destaque laranja |
| **Oceano** | Fundo azul-marinho, destaque ciano |
| **Floresta** | Fundo verde escuro, destaque verde |
| **Roxo** | Fundo roxo escuro, destaque violeta |
| **Rosa** | Fundo rosa escuro, destaque pink |
| **Rubi** | Fundo vermelho escuro, destaque vermelho |
| **Grafite** | Fundo cinza azulado, destaque laranja |

---

## 🛠️ Tecnologias

- **HTML5 / CSS3 / JavaScript** — sem frameworks
- **[Chart.js](https://www.chartjs.org/)** v4.4.3 — gráficos
- **[Firebase Realtime Database](https://firebase.google.com/)** — sincronização em tempo real
- **localStorage** — cache local para funcionamento offline

---

## 📱 Como usar no iPhone

1. Acesse o link acima no Safari
2. Toque em **Compartilhar → Adicionar à Tela Inicial**
3. O app funciona como se fosse nativo, com ícone na home

---

## 📋 Histórico de atualizações

| Versão | Data | Descrição |
|--------|------|-----------|
| **v3.0** | Mai/2026 | Rebrand para **KeyCash**, correção do seletor de temas, tema Grafite, aparência colapsável no dropdown |
| **v2.0** | Mai/2026 | Multiusuário, FAB lançamentos, gráfico investimentos, avisos configuráveis, regras com exceção |
| **v1.5** | Mai/2026 | Novo design do login, recuperação de senha |
| **v1.0** | 2025 | Temas, menu hambúrguer, login único |

---

*Desenvolvido por Luiz Dalpim · 2026*
