# Gerador de Imagens com DCGAN no Dataset CelebA

Este projeto apresenta a implementação de uma **Rede Generativa Adversarial Profunda** (*Deep Convolutional Generative Adversarial Network – DCGAN*) com o objetivo de **gerar imagens sintéticas de rostos humanos** a partir de vetores de ruído aleatório. Utilizando o **dataset CelebFaces Attributes (CelebA)**, composto por milhares de imagens de rostos de celebridades, o modelo foi treinado para **aprender a distribuição de probabilidade das imagens reais**, permitindo a geração de novas amostras visuais com características fotorrealistas.

O treinamento seguiu as **práticas recomendadas para GANs**, incluindo o uso de **camadas convolucionais profundas** e **funções de ativação adequadas**, resultando em um gerador capaz de produzir imagens de alta qualidade. Este trabalho demonstra o potencial das **redes generativas adversariais** na **síntese de imagens realistas** e na **modelagem de distribuições complexas de dados visuais**.

---

## 📄 Sobre o Projeto

As **GANs (Generative Adversarial Networks)** são uma abordagem inovadora de **aprendizado profundo**, composta por duas redes neurais:

* **Gerador**: responsável por criar imagens sintéticas a partir de vetores de ruído.
* **Discriminador**: encarregado de distinguir entre imagens reais e imagens geradas.

Essas redes são treinadas de forma **adversarial**, ou seja, competindo entre si: o Gerador busca enganar o Discriminador com imagens cada vez mais realistas, enquanto o Discriminador tenta aprimorar sua capacidade de identificação.

Neste projeto, foi utilizada uma **DCGAN (Deep Convolutional GAN)**, que incorpora **camadas convolucionais profundas** no Gerador e no Discriminador, aprimorando a qualidade das imagens geradas e estabilizando o treinamento.

O objetivo central foi **gerar imagens de rostos humanos com qualidade progressivamente melhor ao longo das épocas de treinamento**, partindo de padrões aleatórios de ruído até alcançar imagens com **coerência visual e realismo aprimorado**.

---

## ✅ O que foi feito

- Preparação e pré-processamento do dataset **CelebA** com imagens redimensionadas para 64x64 pixels.
- Implementação do **Gerador** e do **Discriminador** utilizando o **PyTorch**.
- Definição da função de perda e inicialização dos pesos.
- Treinamento da rede ao longo de **50 épocas**, salvando as imagens geradas ao longo do processo.
- Visualização da evolução das imagens geradas em diferentes épocas.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **PyTorch**
- **Torchvision**
- **Matplotlib**
- **PIL (Python Imaging Library)**

---

## 🎯 Para que Serve?

Este projeto demonstra na prática como GANs podem ser utilizadas para:

- Geração de rostos sintéticos.
- Entendimento de **aprendizado não-supervisionado**.
- Criação de datasets artificiais.
- Exploração de aplicações em **arte generativa**, **animação** e **pesquisa médica**.

---

## 🌟 Por que é Importante?

As GANs têm sido usadas em diversas áreas modernas, como:

- **DeepFakes**
- **Restauração de imagens antigas**
- **Transferência de estilo**
- **Geração de imagens médicas sintéticas**

Entender como essas redes funcionam desde a implementação até os resultados permite **compreender melhor os desafios e potencialidades da inteligência artificial generativa**.

---

## 💡 Aplicações Futuras

Este tipo de abordagem pode ser utilizada para:

- Geração de avatares personalizados.
- Criação de personagens para jogos.
- Simulação de rostos para anonimização de dados.
- Pesquisa sobre **bias (viés) em datasets faciais**.

---

## 📷 Exemplos de Imagens Geradas

### Imagem da Época 0:

![fake_epoch_000](https://github.com/user-attachments/assets/7f3ac21a-d74c-41db-8b9d-c401da8321ab)

---

### Imagem da Época 49:

![fake_epoch_047](https://github.com/user-attachments/assets/1c111d58-9832-448c-94ac-4221d681a7ae)
---

## 🏁 Conclusão

O desenvolvimento deste projeto permitiu explorar na prática os conceitos de **Redes Generativas Adversariais (GANs)** e suas aplicações no domínio da geração de imagens realistas. Ao longo do treinamento, observou-se uma evolução significativa na qualidade das imagens produzidas, evidenciando a capacidade do Gerador em **aprender padrões complexos** a partir de dados de treinamento.

Embora os resultados tenham apresentado **imagens cada vez mais coerentes com rostos humanos**, ainda há desafios relacionados à **fidelidade dos detalhes e diversidade** das amostras geradas, principalmente em épocas iniciais. Isso abre espaço para futuras melhorias, como o uso de arquiteturas mais avançadas (por exemplo, **StyleGAN**), aumento da resolução das imagens ou **ajustes nos hiperparâmetros e no balanceamento entre Gerador e Discriminador**.

Este projeto reforça a importância das GANs como uma tecnologia promissora em **áreas como arte computacional, síntese de dados, entretenimento e privacidade**, ao mesmo tempo que destaca a necessidade de reflexão sobre **questões éticas e potenciais riscos** associados ao uso indiscriminado de imagens sintéticas.

No geral, os resultados alcançados demonstram a viabilidade e o potencial das **DCGANs** como ponto de partida para aplicações mais complexas e inspiram futuras explorações no campo da **inteligência artificial generativa**.

---
- 📌 **Autor**: Hian Stafford
- 📩 **Email**: hian.correa@gmail.com
```text
  /\_/\  
 ( -.- ) 
  > ^ < 
```
