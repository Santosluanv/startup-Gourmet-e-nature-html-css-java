# 🍫 Gourmet & Nature — Sabores Especiais

Landing page e catálogo digital desenvolvido para a **Gourmet & Nature**, uma doceria gourmet localizada em Planaltina – DF. O projeto conta com carrinho de compras interativo e envio direto de pedidos via WhatsApp.

---

## ✨ Funcionalidades

- **Cardápio Digital:** Exibição de sobremesas com descrição, fotos e preços (*Ninho com Nutella*, *Chocolate branco e Oreo* e *Nutella e uva*).
- **Carrinho Lateral (Drawer):** Adição, remoção e controle de quantidade de itens em tempo real.
- **Cálculo Automático:** Soma dinâmica do subtotal e acréscimo automático da taxa de entrega (R\$ 5,00) ou opção de retirada no local.
- **Checkout via WhatsApp:** Formulário completo (nome, telefone, endereço, forma de pagamento e observações) que gera uma mensagem formatada para envio direto ao atendimento.
- **Design Luxo Minimalista:** Identidade visual em preto (`#090909`) e dourado (`#D4AF37`), totalmente responsiva para celulares, tablets e desktops.

---

## 🎨 Identidade Visual e Tecnologias

- **HTML5:** Estruturação semântica da página e do formulário de checkout.
- **CSS3 (`style.css`):**
  - Variáveis CSS (`:root`) para padronização de cores, espaçamentos e animações.
  - Layout responsivo com **CSS Grid**, **Flexbox** e `clamp()` para tipografia fluida.
  - Suporte a acessibilidade (`prefers-reduced-motion` e `:focus-visible`).
- **JavaScript:** Manipulação do DOM, gerenciamento do estado do carrinho e integração com a API do WhatsApp.
- **Google Fonts:** Tipografia combinando *Playfair Display* (títulos) e *Montserrat* (textos).

---

## 📁 Estrutura de Arquivos

```text
├── index.html      # Estrutura principal da página e do carrinho
├── style.css       # Folha de estilos (identidade preto e dourado)
├── script.js       # Lógica do carrinho e envio para o WhatsApp
└── README.md       # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd gourmet-nature
   ```
3. Abra o arquivo `index.html` no seu navegador ou utilize uma extensão como o **Live Server** no VS Code.

---

## 📍 Informações do Negócio

- **Localização:** Estância, Planaltina – DF
- **Atendimento:** Das 8h às 18h
- **Formas de Pagamento:** Pix, dinheiro, cartão ou link de pagamento

---

© **Gourmet & Nature**. Todos os direitos reservados.
