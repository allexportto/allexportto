# Criar README.md automaticamente

github_username = "Alex Porto"  # Substitua pelo seu nome de usuário do GitHub
whatsapp_numero = "Alex Porto"   # Substitua pelo seu número no formato internacional (+5519 971035896)

conteudo = f"""\
# Olá! Eu sou o Alex Porto 👋  

💡 **Sobre mim**  
🎓 Estudante de **Sistemas de Informação** na Wyaden  
🚀 Apaixonado por tecnologia, desenvolvimento e logística  
📚 Sempre em busca de aprendizado e novas oportunidades  

### 🚀 Tecnologias que gosto de trabalhar:  

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)![Java]https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)  
![Front-End](https://img.shields.io/badge/Front--End-FF5722?style=for-the-badge)  

📫 **Entre em contato comigo:**  
📩 **E-mail:** alexsandroporto622@gmail.com.com  
📱 **WhatsApp:** ![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white) [Fale comigo!](https://wa.me/{(19) 97103-5896)  
💼 [LinkedIn](https://www.linkedin.com/in/alex-sandro-porto-148671268/) 

🌟 **Me siga no GitHub:**  
[![Follow](https://img.shields.io/github/followers/{github_username}?label=Follow&style=social)](https://github.com/{github_username})
"""

# Criando o arquivo README.md
with open("README.md", "w", encoding="utf-8") as arquivo:
    arquivo.write(conteudo)

print("README.md gerado com sucesso! 🚀")
