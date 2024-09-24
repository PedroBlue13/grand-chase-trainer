# grand-chase-trainer


Grand Chase Trainer - Automação para Evolução no Jogo
Grand Chase Trainer é uma ferramenta projetada para auxiliar jogadores que desejam evoluir seus personagens de forma automática no jogo Grand Chase. Esta solução foi criada pensando em pessoas que não possuem muito tempo para se dedicar ao jogo, mas que ainda assim gostariam de progredir de maneira eficiente.

Usando tecnologias de automação e OCR (Reconhecimento Óptico de Caracteres) na linguagem Python, o Grand Chase Trainer permite que seu personagem trilhe seu caminho de forma autônoma, sem a necessidade de intervenção constante, e sem alterar diretamente endereços de memória do jogo. Essa abordagem visa dificultar a identificação como um programa auxiliar, promovendo maior segurança e evitando violações de regras do jogo.

Características principais
Automação Completa: Controle automático do personagem em diversas atividades do jogo.
OCR Avançado: Utilização de Reconhecimento Óptico de Caracteres para identificar informações visuais, como o nome do personagem e elementos importantes da interface do jogo.
Tecnologia Python: Construído inteiramente em Python, garantindo flexibilidade, eficiência e facilidade de customização.
Segurança e Discrição: A solução não altera diretamente os endereços de memória do jogo, o que torna sua detecção mais difícil, promovendo uma abordagem mais segura.
Tecnologias Utilizadas
Python: Linguagem principal utilizada no desenvolvimento do projeto.
OpenCV: Biblioteca para processamento de imagens, usada para capturar e manipular a tela do jogo.
Tesseract OCR: Ferramenta de reconhecimento de texto para identificar elementos como o nome do personagem e outras informações da interface.
PyGetWindow: Utilizada para detectar e manipular a janela do jogo.
Pillow (PIL): Usada para capturar partes específicas da tela.
Como funciona
O Grand Chase Trainer detecta a janela do jogo em execução e utiliza OCR para capturar o nome do personagem e outros elementos-chave na interface do jogo. Com base nessas informações, o sistema é capaz de automatizar o comportamento do personagem, fazendo-o seguir rotas predefinidas, atacar inimigos e evoluir dentro do jogo de maneira autônoma.

Exemplo de funcionamento:
O sistema detecta o nome do personagem através do texto em verde na interface do jogo.
Utilizando processamento de imagem, o sistema reconhece os elementos da tela e executa ações automáticas, como movimento e ataques.
Tudo isso ocorre sem a necessidade de editar diretamente a memória do jogo, o que torna o programa mais discreto.
Requisitos
Python 3.x
Tesseract OCR: Instruções de instalação
Bibliotecas Python:
OpenCV
Pillow (PIL)
PyTesseract
PyGetWindow
Numpy
