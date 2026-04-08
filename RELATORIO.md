# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>`00580709`</mark>
- **Nome**: <mark>`Iuri Kali Sieczkowski de Carvalho`</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

<mark>`
- Crie um loop “for” que começa em 0 e passa por todos os coelhos.

- Coelhos:
    - Para cada coelho:
    - Calcule o seu ângulo correspondente dentro do círculo (phase = ((2 * M_PI) / rabbits) * i).
    - Obtenha a variação do ângulo subtraindo o ângulo anterior pelo o glfwGetTime() (final_angle = phase - (glfwGetTime() * vel)) para que gire para direita.
    - Calcule a posição x e z utilizando coordenadas polares.
    - Calcule a posição y utilizando seno e alterando a frequência pela quantidade de pulos (float rabbit_y = (amplitude * sin(final_angle * jumps))).
    - Calcule a rotação no eixo y para que o coelho sempre fique olhando para frente utilizando -final_angle + M_PI + M_PI / 2.
    - A cada 4 coelhos calcule a pirueta no eixo z somando o ângulo utilizado para calcular a posição y com PI / 4.
    - Faça a seguinte multiplicação de matrizes: Translação * Rotação em Y * Rotação em Z * Escala.

- Ovos:
    - Calcule o movimento de órbita do ovo ao redor do coelho utilizando coordenadas polares no plano yz.
    - Para transformar a esfera em um ovo, altere a escala x e z para um valor menor do que o do eixo y.
    - Multiplique a matriz do coelho pela do matriz do ovo para que o ovo vire “filho” do coelho.
    - Para o segundo ovo apenas some PI no ângulo da coordenadas polares.

</mark>

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

<mark>`<preencher>`</mark>

## Você acha que conseguiu resolver o problema de forma adequada?

<mark>`<preencher>`</mark>

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

<mark>`<preencher>`</mark>

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>
