# corretor-ortografico-em-python

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/corretor-ortografico-em-python)
![Badge de Atualização](https://img.shields.io/github/last-commit/fab-souza/corretor-ortografico-em-python)

| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Corretor Ortográfico em Python**
| :label: Tecnologias | python
| :rocket: URL         | [Notebook no Kaggle](https://www.kaggle.com/fabianadesouza/corretor-ortografico)
| :fire: Desafio     | Conteúdo do curso [Corretor Ortográfico em Python](https://www.alura.com.br/curso-online-nlp-corretor-ortografico)

![](https://user-images.githubusercontent.com/67301805/215895439-4b0d4737-5b11-4ddc-9ac9-092a284b5e39.jpg#vitrinedev)


## Sobre o curso 📚

Neste curso, do instrutor [Thiago Santos](https://www.linkedin.com/in/thiago-gon%C3%A7alves-santos/), tive meu primeiro contato com os conceitos fundamentais de NLP (processamento de linguagem natural) para criar um corretor de palavras, parecido com o temos no smartphone e sites de pesquisa.

O foco do curso era criar um modelo capaz de corrigir os diversos tipos de erro de digitação, por exemplo além da palavra com ortografia incorreta, também pode ocorrer erro ao esbarrar acidentalmente na letra do lado, acabar trocando a ordem de algumas letras ou esquecer de digitar alguma. Para cada tipo de erro foi criado uma função que fatia cada letra da palavra e efetuava a inserção, troca, inversão de ordem, delete de caracteres e, ao final, verificar se alguma palavra gerada nas funções consta no *corpus*, a base de dados composta por 18.464 termos únicos.

![image](https://user-images.githubusercontent.com/67301805/217243015-9fc286b6-6155-4074-b365-b7e212fd92a4.png)
![image](https://user-images.githubusercontent.com/67301805/217243131-2dbac3df-2999-4c0e-ba90-f38584775650.png)

E para verificar o desempenho do modelo, importamos mais um arquivo com 186 palavras, escrita da maneira correta e depois com algum erro. Uma nova função foi criada para ler a grafia incorreta, passar pelas funções de correção e comparar com a palavra escrita de maneira correta. Ao final do curso, chegamos a um modelo com 76,34% de taxa de acerto.


## Minha prática 👩🏻‍💻

Para minha base de dados, usei um dataset disponível no [Kaggle](https://www.kaggle.com/), o [14 million word corpus](https://www.kaggle.com/datasets/luisgasparcordeiro/14-million-word-corpus-txt). Mesmo com essa quantidade absurda de palavras, meu modelo teve um desempenho menor do que o que foi desenvolvido no curso. Enquanto o modelo do instrutor foi avaliado com mais de 70% de acerto, o meu atingiu no máximo 64,54%.

![image](https://user-images.githubusercontent.com/67301805/217310271-e3ea319d-908c-4ee9-ba29-30dd630a7951.png)

## Conclusão 🏁

Mesmo sendo algo recorrente no nosso cotidiano, eu nunca havia parado para pensar no que há por trás dos corretores ou como foram desenvolvidos. Este foi um dos projetos mais desafiadores, até o momento, e apesar da complexidade, eu gostei de conhecer sobre processamento de linguagem natural e de ver outras áreas de aplicação para inteligência artificial.




## Ferramentas utilizadas 🧰 
<p> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
    <a href="https://www.nltk.org/" target="_blank" rel="noreferrer"> <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--G6tJrBaV--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/4rz47l767g96lws0m73g.png" alt="nltk" width="40" height="40"/> </a>
    </p>
