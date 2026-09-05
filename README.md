# 🧪 Teste seu Código HTML

Um projeto simples desenvolvido em HTML e JavaScript que permite escrever, editar e testar páginas HTML diretamente no navegador.

# 📌 Sobre o projeto

Este projeto funciona como um pequeno editor e executor de código HTML.

O usuário pode escrever seu código dentro de uma área de texto e, ao clicar no botão "Testar sua página", o navegador interpreta e executa o código informado.

# 🚀 Funcionalidades
# 📝 Editor de código HTML através de um textarea
# ⚡ Execução do código diretamente no navegador
# 💻 Suporte para JavaScript dentro do HTML
# 🎨 Interface simples e intuitiva
# 🌐 Não necessita de servidor ou instalação de dependências
# 🛠️ Tecnologias utilizadas
# HTML5
# JavaScript
# 📂 Estrutura do projeto
Teste-seu-codigo-HTML/
├── index.html
└── README.md

# ▶️ Como executar
Clone o repositório:
git clone https://github.com/Saloma0/Run-Html

Entre na pasta do projeto:
cd Run-Html

Abra o arquivo index.html no navegador.

Não é necessário instalar nenhuma dependência.

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


Depois, clique no botão "Testar sua página" para executar o código.

# ⚙️ Funcionamento

O botão utiliza o seguinte código JavaScript:

document.write(fonte.value);


O processo funciona da seguinte maneira:

O usuário escreve o código no textarea.
fonte.value obtém o código digitado.
document.write() escreve o conteúdo no documento.
O navegador interpreta e executa o HTML e o JavaScript.
# ⚠️ Observação

Este projeto foi desenvolvido principalmente para fins educacionais, demonstrando uma forma simples de executar código HTML e JavaScript no navegador.

O uso de document.write() não é recomendado para aplicações modernas. Em projetos maiores, é preferível utilizar métodos de manipulação do DOM, como:

innerHTML
createElement()
appendChild()


Atenção: não execute código de fontes desconhecidas ou não confiáveis, pois o JavaScript inserido pode ser executado diretamente pelo navegador.


# 📄 Licença

Este projeto está disponível para fins de estudo e aprendizado.
