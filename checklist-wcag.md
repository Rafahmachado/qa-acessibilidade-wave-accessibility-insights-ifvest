# Checklist de Acessibilidade – WCAG 2.1  
Plataforma: IFVEST  
Ferramentas: WAVE | Accessibility Insights for Web  
Responsável: Rafaela Machado  

Este checklist consolida os critérios WCAG avaliados,
o status de conformidade e as evidências associadas,
garantindo rastreabilidade dos testes de acessibilidade.

---

## Legenda de Status
- ✅ Conforme
- ⚠️ Parcialmente conforme
- ❌ Não conforme
- 🔄 Correção sugerida

---

## 1. Perceptível

### 1.1 Alternativas Textuais
| Critério | Descrição | Status | Páginas | Evidência |
|--------|-----------|--------|---------|-----------|
| 1.1.1 | Texto alternativo para imagens | ⚠️ | Login, Cadastro | `login/wave/evidencias/` |

### 1.3 Adaptável
| Critério | Descrição | Status | Páginas | Evidência |
|--------|-----------|--------|---------|-----------|
| 1.3.1 | Informação e relações | ❌ | Login, Simulados | `correcoes-acessibilidade.md` |

---

## 2. Operável

### 2.1 Acessível por Teclado
| Critério | Descrição | Status | Páginas | Evidência |
|--------|-----------|--------|---------|-----------|
| 2.1.1 | Teclado | ⚠️ | Login, Cadastro | `accessibility-insights/evidencias/` |

### 2.4 Navegável
| Critério | Descrição | Status | Páginas | Evidência |
|--------|-----------|--------|---------|-----------|
| 2.4.3 | Ordem do foco | ❌ | Simulados | `simulados/analise-simulados.md` |
| 2.4.7 | Foco visível | ❌ | Login, Quiz | `login/accessibility-insights/evidencias/` |

---

## 3. Compreensível

### 3.3 Assistência à Entrada de Dados
| Critério | Descrição | Status | Páginas | Evidência |
|--------|-----------|--------|---------|-----------|
| 3.3.1 | Identificação de erros | ⚠️ | Cadastro | `cadastro/analise-cadastro.md` |

---

## 4. Robusto

### 4.1 Compatível
| Critério | Descrição | Status | Páginas | Evidência |
|--------|-----------|--------|---------|-----------|
| 4.1.2 | Nome, função, valor | ❌ | Login, Flashcards | `correcoes-acessibilidade.md` |
| 4.1.3 | Mensagens de status | ⚠️ | Simulados | `simulados/analise-simulados.md` |

---

## Observações Gerais
- Avaliações realizadas com ferramentas de verificação
  automatizada assistida (WAVE e Accessibility Insights),
  complementadas por análise manual.
- O status dos critérios pode ser atualizado conforme
  novas correções sejam aplicadas.
