# Explorando Práticas de Teste

Neste exercício, vamos explorar práticas de teste em sistemas reais utilizando a ferramenta [TestMiner](https://andrehora.github.io/testminer).

O TestMiner permite visualizar e analisar testes de software em repositórios do GitHub, fornecendo dados sobre como os projetos organizam seus testes, como eles evoluem entre versões e quais bibliotecas de teste são utilizadas.
Explore a ferramenta antes de começar para se familiarizar com seu funcionamento.

Mais detalhes no GitHub da ferramenta: https://github.com/andrehora/testminer.

---

## Passo 1: Selecionar um repositório

Escolha um repositório real que possua testes de software.
Abaixo estão alguns links para ajudá-lo a encontrar projetos interessantes:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

- Tópicos: [ai](https://andrehora.github.io/testminer/#topic:ai), [llm](https://andrehora.github.io/testminer/#topic:llm), [api](https://andrehora.github.io/testminer/#topic:api), [nodejs](https://andrehora.github.io/testminer/#topic:nodejs), [android](https://andrehora.github.io/testminer/#topic:android)

- Por organização: [Google](https://andrehora.github.io/testminer/#google), [Microsoft](https://andrehora.github.io/testminer/#microsoft), [Apple](https://andrehora.github.io/testminer/#apple), [Facebook](https://andrehora.github.io/testminer/#facebook), [Netflix](https://andrehora.github.io/testminer/#netflix), 
[GitHub](https://andrehora.github.io/testminer/#github), [Apache](https://andrehora.github.io/testminer/#apache), [HuggingFace](https://andrehora.github.io/testminer/#huggingface)

## Passo 2: Explorar o repositório selecionado

Busque o repositório escolhido no [TestMiner](https://andrehora.github.io/testminer) e analise os dados de teste gerados pela ferramenta.

## Passo 3: Explicar uma prática de teste

Escolha uma prática ou dado de teste relevante e explique com suas próprias palavras.

---

## Instruções de entrega

1. Faça um `fork` deste repositório (saiba mais sobre forks [aqui](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)).
2. Responda às questões abaixo diretamente neste arquivo `README.md` do seu fork. Pode adicionar imagens para enriquecer sua explicação.
3. No Moodle, submeta apenas a URL do seu fork.

---

## Respostas

Repositório: https://github.com/fastapi/fastapi

URL TestMiner: https://andrehora.github.io/testminer/#fastapi/fastapi

Explicação: A prática de teste que escolhi analisar foi a organização dos testes e a configuração do ambiente de testes.

O FastAPI mantém seus testes em um diretório chamado tests/, separado do diretório principal fastapi/, que contém o código da biblioteca. Além disso, o projeto utiliza o pytest e configura opções rigorosas para a execução dos testes no arquivo pyproject.toml.

Essa organização é importante porque facilita a localização, a manutenção e a compreensão dos testes. Já configurações como a validação estrita de marcadores e de opções do pytest ajudam a identificar configurações incorretas, enquanto tratar avisos como erros pode revelar problemas que passariam despercebidos durante a execução.

O TestMiner permite explorar essas práticas por meio das seções de visão geral, localização dos testes, histórico e dependências. Assim, é possível compreender melhor como um projeto real organiza e mantém sua estratégia de testes.

<img width="937" height="456" alt="image" src="https://github.com/user-attachments/assets/51dbb1dc-49b0-44cc-a7ab-7dc6670b7989" />
<img width="973" height="812" alt="image" src="https://github.com/user-attachments/assets/b3ac4c04-731c-460d-8e4b-0ef1eafa8edb" />
<img width="943" height="192" alt="image" src="https://github.com/user-attachments/assets/a9aa8a2b-caf3-4b20-8fe6-11a39c01da9c" />

Concluo que uma boa prática de teste não consiste apenas em escrever vários testes, mas também em organizá-los adequadamente e configurar sua execução para detectar possíveis problemas. A quantidade de testes, isoladamente, não garante que o sistema esteja livre de defeitos.
