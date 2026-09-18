# WikiAcolhe

**Conhecimento para navegar por dentro e por fora.**

[Acessar o portal](https://wikiacolhe.blubier.chatgpt.site/) · [English below](#english)

O WikiAcolhe é um portal educacional gratuito para pessoas que estão iniciando ou recomeçando sua relação com a internet. Um pequeno robô viajante conduz o visitante por um percurso curto, acolhedor e crítico: observar antes de clicar, formular perguntas melhores, cruzar referências e reconhecer a hora de fazer uma pausa.

## Objetivos

- apoiar a alfabetização e a inclusão digital;
- ensinar pesquisa e verificação básica de informações;
- apresentar a Wikipédia como ponto de partida, não como resposta final;
- incentivar autonomia, pensamento crítico e cuidado durante a navegação;
- oferecer uma experiência acessível, bilíngue e sem coleta de dados.

## Funcionalidades

- percurso inicial em quatro gestos;
- oficina interativa de verificação de uma afirmação;
- pausa respiratória guiada;
- português e inglês na mesma interface;
- progresso guardado somente no dispositivo;
- PWA com funcionamento offline;
- navegação por teclado, foco visível e suporte a leitores de tela;
- layout responsivo para celular, tablet e computador;
- SEO técnico com URL canônica, dados estruturados, `robots.txt` e `sitemap.xml`.

## Privacidade e cuidado

O portal não exige cadastro, não usa rastreadores e não envia o progresso do visitante. O WikiAcolhe é um recurso educativo e reflexivo. Não oferece terapia, diagnóstico ou atendimento de emergência.

## Tecnologia

Projeto estático em HTML, CSS e JavaScript, sem dependências obrigatórias. Para executar localmente, basta servir a pasta `dist` com qualquer servidor HTTP.

## Estrutura

```text
dist/
├── assets/              # ilustração do personagem-guia
├── index.html           # conteúdo, acessibilidade e dados estruturados
├── styles.css           # identidade visual e responsividade
├── footer.css           # apoio institucional
├── app.js               # idioma, progresso e atividades
├── manifest.webmanifest # instalação como aplicativo
├── robots.txt           # orientação aos buscadores
├── sitemap.xml          # mapa público do portal
└── sw.js                # funcionamento offline
```

## Autoria e apoio

Idealizado por **Sidiney Rodrigues** e desenvolvido com apoio de inteligência artificial.

Este projeto nasceu do desejo de ensinar e cuidar. Se ele tocou você, [considere doar diretamente ao Hospital Pequeno Príncipe](https://pequenoprincipe.org.br/doadores/apoie-o-pequeno-principe/). Iniciativa voluntária, independente e sem intermediação financeira.

## Licença

O código está disponível sob a licença MIT. O conteúdo educacional está disponível sob [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.pt-br), com atribuição a Sidiney Rodrigues.

---

## English

**Knowledge to navigate outside and within.**

WikiAcolhe is a free educational portal for people beginning or restarting their relationship with the internet. A small robot traveler guides visitors through four gestures: pause and observe, ask better questions, cross-check references, and know when to step away.

The portal is bilingual, accessible, privacy-friendly, installable and available offline. It requires no account, uses no trackers and stores progress only on the visitor's device. WikiAcolhe is educational and reflective; it does not provide therapy, diagnosis or emergency care.

Created by **Sidiney Rodrigues**. Code: MIT. Educational content: CC BY 4.0.
