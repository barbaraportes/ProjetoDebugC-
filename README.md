# Projeto guiado desenvolvido para estudos de depuração durante o curso de Introdução ao C# - Parte 6 da Microsoft.

- O objetivo deste aplicativo era obter experiência com o depurador do Visual Studio Code, implementar um padrão try-catch e criar e lançar exceções que são capturadas em um nível inferior da pilha de chamadas.
- Usei as ferramentas do depurador para configurar um ponto de interrupção nas instruções de nível superior do aplicativo. Com a execução pausada percorri o código para isolar um problema na lógica de código.
- Implementei um padrão try-catch nas instruções de nível superior.
- Criei e lancei uma exceção InvalidOperationException no método MakeChange.
- Utilizei a cláusula catch para capturar apenas o tipo de exceção InvalidOperationException.
