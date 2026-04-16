# Raízes do Nordeste

Projeto Front-End demonstrativo para a atividade prática da trilha de Front-End, baseado no estudo de caso da rede "Raízes do Nordeste".

## O que já está implementado

- Fluxo de cadastro e autenticação com dados mockados.
- Seleção de unidade, canal de atendimento e modalidade do pedido.
- Cardápio dinâmico por unidade.
- Carrinho com subtotal, desconto promocional, frete e pontos.
- Pagamento com integração externa simulada.
- Acompanhamento do status do pedido.
- Programa de fidelidade com recompensas.
- Tela de perfil com controles de dados e privacidade.
- Painel administrativo com campanhas, pedidos e indicadores.

## Estrutura

```text
raizes-do-nordeste/
├── index.html
├── cadastro.html
├── unidades.html
├── cardapio.html
├── carrinho.html
├── pagamento.html
├── pedido.html
├── fidelidade.html
├── perfil.html
├── admin.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   ├── app.js
│   ├── mock.js
│   ├── auth.js
│   ├── unidades.js
│   ├── cardapio.js
│   ├── carrinho.js
│   ├── pagamento.js
│   ├── pedido.js
│   ├── fidelidade.js
│   └── admin.js
├── docs/
│   ├── diagramas-atividade.md
│   └── plano-de-testes.md
└── README.md
```

## Como executar

1. Abra o projeto em um servidor local simples.
2. Inicie pela página `index.html`.
3. Para login rápido na plataforma, use:

```text
Cliente:
E-mail: danilo@demo.com
Senha: 123456

Admin:
E-mail: admin@demo.com
Senha: admin123
```

## Checklist para a entrega da atividade

- Publicar a aplicação em link público funcional.
- Disponibilizar o repositório em modo público.
- Produzir no PDF final:
  - Introdução e objetivos.
  - Requisitos funcionais e não funcionais.
  - Diagrama de casos de uso.
  - Descrição de uma feature com fluxo principal.
  - Jornada do usuário.
  - Wireframes mobile e desktop.
  - Evidências de LGPD na interface.
  - Plano de testes com pelo menos 10 cenários.
  - Conclusão técnica.

## Documentos de apoio já preparados

- `docs/diagramas-atividade.md`: diagrama de casos de uso, descrição da feature e jornada do usuário.
- `docs/plano-de-testes.md`: seção 7 com bateria de testes pronta para o PDF final.

## Observação importante

Este projeto usa `localStorage` e dados mockados para representar os fluxos da plataforma sem depender de back-end real ou gateway de pagamento real.
