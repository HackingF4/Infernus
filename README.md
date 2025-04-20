# Infernus Dooxing - Site de Conteúdo Obscuro

Um site estático com estética inspirada na deep web, desenvolvido para exibir vídeos e imagens com descrições, sem necessidade de login ou contas de usuário.

## Estrutura do Projeto

```
/
├── index.html                       # Página inicial com lista de postagens
├── post/
│   ├── video1.html                  # Página individual do post 1
│   ├── video2.html                  # Página individual do post 2
│   └── video3.html                  # Página individual do post 3
├── media/
│   ├── video1.mp4                   # Vídeo para o post 1
│   ├── favicon.ico                  # Favicon principal 16x16 
│   ├── favicon-16x16.png            # Favicon 16x16 em PNG
│   ├── favicon-32x32.png            # Favicon 32x32 em PNG
│   ├── apple-touch-icon.png         # Ícone para dispositivos Apple (180x180)
│   ├── safari-pinned-tab.svg        # Ícone SVG para Safari
│   ├── imagem1.jpg                  # Imagem para o post 2
│   ├── audio1.mp3                   # Áudio para o post 3
│   └── ambient.mp3                  # Som ambiente de fundo
├── css/
│   └── style.css                    # Todo o CSS personalizado do site
├── fonts/
│   └── Creepster.ttf                # Fonte gótica usada no site
└── README.md                        # Este arquivo de documentação
```

## Características

- Design sombrio inspirado em estética de deep web
- Efeito glitch no título e elementos visuais
- Páginas individuais para cada conteúdo
- Reprodutor de mídia estilizado
- Responsivo para diferentes tamanhos de tela
- Efeitos visuais de TV antiga/VHS
- Som ambiente (mutado por padrão)

## Como Utilizar

1. Faça o download ou clone este repositório
2. Adicione seus próprios arquivos de mídia na pasta `/media/`
3. Para adicionar novos posts:
   - Crie um novo arquivo HTML na pasta `/post/` usando os exemplos existentes como modelo
   - Adicione um link para o novo post na página inicial (`index.html`)

## Como Personalizar

- Cores: Edite as variáveis CSS no início do arquivo `css/style.css`
- Fontes: Substitua a fonte Creepster ou edite as importações no CSS
- Efeitos: Ajuste as animações no arquivo CSS conforme necessário

## Como Publicar

Este site é totalmente estático e pode ser hospedado em qualquer serviço de hospedagem gratuito:

1. **GitHub Pages**:
   - Faça upload para um repositório GitHub
   - Ative o GitHub Pages nas configurações do repositório

2. **Netlify**:
   - Faça upload ou vincule ao seu repositório Git
   - Netlify detectará automaticamente que é um site estático

3. **Vercel**:
   - Conecte ao seu repositório Git
   - Implante com as configurações padrão para sites estáticos

4. **InfinityFree ou outro serviço de hospedagem gratuito**:
   - Comprima todos os arquivos em um arquivo ZIP
   - Faça upload via painel de controle do serviço

## Adicionar Novos Conteúdos

Para adicionar um novo post:

1. Adicione seu arquivo de mídia à pasta `/media/`
2. Crie um novo arquivo HTML na pasta `/post/` (copie um dos existentes como modelo)
3. Atualize o título, descrição e caminho do arquivo de mídia
4. Adicione um link para o novo post na página inicial

## Personalizar o Favicon

Você pode criar um favicon personalizado seguindo estes passos:

1. Crie uma imagem que combine com a estética do site (preferencialmente uma aranha ou caveira)
2. Acesse um gerador de favicon online como [favicon.io](https://favicon.io/) ou [realfavicongenerator.net](https://realfavicongenerator.net/)
3. Faça upload da sua imagem e gere os diferentes tamanhos de favicon
4. Baixe o pacote de favicons e substitua os arquivos na pasta `/media/`

Recomendações para o favicon:
- Use cores escuras que combinem com o tema do site (preto e vermelho)
- Formato quadrado com bordas transparentes
- Imagem simples e reconhecível mesmo em tamanho pequeno
- Formatos necessários: ICO, PNG (16x16, 32x32) e PNG (180x180 para Apple)

## Observações

- O áudio de fundo está configurado como mudo por padrão (autoplay muted)
- O site não possui funcionalidades de comentários ou login
- Todo o conteúdo é carregado localmente, sem dependências externas além das fontes do Google

---

Desenvolvido como um projeto de site estático com temática sombria. 