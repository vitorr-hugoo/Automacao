# Automacao

# Sistema de Monitoramento e Paletização de Uvas 🍇

Este projeto foi desenvolvido para a disciplina de Automação Industrial. Trata-se de um sistema de controle para uma esteira seletora, programado em **Texto Estruturado (ST)** utilizando o software **CODESYS**.

## Equipe
* Vitor Hugo Pavanelli dos Reis
* Leoanm Rossini
* Beatriz Duran
* Felipe Alves

## Tecnologias Utilizadas
* **Linguagem:** Texto Estruturado (ST) - IEC 61131-3
* **Ambiente de Desenvolvimento:** CODESYS
* **Arquitetura de Software:** Máquina de Estados Finitos (State Machine)
* **Recursos:** Temporizadores (TON), Lógica de Intertravamento, IHM interativa com animações dinâmicas.

## ⚙️ Funcionalidades do Sistema
O sistema simula uma esteira industrial de separação de caixas com base em **Peso** e **Cor**, possuindo 3 rotas principais:
1. **Subpeso:** Descarte rápido no primeiro reservatório.
2. **Peso Ideal + Cor Amarela:** Desvio para a rota secundária.
3. **Peso Ideal + Cor Verde:** Rota principal até o fim (Paletização).

*Nota: As animações da IHM foram sincronizadas matematicamente com a lógica de varredura do CLP, simulando a inércia dos motores e o tempo de resposta físico dos sensores.*

## 📂 Estrutura de Arquivos
* `projeto_AUT_V_Final.project`: Arquivo executável do CODESYS (contém IHM e Lógica).
* `codigo_AUT_V_final.txt`: Código fonte principal em texto estruturado.

## 🎥 Demonstração
[Clique aqui para assistir ao vídeo de explicação do funcionamento no YouTube](https://www.youtube.com/watch?v=wyYrGY2WBgg))
