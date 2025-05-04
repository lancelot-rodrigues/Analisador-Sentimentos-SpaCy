# Analisador de Sentimentos com spaCy (Português 🇧🇷)

Este projeto utiliza a biblioteca **spaCy** para detectar o sentimento de frases em português com base em palavras-chave positivas e negativas. A análise classifica o texto como **Positivo**, **Negativo** ou **Neutro**.

## 🔧 Ferramentas e Bibliotecas Utilizadas

- **Python**
- **spaCy**
- **Modelo linguístico:** `pt_core_news_sm`

## 🚀 Como Funciona

1. O texto é processado com o modelo do spaCy.
2. Um `Matcher` busca por palavras positivas e negativas.
3. Uma extensão personalizada (`.sentimento`) classifica a frase com base na contagem das palavras encontradas.

## 📌 Exemplo de Saída

```
Frase: Eu gostei muito do filme, foi ótimo!
Sentimento detectado: Positivo
----------------------------------------
Frase: O serviço foi péssimo e eu fiquei muito decepcionado.
Sentimento detectado: Negativo
----------------------------------------
```

## 👥 Integrantes

- **Lancelot Chagas Rodrigues** - RM: 554707  
- **Ana Carolina Martins da Silva** - RM: 555762

## 📂 Execução

Instale os pacotes necessários:

```bash
pip install -U spacy
python -m spacy download pt_core_news_sm
```

Execute o script em Python e veja os sentimentos detectados para cada frase!