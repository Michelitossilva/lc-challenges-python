# Reúne os desafios lançados no Let's Code Pass
Para mais informações, entre em nossa comunidade se inscrevendo em nosso [site](https://letscode.com.br/lets-code-pass)

## python-challenge1
O primeiro desafio é aplicação do **Método Twist** para codificação e decodificação de mensagens. Mais informações em `Challenge_Dados_-_Fevereiro.pdf`

`nb_challenge1_python.ipynb`: notebook com enunciado e solução passo a passo.<br>
`script_solution1.py`: script com a solução do problema. 

### Modificações Realizadas no Código
1. Tratamento de Caracteres Especiais
A função de conversão agora trata corretamente os caracteres especiais, como:

Espaço : Mapeado para o valor 28 para garantir que o espaço seja corretamente codificado e decodificado.
Underscore ('_') : Mapeado para o valor 0 para ser corretamente tratado.
Ponto ('.') : Mapeado para o valor 27, mantendo a funcionalidade correta para mensagens com pontuação.
2. Correção da Lógica de Conversão
Funçãoconverte_char_int : Agora converta corretamente os caracteres para seus valores inteiros, incluindo os caracteres especiais e alfabéticos.
Funçãoconverte_int_char : Realiza a conversão inversa, retornando os caracteres corretos com base nos inteiros processados.

#### Como usar
Executando o Código
Codificação:

Digite 0 para codificar a mensagem.
Insira uma chave (número inteiro).
Insira a mensagem a ser codificada.

Exemplo codificar:

python ./nome_do_arquivo.py
Digite 0 para codificar e 1 para decodificar: 0
Digite a chave (número inteiro): 5
Digite a mensagem: esta funcionando
Frase codificada: eemlpdzvwejcqfg.

Decodificação:

python ./nome_do_arquivo.py
Digite 1 para decodificar a mensagem.
Insira uma chave (número inteiro).
Insira uma mensagem codificada.

Exemplo decodificar:

Digite 0 para codificar e 1 para decodificar: 1
Digite a chave (número inteiro): 5
Digite a mensagem: eemlpdzvwejcqfg.
Frase decodificada: esta funcionando