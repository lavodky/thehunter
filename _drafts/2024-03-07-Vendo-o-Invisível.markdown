---
layout: post
title:  "Vendo o Invisível"
tagline: Single Page
date: 2016-04-11 12:51
categories: [Graphic Design]
tags: [Endpoint Security, XDR]
image: /portfolio/port1.jpg
---

Como o Falcon Exposure Management ajuda as equipes de segurança a reduzir o risco de extensões de navegador


À medida que a produtividade da força de trabalho depende cada vez mais de aplicações baseadas na web, os navegadores se tornaram portas essenciais para a "economia da conectividade". Segundo dados recentes, 93% do tráfego de internet em desktops em 2023 passou por quatro navegadores populares.

Com suas diversas funcionalidades e usos, os navegadores são as aplicações de desktop mais utilizadas. Para expandir ainda mais sua utilidade, é comum instalar e usar extensões de navegador: pequenos módulos de software que aprimoram e personalizam a funcionalidade dos navegadores. Os usuários as instalam para adaptar a experiência de navegação às suas necessidades e preferências, variando de bloqueadores de anúncios e ferramentas de segurança a melhoradores de produtividade e assistentes de compras. No entanto, como as aplicações normais, as extensões de navegador podem se tornar fontes de malware e ser exploradas por atacantes, o que significa que carregam riscos significativos.

Neste blog, exploraremos por que as extensões de navegador são particularmente atraentes para atores de ameaças e como as novas capacidades do CrowdStrike Falcon® Exposure Management podem ajudar as equipes de segurança a detectar e avaliar esses riscos para se manter à frente dos atacantes.
O Que Torna as Extensões de Navegador Problemáticas

Quando um usuário final instala uma extensão de navegador, as permissões concedidas abrem a porta para um mundo de possibilidades — e vulnerabilidades. Dependendo do que é permitido, essas extensões podem acessar um verdadeiro tesouro de informações: desde o tráfego da web e credenciais salvas até cookies de sessão, dados da área de transferência e além. Embora as extensões legítimas muitas vezes necessitem dessas permissões para operar eficazmente, nas mãos erradas, essas permissões podem se tornar ferramentas de exploração, dando aos maus atores as chaves para dados críticos e informações privadas.

Os dados ricos obtidos por esses meios podem ser subsequentemente transformados em armas e monetizados por criminosos. Por exemplo, usando dados privilegiados, eles podem elaborar e-mails de phishing mais convincentes ou usar credenciais coletadas para realizar ataques baseados em identidade.

A análise do CrowdStrike sobre extensões de navegador em nossos ambientes de produção indica que bem mais da metade delas requerem o que pode ser considerado permissões excessivas. Isso significa que essas permissões carregam riscos fortes, pois podem permitir que os atores de ameaça vejam todo o tráfego da web ou manipulem guias do navegador.

Além disso, como as extensões estão incorporadas nas aplicações do navegador e não criam eventos de início de processo, elas podem ser mais difíceis de detectar do que as aplicações de desktop comuns, permitindo que os atores de ameaça ofusquem e persistam em suas atividades maliciosas.
Como os Adversários Desdobram Extensões Maliciosas

As extensões podem ser relativamente fáceis de desenvolver, mas geralmente não vêm com um navegador web por padrão. Portanto, o ato de desdobrar extensões maliciosas nos navegadores das vítimas é uma parte importante da tática. Os adversários alcançam isso empregando várias táticas.

Um método comum é listar extensões enganosas nas lojas de navegadores. A enganação pode ser alcançada de várias maneiras, incluindo imitar nomes de produtos de fornecedores legítimos conhecidos ou publicar extensões com finalidades populares de produtividade.

Outra tática popular é a tomada de posse, onde os atores de ameaça compram ou de outra forma assumem extensões de navegador previamente legítimas que já têm uma base de usuários e distribuem atualizações maliciosas para comprometer sistemas-alvo.

O método mais perigoso talvez seja o "sideloading", que envolve instalar extensões de navegador de fontes fora da loja oficial da web, adicionando diretamente os arquivos da extensão. Esse método contorna as proteções usuais que vêm com as lojas de navegadores. Os atacantes exploram esse método ao empacotar extensões maliciosas com aplicações de software aparentemente legítimas. Quando os usuários instalam essas aplicações, as extensões ocultas também são instaladas, concedendo aos atacantes acesso ao navegador e dados dos usuários.

Mesmo com o método da loja da web, as extensões de navegador podem expandir suas permissões após a instalação e baixar cargas adicionais maliciosas. Esta é uma tática popular de ofuscação onde os adversários publicam extensões nas lojas de navegadores com requisitos mínimos de permissão inicial, mas expandem sua presença com intenções prejudiciais. Um exemplo foi a notória extensão maliciosa PDF Toolbox, que baixava cargas adicionais após a instalação para melhorar suas capacidades e persistência.
