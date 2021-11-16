<h1>ABQ DATA Entry</h1>

Este programa é uma adaptação do aplicativo "ABQ DATA Entry", presente no terceiro capítulo do livro Python GUI Programming with Tkinter Design and build functional and user-friendly GUI applications, 2nd Edition by Alan D. Moore lançado em outubro de 2021 e disponível em: https://www.amazon.com.br/Python-GUI-Programming-Tkinter-user-friendly-ebook-dp-B09DPN8MB3/dp/B09DPN8MB3/ref=dp_ob_title_def .

O aplicativo apresenta de forma concisa alguns dos widgets mais populares do uso do tkinter assim como seu
pacote de atualização gráfica **ttk**.

No referente capítulo do livro, nos é apresentado um estudo de caso fictício a respeito de uma empresa voltada para melhoramento genético de plantas. A empresa apresenta três laboratórios distintos, cuja suas 
anotações são feitas de modo manual. Sendo proposto a criação de um applicativo com objetivo de digitalizar
essas anotações através do uso de formulários eletronicos e geração de arquivos com formato CSV.

O estudo de caso proposto tem por objetivo a pratica e assimilação dos seguintes conceitos:

* Anatomia de uma aplicação Tkinter.
* Intercambialidade nos métodos de alocação geometrica dos widgets.
* Uso de variáveis de controle relacionadas aos dados de entrada fornecidos pelo usuário.

 
Função de salvamento (The Save Callback)

* Determinar  a data atual a ser gerada para nome do arquivo.

* Determinar se o arquivo existe, caso não exista, cria-lo e escrever uma linha como cabeçalho.

* Extrair dados do formulário e reaizar todas as limpezas nessessárias.

* Realizar incrementos dos records_save e informar ao usuário que os dados foram salvos.

* Resetar o formulário para o próximo arquivo

* Criararquivo CSV contendo os dados indormados no formulário