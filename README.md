# Merco — Landing Page

Landing page criativa e responsiva para a Merco, uma agência de software focada em produto digital. Reúne hero com métricas, seções de serviços, cases, processo de trabalho e CTA final, tudo em uma única página HTML+CSS sem dependências externas além das fontes do Google Fonts.

## Stack e decisões
- **HTML5 + CSS puro**: estrutura sem frameworks para facilitar leitura e customização rápida.
- **Tipografias**: Space Grotesk e Inter via Google Fonts para dar personalidade e boa legibilidade.
- **Layout responsivo**: grid fluido, `clamp` e ajustes em breakpoints (900px e 600px) garantem boa experiência em desktops e mobile.
- **Tema futurista**: cores escuras com gradientes neon reforçam o posicionamento premium da Merco.

## Estrutura
```
/
├── index.html  # Landing page completa com estilos embutidos
└── README.md   # Este documento
```

- **Hero**: navegação, headline, CTAs, métricas e cards visuais com roadmap/stack.
- **Serviços** (`#servicos`): apresenta discovery, squads dedicadas e suporte contínuo.
- **Cases** (`#cases`): três estudos com impacto, tempo e alcance.
- **Processo** (`#processo`): passos numerados destacando imersão, blueprint e sprints.
- **CTA final** (`#contato`): convite para diagnóstico rápido com botões centrais.

## Como usar
1. Abra `index.html` diretamente no navegador ou sirva com qualquer servidor estático.
2. Ajuste textos, cores ou métricas editando a própria página (os estilos estão dentro da tag `<style>`).
3. Opcional: extraia o CSS para um arquivo separado caso deseje evolução maior ou integração com frameworks.

## Personalização sugerida
- Substitua logos/nomes de clientes pelos seus cases reais.
- Conecte os botões de CTA a formulários (Typeform, HubSpot, etc.) ou âncoras internas.
- Atualize contatos do rodapé e informe analytics/código de tracking, se necessário.

## Contato
Se precisar de extensões (por exemplo, animações extras ou integração com backend), basta abrir um issue ou adaptar o HTML conforme seu fluxo.
