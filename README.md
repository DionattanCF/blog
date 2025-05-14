# Blog Dionattan Advogados

Este é um blog simples em HTML/CSS para o site dionattan.adv.br, focado em publicação de artigos sobre diversos temas jurídicos.

## Estrutura de Arquivos

```
blog/
│
├── css/
│   └── style.css           # Estilos do blog
│
├── img/                    # Pasta para armazenar as imagens
│
├── artigos/                # Pasta com os artigos individuais
│   └── direitos-trabalhistas.html   # Exemplo de artigo
│
├── categorias/             # Pasta para páginas de categorias
│
├── index.html              # Página inicial do blog
├── artigos.html            # Página de listagem de todos os artigos
└── README.md               # Este arquivo
```

## Funcionalidades

1. **Página Inicial**: Exibe artigos em destaque e artigos recentes.
2. **Página de Artigos**: Lista todos os artigos com filtragem por categoria.
3. **Páginas de Artigos Individuais**: Formato detalhado para cada artigo.
4. **Sistema de Categorias**: Organiza artigos por temas jurídicos.
5. **Design Responsivo**: Adaptável para dispositivos móveis e desktop.

## Como Adicionar um Novo Artigo

1. Crie um novo arquivo HTML na pasta `artigos/` seguindo o modelo do arquivo `direitos-trabalhistas.html`.
2. Adicione a imagem de destaque do artigo na pasta `img/`.
3. Atualize as páginas `index.html` e `artigos.html` para incluir links para o novo artigo.

## Desenvolvimento Futuro

Futuramente, este blog pode ser evoluído para:

1. Implementar um sistema de gerenciamento de conteúdo (CMS).
2. Adicionar funcionalidade de comentários.
3. Implementar um sistema de busca mais avançado.
4. Integrar com redes sociais para compartilhamento automático.

## Deploy para o Servidor

Para fazer o deploy deste blog para o servidor:

1. Faça o upload de todos os arquivos para o servidor web.
2. Configure o domínio dionattan.adv.br para apontar para a pasta do blog.
3. Ou, se preferir usar um subdomínio, configure blog.dionattan.adv.br.

## Usando Git para Deploy

```bash
# Clone o repositório no servidor (primeira vez)
git clone [URL_DO_REPOSITORIO] blog

# Para atualizar o blog após mudanças
cd blog
git pull
```

## Contato

Para mais informações, entre em contato com:
- Email: contato@dionattan.adv.br
- Telefone: (XX) XXXX-XXXX 