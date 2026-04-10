# 🧮 Cálculadora Numérica de Derivadas com Streamlit
* Acesse o site abaixo: 
* [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)]()

Projeto pessoal para automatizar o cálculo numérico de derivadas e auxiliar estudantes de Engenharia. 

##  🚀 Funcionalidades 
* Diferenciação Numérica via Diferença Central
* Cálculo Numérico da primeira e segunda derivada
* Convertor de Trigonometria (Radianos, Graus)
* Suporte para todas as letras do alfabeto latino e grego
* Suporte para Equações Explícitas e Implícitas

## 🛠️ Tecnologias
* **Python 3**
* **SymPy** - Computação Simbólica
* **Streamlit** - Interface web

## ⌨️ Como rodar?  
* Certifique-se que o Python está instalado;
* Instale a biblioteca **Sympy** e o **Streamlit** digitando no terminal: 
```bash
   pip install -r requirements.txt
   ```
* Depois, execute o aplicativo no terminal, ou acesse o site  (SITE)
```bash
    streamlit run app.py
```
* Se digitar uma Equação Implícita, certifique-se que o ponto (x,y) pertence a curva implicita F(x,y) = 0, caso contrário, o cálculo não faz sentido. por exemplo, se  x^2 + y^2 = 25, o ponto P(1,1) não pertence a essa curva.
* Dica importante: se for usar o logaritmo natural, escreva log(...) em vez de ln(...) 
* Para o logaritmo em outras bases, use log(x, base), por exemplo: log(x, 7) 
* Além disso, caso queira usar o expoente natural (e), use, de preferência, exp(...)
* Use ** para expoentes e * para multiplicação 
* Para Seno, use sin(...) 
* Para Tangente, use tan(...)
* Para Cotangente, use cot(...) 
* Para Cossecante, use csc(...) 
* Também está disponível as funções trigonométricas hiperbólicas (sinh, cosh, ...)