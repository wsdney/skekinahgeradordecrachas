Shekinah — Sistema de Gestão de Eventos e Crachás
O Shekinah é uma aplicação web de página única (SPA) projetada para simplificar a logística de eventos. Ele permite a distribuição automatizada de participantes em salas coloridas, o gerenciamento de responsáveis (obreiras) e a criação de crachás personalizados através de um editor visual intuitivo.

🚀 Funcionalidades Principais
1. Logística de Salas & Cores
Distribuição Inteligente: Importe sua lista de nomes e distribua-os automaticamente com base na capacidade por sala ou quantidade total de salas.

Interface Drag & Drop: Reorganize os participantes entre as salas arrastando os nomes diretamente na interface.

Gestão Cromática: Cada sala possui uma paleta de cores dedicada. A cor escolhida reflete automaticamente nos cards, nos gabaritos de porta e nas molduras dos crachás.

Gabarito de Porta (Paisagem): Geração de relatório PDF em formato A4 Paisagem, com cabeçalhos coloridos de alto contraste e listas numeradas para check-in.

2. Editor de Crachás (Design)
Editor Visual: Adicione textos e imagens (logotipos) com total liberdade de posicionamento e redimensionamento.

Tags Dinâmicas: Utilize {{NOME}} e {{SALA}} no design para que o sistema gere crachás individuais personalizados para cada participante.

Precisão Milimétrica: Defina o tamanho do crachá em centímetros e ajuste posições (X/Y) e dimensões (W/H) via painel de propriedades.

Geração de PDF em Grade: Exporta todos os crachás organizados automaticamente em folhas A4, prontos para impressão, respeitando a cor da moldura de cada sala.

3. Persistência de Dados
Exportação/Importação JSON: Salve o progresso completo do seu projeto (nomes, salas, cores e design visual) em um único arquivo.

Imagens Embutidas: As imagens carregadas no design são convertidas para Base64 e salvas dentro do arquivo JSON, eliminando a necessidade de arquivos externos.

🛠️ Tecnologias Utilizadas
Frontend: HTML5, CSS3 (Modern UI com Dark Mode) e JavaScript Puro (Vanilla JS).

Interatividade: Interact.js para manipulação de elementos.

PDF Engine: jsPDF para geração de documentos.

Captura Visual: html2canvas para renderização do palco de design.

Tipografia: Google Fonts (Roboto, Pacifico, Dancing Script).

📂 Como Usar
Faça o download do arquivo .html.

Abra-o em qualquer navegador moderno (Chrome, Edge ou Firefox).

Na aba Salas & Cores, cole a lista de participantes e gere a logística.

Na aba Design, monte o layout do seu crachá.

Use os botões de Exportar JSON para criar backups do seu trabalho.

📄 Licença
Este projeto foi desenvolvido para gestão interna e organização de eventos. Sinta-se livre para adaptar e melhorar o código conforme sua necessidade.

Desenvolvido com foco em agilidade e precisão visual.
