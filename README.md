# 🧐 Natty or Not: Segunda Guerra Mundial

## 📜 Sobre o Projeto

Este projeto explora o uso de **IAs generativas** para criar imagens da **Segunda Guerra Mundial** e comparar com fotos reais. O objetivo é desafiar as pessoas: **Você consegue distinguir o que é real e o que foi criado por IA?**

---

## 📸 Exemplo de Imagem Gerada

### **Imagem IA**

![Imagem IA](/img/IA%2001.png)
![Imagem IA](/img/IA%2002.png)

### **Imagem Real**

![Imagem Real](/img/Real%20soldados.png)

_Você consegue identificar qual é qual?_

---

## 🚀 Como as Imagens Foram Criadas?

Utilizamos a ferramenta **DALL·E** da OpenAI com os seguintes prompts:

```txt
"Soldados americanos marchando durante a Segunda Guerra Mundial, fotografia em preto e branco, aparência realista, com uniformes detalhados e cenário de guerra ao fundo."
```

🖥 Código Python (API OpenAI)
Para fins educacionais, este é o código que geraria as imagens caso tivéssemos créditos na API da OpenAI:

⚠️ Nota: Como a conta da OpenAI atingiu o limite gratuito, as imagens foram geradas diretamente no site do DALL·E.

### Template

```markdown
# Código Python (API OpenAI)

import openai # Biblioteca da OpenAI

# Defina sua chave de API da OpenAI

openai.api_key = "SUA_CHAVE_AQUI"

# Criando uma imagem usando a nova API da OpenAI

response = openai.images.generate(
model="dall-e-2", # Você pode testar também "dall-e-3"
prompt="Soldados marchando na Segunda Guerra Mundial, fotografia em preto e branco, realista",
size="1024x1024",
quality="standard",
n=1,
)

# Pegando o link da imagem gerada

image_url = response.data[0].url

print(f"Imagem gerada: {image_url}")
```

💭 Reflexão
Com o avanço das IAs generativas, distinguir imagens falsas das reais está cada vez mais difícil. Este projeto demonstra como a tecnologia pode enganar até mesmo os olhos mais treinados!

🔹 Você acha que conseguiria diferenciar essas imagens em um teste real? Deixe sua opinião nos comentários!

#LabDIONattyOrNot

### Exemplos e Insigths

- [E-BOOK](/exemplos/E-BOOK.md)
- [Podcast](/exemplos/PODCAST.md)
- [Vídeo (Avatar Virtual)](/exemplos/VIDEO.md)

## Links Interessantes

[Base10: If You’re Not First, You’re Last: How AI Becomes Mission Critical](https://base10.vc/post/generative-ai-mission-critical/)

![Base10's Trend Map Generative AI](https://github.com/digitalinnovationone/lab-natty-or-not/assets/730492/f4df26e8-f8f7-4419-8252-c69d73ea930c)
