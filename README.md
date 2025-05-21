# Sprint4-IOT

# Link Apresentação SPrint4: https://youtu.be/Y1MsfHrPl2k
# **Projeto de IA para Análise de Imagens Odontológicas**

## **Visão Geral**
Este projeto utiliza Machine Learning e Visão Computacional para analisar imagens odontológicas e identificar problemas como cáries e tártaro. A IA foi treinada utilizando o **Roboflow**, integrando modelos como **YOLOv8** e **TensorFlow** para garantir alta precisão na detecção.

## **Arquitetura da IA / ML**

### **1. Coleta e Organização de Dados**
- Utilização de um dataset de imagens odontológicas.
- Armazenamento e rotulação utilizando o **Roboflow**.

### **2. Pré-processamento de Imagens**
- Uso do **OpenCV** para melhorar qualidade e segmentação das imagens.
- Conversão para escala de cinza e ajustes de contraste para destacar regiões de interesse.

### **3. Treinamento do Modelo**
- Implementação utilizando **YOLOv8** e **TensorFlow**.
- Treinamento baseado em **detecção de objetos**.
- Divisão do dataset: **80% treinamento, 10% validação, 10% teste**.

### **4. Validação e Teste**
- Uso de métricas como **mAP (Mean Average Precision)** para avaliar o desempenho.
- Testes com imagens não vistas pelo modelo para medir generalização.

### **5. Inferência e Aplicação**
- Integração do modelo para processar imagens odontológicas em tempo real.
- Geração de relatórios automáticos sobre os diagnósticos identificados.

---

## **Integração com Outras Disciplinas**

| **Disciplina**        | **Integração** |
|----------------------|---------------|
| **Java Advanced**   | Comunicação com APIs para análise em tempo real. |
| **DevOps**         | Automação do treinamento e deploy do modelo. |
| **Mobile Development** | Aplicação da IA no app mobile para análise de imagens odontológicas. |
| **QA (Quality Assurance)** | Testes para garantir a precisão e confiabilidade da IA. |
| **Banco de Dados**  | Armazenamento de imagens processadas e diagnósticos. |
| **.NET**           | Interface web para visualização dos resultados da IA. |

---

## **Próximos Passos**
- Melhorar a precisão do modelo com mais dados de treinamento.
- Testar a robustez do modelo com diferentes imagens.
- Refinar a integração entre as diversas disciplinas do projeto.
- Disponibilizar o código como **open-source** para colaboração.

  # Link Apresentação passada com teste: https://youtu.be/5ik2Sh-9aCM
