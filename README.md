# Sistema Inteligente para Predição de Falhas em Máquinas Agrícolas por meio de Dados de Sensores


## Descrição Inicial do Problema Escolhido

Máquinas agrícolas, como tratores, colheitadeiras e pulverizadores, desempenham papel fundamental na produtividade do agronegócio. Entretanto, falhas inesperadas nesses equipamentos podem causar interrupções nas operações, aumento dos custos de manutenção e prejuízos financeiros.
Atualmente, muitas empresas realizam manutenção corretiva, após a ocorrência de uma falha, ou manutenção preventiva baseada em períodos fixos de tempo. Essas abordagens podem não ser suficientes para evitar paradas não planejadas.
Com a utilização de sensores embarcados, é possível monitorar continuamente informações como temperatura do motor, vibração, pressão hidráulica, rotação (RPM) e horas de operação. A análise desses dados por técnicas de Inteligência Artificial permite identificar padrões que antecedem falhas mecânicas.
O objetivo deste projeto é desenvolver um modelo capaz de analisar dados de sensores e prever possíveis falhas em máquinas agrícolas, auxiliando equipes de manutenção na tomada de decisão e reduzindo custos operacionais.



## Estrutura Inicial do Projeto - Etapa1

```text
project/
├── src/
│   ├── data_loader.py
│   ├── preprocess.py
│   └── main.py
├── README.md
└── requirements.txt
```

---

## Funções Iniciais Sugeridas

### data_loader.py

```python
def load_data(path: str):
    pass
```

Responsável por carregar a base de dados que será utilizada no treinamento e avaliação dos modelos.

---

### preprocess.py

```python
def clean_data(data):
    pass


def split_data(data):
    pass
```

Responsável pelo tratamento dos dados, remoção de inconsistências e separação entre conjuntos de treinamento e teste.

---

### main.py

```python
def main():
    pass


if __name__ == "__main__":
    main()
```

Responsável por coordenar o fluxo principal da aplicação, executando o carregamento, tratamento e preparação dos dados.

---

## Equipe

1. João
2. Maria
3. Renata
