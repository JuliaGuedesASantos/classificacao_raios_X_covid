# <p align="center">  Tratamento e classificação de imagens de raios X pulmonares para detecção de COVID-19 🫁</p>
<p align="center"> <b>Júlia Guedes Almeida dos Santos & Yasmin Barbosa Shimizu </b> </p>
<p align="center"> Repositório destinado a armazenar o trabalho desenvolvido na disciplina de "Processamento de Linguagem Natural e de Imagens" para a classificação de imagens de Raios X.
 </p>

<!---
<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>
--->

<div align="center">
  <img src="https://github.com/user-attachments/assets/ccb6f5f1-0e07-4eb2-aa7c-5f681c57a59c" alt="Descrição da imagem" width="1000"/>
</div>

## 📝 Descrição

<p align="justify">
Doenças pulmonares são caracterizadas pelo avanço rápido e consequente necessidade de diagnóstico precoce. Nesse contexto, a Inteligência Artificial, especialmente desde o período de pandemia do COVID-19, emergiu como uma possível ferramenta para auxiliar no diagnóstico assistido de infecções pulmonares. Partindo disso, o presente trabalho busca classificar imagens de raios X em “Covid” e “Normal”, a partir de dados disponíveis da plataforma Kaggle. Nesse aspecto, a classificação das imagens consistiu em três principais etapas: Extração de features a partir das imagens originais – por meio da aplicação de filtros –, treinamento de um modelo de classificação Random Forest, e explicabilidade desse a partir do módulo SHapley Additive ExPlanations (SHAP). Como resultado, obteve-se um modelo com acurácia de 97,73%, sensibilidade de 96,67% e precisão de 100%, do qual foi possível extrair a importância por pixel de cada filtro e identificar as regiões mais relevantes para a previsão. 
</p>

## 📔 Notebooks e arquivos do projeto
## 🖇️ Informações técnicas
* Linguagem de programação: `Python 3.9`.
* Software:  `Visual Studio Code`, `Jupyter Notebook`.
* Bibliotecas e Módulos: `os`, `glob`, `pandas`, `numpy`, `matplotlib`, `cv2`, `seaborn`, `skimage`, `sklearn`.
  

### Como executar o algoritmo?
Os procedimentos realizados neste trabalho podem ser executados em compiladores de Python como Jupyter Notebook, Visual Studio Code e Google Colab. Para tal, é necessário:
1. A instalação das bibliotecas citadas acima, utilizando, por exemplo, o método `!pip install <nome_da_biblioteca>`;
2. O download do *dataset* ***Chest Xray for covid-19 detection*** disponível na plataforma *[Kaggle](https://www.kaggle.com/datasets/fusicfenta/chest-xray-for-covid19-detection)*, e do notebook `classificacao_raios_X_covid.ipynb` no mesmo diretório;
3. Execução do notebook em um compilador de Python.
   
<!---
## 😁 Conclusão
--->

## 🧠 Contribuições dos Colaboradores
**Desenvolvimento:** Júlia Guedes Almeida dos Santos & Yasmin Barbosa Shimizu
**Orientação e Revisão:** Prof. Dr. James Moraes de Almeida

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172424779?v=4" width=115><br><sub> Júlia Guedes </sub>](https://github.com/JuliaGuedesASantos)<br> [<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/9504021537643847)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/j%C3%BAlia-guedes-546542283/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/171518829?v=4" width=115><br><sub>Yasmin Shimizu</sub>](https://github.com/yasminbshimizu)<br> [<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](https://wwws.cnpq.br/cvlattesweb/PKG_MENU.menu?f_cod=B946BED44B4E2F555F7290AF3E8AF4F3#)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/yasminbshimizu/)
| :---: | :---: |

