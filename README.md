# BlazorPokeApi

Aplicação web desenvolvida em **Blazor WebAssembly (.NET)** para consumo da [PokéAPI](https://pokeapi.co/), permitindo a busca de informações detalhadas sobre personagens do anime Pokémon.

---

## 👨‍🎓 Identificação do Aluno

* **Nome:** Ryan Victor Vieira Quintiliano Martins
* **RA:** 12319683
* **Curso:** Engenharia de Software — UNI-BH (Ânima Educação)
* **Unidade Curricular:** Usabilidade, Desenvolvimento Web, Mobile e Jogos
* **Professor:** Daniel Henrique Matos de Paiva

---

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte da lista de exercícios práticos de Desenvolvimento Web. A aplicação conecta-se à internet para consumir o endpoint público da PokéAPI (`https://pokeapi.co/api/v2/pokemon/{nome}`) e apresenta os seguintes dados na interface:

* **Imagem oficial** (extraída do caminho `sprites.other.official-artwork.front_default` do JSON)
* **ID** do Pokémon
* **Nome**
* **Altura** (convertida para metros)
* **Peso** (convertido para quilogramas)

---

## 🚀 Tecnologias Utilizadas

* **C# / .NET 8**
* **Blazor WebAssembly**
* **System.Net.Http.Json** (para consumo e desserialização da API REST)
* **HTML5 / CSS3 / Bootstrap**

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos
* [.NET SDK](https://dotnet.microsoft.com/download) instalado na máquina.

### Passo a passo

1. Clone este repositório:
   ```bash
   git clone [https://github.com/ryanvictor432/blazor-pokeapi.git](https://github.com/ryanvictor432/blazor-pokeapi.git)
