# Correções de Acessibilidade – IFVEST

Este documento registra as correções de acessibilidade
identificadas durante as avaliações realizadas com as
ferramentas WAVE e Accessibility Insights for Web, relacionando
cada ajuste aos critérios WCAG correspondentes.

---

## Correções Aplicadas e Critérios WCAG

| Correção aplicada | Critério WCAG relacionado |
|------------------|---------------------------|
| Campos interativos acessíveis por teclado (`tabindex`, `role`, `aria-label`) | 2.1.1 – Teclado<br>4.1.2 – Nome, função, valor |
| Implementação de foco visível com CSS `:focus` | 2.4.7 – Foco visível |
| Ajustes de semântica ARIA (`role="status"`, `role="textbox"`, `aria-hidden`) | 4.1.2 – Nome, função, valor |
| Correção de links com `href="#"` (uso de `preventDefault`, `tabindex="0"`) | 2.4.3 – Ordem de foco |
| Spinner de carregamento com `role="status"` e `aria-label="Carregando"` | 4.1.3 – Mensagens de status |
| Campos ocultos utilizando `hidden` e `aria-hidden="true"` | 1.3.1 – Informação e relações |
| Correção de tabelas com uso de `col` e `scope` em checkboxes | 1.3.1 – Informação e relações |

---

## Observações
- As correções listadas foram avaliadas com base nas diretrizes
  WCAG 2.1.
- A validação dos ajustes considerou navegação por teclado,
  foco visível e semântica adequada para tecnologias assistivas.
- Este documento possui caráter demonstrativo e educacional.
