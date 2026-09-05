Teste seu código HTML

Este projeto é uma página HTML simples que permite ao usuário escrever e testar código HTML diretamente no navegador.

A página possui uma área de texto (textarea) onde o usuário pode inserir seu código HTML e JavaScript. Ao clicar no botão "Testar sua página", o código digitado é executado na própria página.

📋 Funcionalidades
✏️ Área para escrever código HTML.
💻 Suporte para código JavaScript dentro da página.
▶️ Botão para executar o código digitado.
🌐 Execução diretamente no navegador.
🎨 Interface simples utilizando HTML.
🛠️ Tecnologias utilizadas
HTML5 — estrutura da página.
JavaScript — responsável por executar o código informado pelo usuário.
📂 Estrutura do projeto

O projeto pode ser composto por um único arquivo:

/
├── index.html
└── README.md

🚀 Como executar
Baixe ou clone este projeto.
Abra o arquivo index.html em um navegador.
Digite ou altere o código dentro da caixa de texto.
Clique no botão "Testar sua página".
O código informado será carregado na página.
💡 Exemplo

Você pode testar o seguinte código:

<html>
<body>

    <h1>Olá, mundo!</h1>

    <script>
        alert("Olá! Este é um teste.");
    </script>

</body>
</html>


Ao clicar em "Testar sua página", o navegador exibirá o conteúdo e executará o JavaScript presente no código.

⚙️ Como funciona

O botão utiliza o evento onclick:

document.write(fonte.value);


Nesse comando:

fonte representa o textarea onde o código foi digitado.
fonte.value obtém o conteúdo escrito pelo usuário.
document.write() escreve esse conteúdo no documento atual, substituindo a página existente.
⚠️ Observação

Este projeto utiliza document.write(), que é uma abordagem simples e adequada para fins de estudo. Em aplicações reais, recomenda-se utilizar métodos mais modernos e seguros para manipulação do DOM, como innerHTML, createElement() e appendChild().

Além disso, como o código digitado pelo usuário é executado diretamente pelo navegador, não é recomendado utilizar esta implementação para executar código de terceiros ou conteúdo não confiável.


📄 Licença

Este projeto pode ser utilizado para fins de estudo e aprendizado de HTML e JavaScript.
