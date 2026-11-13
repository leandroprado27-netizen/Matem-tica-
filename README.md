# Mundo dos Números

Jogo de matemática para celular, feito para o 3º ano. Não precisa instalar nada:
é uma única página (`index.html`) que funciona no navegador do celular.

## Como abrir no celular

- **Mais simples:** copie o arquivo `index.html` para o celular (ou abra o repositório
  em um serviço de hospedagem estática, como GitHub Pages) e abra no Chrome/Safari.
- Para aparecer como um app na tela inicial: menu do navegador → "Adicionar à tela inicial".

O progresso é salvo no próprio navegador do aparelho. Se trocar de celular ou limpar
os dados do navegador, o progresso começa do zero.

## Como funciona a evolução

As fases estão em ordem e só liberam quando a anterior é dominada:

1. Somas até 20
2. Subtrações até 20
3. Somas até 100 (com "vai um")
4. Subtrações até 100 (com "empréstimo")
5. Tabuada do 2, 5 e 10
6. Tabuada do 3 e do 4
7. Tabuada do 6 a 9
8. Divisão exata
9. Números até 1000
10. Problemas do dia a dia

Dentro de cada fase há três níveis: **Fácil → Médio → Difícil**.

- Acertar 5 de 6 perguntas recentes sobe de nível.
- Errar 3 seguidas faz voltar um nível, para treinar mais.
- No nível Difícil, acertar 8 de 10 conclui a fase e libera a próxima.

Cada rodada tem 10 perguntas. Na maioria delas aparece a fase atual; em algumas,
perguntas de fases já passadas, para não esquecer.

## Painel dos pais

Pelo botão 👨‍👩‍👧 no topo: mostra o nível e a porcentagem de acerto de cada fase,
e permite liberar todas as fases, ligar/desligar o som ou zerar o progresso.

## Desenvolvimento

Sem build e sem dependências. Para testar, basta abrir `index.html` no navegador.
Para ajustar regras de progressão, veja `RULES` no início do script;
para mudar as perguntas, veja o array `SKILLS`.

## Corrida da Matemática (`corrida.html`)

Jogo de corrida no estilo Gran Turismo: cada conta de matemática é uma curva da pista.

- Acertar faz o carro avançar; responder rápido avança mais. 3 acertos seguidos ativam o **TURBO**.
- Errar ou deixar o tempo acabar faz o carro perder ritmo.
- Cinco licenças (Iniciante → Platina), cada uma com 3 corridas. A Copa de cada licença libera a próxima.
- Ganhe 🪙 nas corridas e compre carros mais potentes na garagem.
- Painel dos pais (📊): acertos por assunto, som liga/desliga e zerar progresso.

Abra `corrida.html` no navegador do celular, como o `index.html`. O progresso fica salvo no navegador.
