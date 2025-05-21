# PortalGunStore

Olá, meu nome é Gustavo, e essa é a minha landing page, ela é baseada no universo de Rick and Morty, sendo uma loja de armas de portal.

Link para o site: https://portalgunstore.vercel.app/

## Sobre o projeto

Este projeto foi feito em Next.js, uma framework do React, em conjunto com o tailwind CSS, voltado para a estilização. Além disso, foi integrado com um Banco de Dados MySQL open source, o Supabase.

## Para rodar o projeto:

Crie um arquivo .env na raiz do projeto, fora da pasta src. Nesse arquivo, adicione:

```bash
NEXT_PUBLIC_SUPABASE_URL=https://xxfrngdrypkuzjyxllkx.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Inh4ZnJuZ2RyeXBrdXpqeXhsbGt4Iiwicm9sZSI6ImFub24iLCJpYXQiOjE3NDQ3NDkzMTAsImV4cCI6MjA2MDMyNTMxMH0.cDa0CV2JITCuCIWVJU6p4EfslXO2IRBMZ7ZsRgPgkCc
```
Depois execute o seguinte comando no terminal para instalar todas as dependências:
```bash
npm install
```

Após isso, execute em localhost com:
```bash
npm run dev
```

Depois abra [http://localhost:5000](http://localhost:5000) no seu navegador.

Caso a porta esteja em uso, vá até o arquivo package.json e localize a linha 6.

Mude o argumento da opção -p:
```bash
"dev": "next dev --turbopack -p 5000",
```
Para:
```bash
"dev": "next dev --turbopack -p 3000",
```
Ou qualquer outra porta que não esteja sendo utlizada.

## Brainstorming

### Descrição geral: 
Minha ideia é uma loja "virtual" de Portal Guns do universo de Rick and Morty, elas serão mostradas em um carrosel de imagens, ao clicar em uma delas será aberto um pop-up com os detalhes da arma e o procedimento (descrição e formulário a ser preenchido) para efetuar a compra. Haverá tbm uma barra de navegação para a procura de armas específicas, para isso, vou tentar add uma quantidade diversificada para isso ser viável, tipo umas 15 a 20 armas diferentes, estou considerando a utilização de IA para gerar modelos de armas, mas vou tentar procurar modelos reais criados pelo estúdio. O rodapé será bem simples, vou zoar um pouco aqui com algumas referências ao universo colocar alguns Links. Primeiramente, vou procurar uns modelos de Landing Page, até pq não sou muito designer, mas durante o projeto vou tentar ser o mais autêntico possível e confiar nas minhas habilidades, ou seja, limitar o uso de IA (principalmente no código, tirando as imagens rsrs) e CTRL C CTRL V. Responsividade e ReadMe por último. 

Checklist dos requisitos obrigatórios desenvolvidos:
- Barra de navegação |✓|
- Catálogo de produtos |✓|
- Carrossel de imagens (produtos |✓|
- Rodapé |✓|
- Design responsivo Mobile Firts |✓|
- ReadMe |✓|



