Objetivo Principal: Criar um website visualmente impressionante, moderno, intuitivo e educativo que explique de forma abrangente os conceitos de Fundamentos de Redes de Computadores. O conteúdo deve ser baseado nos materiais de aula fornecidos (CP1 a CP6) e, quando aplicável, fazer referência a exemplos práticos dos testes e do trabalho prático.

Público-Alvo: Estudantes da disciplina de Fundamentos de Redes de Computadores.

Requisitos de Conteúdo e Estrutura:

Organização Lógica e Intuitiva:

O website deve ter uma estrutura de navegação clara (ex: menu lateral ou superior) que reflita a organização da matéria, idealmente seguindo a progressão das aulas (Modelo OSI/TCP-IP, Camada Física, Ligação de Dados, MAC, Rede, etc.).
Cada tópico principal deve ser uma secção ou página distinta.
Dentro de cada secção, os sub-tópicos devem ser apresentados de forma hierárquica e fácil de seguir.
Explicações Claras e Didáticas (Estilo Feynman):

Para cada conceito fundamental, fornecer uma explicação simples, clara e concisa, como se estivesse a ser explicado a alguém com pouco conhecimento prévio sobre o tema.
Utilizar analogias e exemplos práticos sempre que possível para facilitar a compreensão.
Foco na Interligação: Explicar explicitamente como cada novo tópico se baseia ou se relaciona com os anteriores. Criar uma narrativa que mostre a progressão natural da matéria (ex: "Depois de entendermos como os bits são transmitidos fisicamente (Camada Física), precisamos de ver como organizar esses bits em tramas e controlar o acesso ao meio partilhado (Camada de Ligação de Dados)...").
Detalhe nos Tópicos Chave (baseado nas aulas):

Modelos OSI e TCP/IP: Descrever cada camada, as suas funções principais, PDU associada e exemplos de protocolos.
Camada Física: Meios de transmissão, multiplexagem, comutação, atrasos.
Camada de Ligação de Dados: Endereçamento MAC, delimitação de tramas (HDLC, Ethernet), controlo de erros (Paridade, CRC, Distância de Hamming), protocolos ARQ (Stop-and-Wait, GBN, SR).
Subcamada MAC: CSMA/CD (Ethernet), Switches (aprendizagem, VLANs, STP), CSMA/CA (Wi-Fi, NAV, RTS/CTS, arquitetura).
Camada de Rede: Endereçamento IPv4 (sub-redes, CIDR), pacote IP (cabeçalho, fragmentação), ARP, ICMP, algoritmos de encaminhamento (Distance Vector vs. Link State), protocolo RIP.
Camada de Transporte: TCP (fiabilidade, ligação), UDP (não fiabilidade, sem ligação).
Camada de Aplicação: DHCP (DORA, Relay Agent), HTTP.
Requisitos de Design e Funcionalidade (Aspeto "Perfeito"):

Estética Moderna e Profissional:

Utilizar um design limpo, com boa tipografia (sugestão: Inter ou similar), espaçamento adequado e uma paleta de cores agradável e profissional (tons de azul e cinza neutros costumam funcionar bem para temas técnicos, com cores de destaque para elementos importantes).
O layout deve ser responsivo, adaptando-se perfeitamente a desktops, tablets e telemóveis.
Utilizar Tailwind CSS para estilização.
Elementos Visuais:

Incorporar diagramas e esquemas visuais para ilustrar conceitos complexos (ex: encapsulamento de PDUs, topologias de rede, funcionamento de protocolos como STP, troca de mensagens DHCP/ARP). Podem ser SVGs ou imagens bem desenhadas.
Considerar o uso de ícones para melhorar a navegação e a identificação de secções.
Animações subtis ou transições podem ser usadas para melhorar a experiência do utilizador, mas sem sobrecarregar.
Interatividade (Opcional, mas desejável):

Secções expansíveis/colapsáveis (como no exemplo do mapa conceptual HTML) para organizar grandes quantidades de informação.
Possíveis "tooltips" ou caixas de informação que aparecem ao pairar sobre termos técnicos chave.
Se possível, pequenos exemplos interativos simples para demonstrar um conceito (ex: cálculo de máscara de sub-rede).
Navegação e Usabilidade:

Menu de navegação principal sempre visível e fácil de usar.
Possibilidade de "breadcrumbs" para o utilizador saber onde se encontra na estrutura do site.
Conteúdo bem organizado e fácil de ler.
Tecnologias a Utilizar:

HTML5 semântico.
CSS3 com Tailwind CSS.
JavaScript para interatividade (se aplicável).
Entrega:

Um ficheiro HTML completo e auto-contido (ou um conjunto de ficheiros HTML, CSS, JS se for mais complexo) que possa ser aberto diretamente num navegador.
Fonte do Conteúdo:

Os materiais de aula fornecidos (PDFs: CP1, CP2, CP3, CP4, CP5 e CP6). O agente deve extrair e reinterpretar a informação destes documentos.
O objetivo final é um recurso de estudo que seja não só informativo, mas também agradável de usar e que ajude verdadeiramente a visualizar e a compreender a matéria de redes de computadores
