# GRUPO 2

- GitFLow

| Nome        | Função       |
| ----------- | ------------ |
| feat/commit | novo recurso |
| fix/bug     | correcao     |
| docs/readme | documentos   |

---

## Branchs

| Nome             | Função                               |
| ---------------- | ------------------------------------ |
| Merge Commit     | preserva todo o historico            |
| Squash and Merge | transforma todos os commits em um só |
| Rebase           | reorganiza pela timeline dos commits |

### Comandos importantes

| Nome                                  | Função                               |
| ------------------------------------- | ------------------------------------ |
| git branch                            | branchs locais                       |
| git branch -r                         | branchs remotas                      |
| git branch -a                         | todas as branchs                     |
| git branch nome-da-branch             | criar nova branch                    |
| git checkout nome-da-branch           | mudar para branch selecionada        |
| git checkout -b nome-da-branch        | criar e mudar pra branch selecionada |
| git branch -d nome-da-branch          | deleta branch local                  |
| git branch push origin nome-da-branch | manda pro repositorio remoto         |
| git -m novo-nome                      | renomeia o nome da branch            |

# Merge

Junção de branchs

## Tipos
- Fast-Foward
    - Ocorre quando a branch de destino não tem commits desde que a outra foi criada. O Git simplesmente "avança" o ponteiro da branch de destino para o último commit da branch de origem. É uma operação linear e limpa, que não cria um novo "merge commit

- Squash and Merge: Junta e mescla as branchs
    - Uma estratégia onde todos os commits de uma branch são combinados em um único novo commit antes de serem mesclados à branch de destino. 

- Three-Way Merge (Três vias)
    - Ocorre quando ambas as branches têm novos commits. O Git identifica um ancestral comum e cria um novo commit especial de merge para combinar as duas histórias. Esse merge pode resultar em conflitos, caso as mesmas partes do código tenham sido alteradas em ambas as branches

## Conflitos
- Conflito de conteúdo
    - Acontece quando diferentes devs modificam as mesmas linhas de um mesmo arquivo
- Conflito estrutural 
    - Ocorre quando há mudança no repositório, localização do arquivo, renomeação e etc

## Documentação

| Nome        | Função       |
| ----------- | ------------ |
| feat/commit | novo recurso |
| fix/bug     | correcao     |
| docs/readme | documentos   |

---

# Pull Request
- Commit:
    - Registra data, autor, o que mudou e mensagem
    - Formato: tipo(escopo): descrição ou tipo(escopo)/descrição
- Stagging Area
    - Area de preparação
- PR(Pull Request)
    - É a solicitação de mudanças em um repositório/branch. Ele é solicitado, revisado pelo time, pode sofrer ajustes e aprova e mescla
    - PR Limpo: Cada commit tem um propósito claro; Descrição detalhada no PR; Revisão rápida
    - PR Bagunçado: "test", "fix", "ajusto final"; Demora pra revisar
## Como criar um PR
- Ir em pull request
- solicitar PR
