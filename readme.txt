# Conversor de Temperatura: Celsius para Fahrenheit

Este script Python simples permite ao usuário converter uma temperatura de Celsius para Fahrenheit. Ele solicita ao usuário que insira uma temperatura em Celsius e, em seguida, calcula e exibe o equivalente em Fahrenheit.

## Funcionalidades

- **Conversão de Temperatura**: Converte com precisão uma temperatura dada em graus Celsius para graus Fahrenheit.
- **Fácil de Usar**: Interface simples baseada em texto que solicita a entrada do usuário e exibe o resultado.

## Como Usar

Para usar este script, siga os passos abaixo:

1. **Execute o Script**: Abra um terminal ou prompt de comando e execute o script com um interpretador Python. Certifique-se de que você está na mesma pasta que o arquivo do script ou forneça o caminho completo para ele.

    ```
    python nome_do_arquivo.py
    ```

2. **Insira a Temperatura em Celsius**: Quando solicitado, digite a temperatura em Celsius que você deseja converter. Pressione `Enter` após digitar o valor.

    ```
    Digite a temperatura em Celsius: 25
    ```

3. **Veja o Resultado**: O script calculará automaticamente e exibirá o equivalente em Fahrenheit.

    ```
    25°C é igual a 77.0°F
    ```

## Requisitos

- Python 3.x

## Função Principal

A lógica principal deste script está na função `celsius_para_fahrenheit`, que realiza a conversão de temperatura. Aqui está um breve resumo da função:

```python
def celsius_para_fahrenheit(celsius):
    fahrenheit = celsius * 1.8 + 32
    return fahrenheit
```

- **Parâmetros**:
    - `celsius`: A temperatura em graus Celsius que precisa ser convertida.
- **Retorno**:
    - A função retorna o valor convertido em graus Fahrenheit.

## Contribuições

Contribuições para melhorar este script são sempre bem-vindas.