                           🤖 Generador de Preguntas y Resúmenes con Transformers (Flask + T5 + GPT) 🤖
<br><br>

Este proyecto es una aplicación web construida con Flask y HuggingFace Transformers que permite: <br>

✅ Generar preguntas automáticas a partir de un texto <br>
✅ Responder preguntas usando contexto <br> 
✅ Traducir textos de inglés a francés <br>
✅ Resumir textos largos en párrafos concisos <br>
✅ Interfaz web para interactuar con todas estas funcionalidades <br>
<br>
Todo esto utilizando el poderoso modelo T5-large de Google y GPT2-medium.

![image](https://github.com/user-attachments/assets/d04ab155-bb6a-4736-88d8-cef0b42843dd)

![image](https://github.com/user-attachments/assets/6a15b824-4525-4c1b-a26f-ddb65d85e876)

![image](https://github.com/user-attachments/assets/2c12e8bb-edb7-438f-9689-d7174d295e2d)

![image](https://github.com/user-attachments/assets/d1b3fc7b-0070-4fab-92b6-4930508beeb6)

![image](https://github.com/user-attachments/assets/799cdab1-0bdc-4be4-9b30-ad1194e22980)

![image](https://github.com/user-attachments/assets/09bd8b4d-a85e-47fa-9d27-396a8fa9921c)

-----------------------------------------------------------------------------------------------

🚀 Tecnologías usadas
- Python 3.8+
- Flask
- HuggingFace Transformers (t5-large)
- Torch (PyTorch)
- HTML + Bootstrap (para las vistas)
- Flask-CORS (para habilitar comunicación externa)

-----------------------------------------------------------------------------------------------

📦 Instalación
<br><br>
1. Clona el repositorio<br>
&nbsp;git clone https://github.com/tu-usuario/tu-repo.git<br>
&nbsp;cd tu-repo<br>

2. Crea un entorno virtual (opcional pero recomendado) <br>
&nbsp; python -m venv venv <br>
&nbsp; source venv/bin/activate  # En Windows: venv\Scripts\activate<br>

3. Instala las dependencias<br>
&nbsp;pip install -r requirements.txt <br>
   
-----------------------------------------------------------------------------------------------

🧠 Cómo ejecutar el proyecto

1. Asegúrate de tener Python instalado (3.8 o superior).
2. Ejecuta el archivo principal:
   python server.py
3. Verás algo como esto:
   ![image](https://github.com/user-attachments/assets/409cdf83-b908-4635-921d-1b1744e04a82)
4. Ctrl + click al link que aparece en * Running on*
   
-----------------------------------------------------------------------------------------------

🧪 Endpoints disponibles

📄 Página principal <br>
&nbsp;⭐ / → Página de inicio

🤖 Generar preguntas <br>
&nbsp;⭐ POST /generate_questions → Envía un texto y recibe hasta 10 preguntas generadas automáticamente.

❓ Responder preguntas <br>
&nbsp;⭐ POST /procesar_pregunta → Envía una pregunta (y opcionalmente un contexto) y devuelve una respuesta generada.

🌍 Traducir inglés a francés <br>
&nbsp;⭐ POST /traducir → Traduce textos del inglés al francés.

📚 Resumir textos <br>
&nbsp;⭐ POST /procesar_resumen → Devuelve un resumen breve del texto enviado.

-----------------------------------------------------------------------------------------------

📁 Estructura de carpetas (sugerida) <br>

![image](https://github.com/user-attachments/assets/4abd4819-5d1d-4609-9edf-3da6b0b50ae9)

-----------------------------------------------------------------------------------------------

📝 Notas finales <br>

⭐ El modelo T5-large es pesado (~850MB), así que asegúrate de tener buena conexión o usar GPU. <br>
⭐ El modelo gpt2-medium también es pesado (~345MB), así que asegúrate de tener buena conexión o usar GPU si es posible. <br>
⭐ Si tienes una GPU, el código usará automáticamente cuda, si no, funcionará con CPU (más lento). <br>
⭐ Puedes extender este proyecto fácilmente para que tenga autenticación, base de datos o exportación de resultados. <br>

-----------------------------------------------------------------------------------------------

🧑‍💻 Autor <br>
Desarrollado con ❤️ por Bet<br>
Si te gusta, dale una estrella ⭐ al repo y sígueme para más proyectos geniales.<br>
<br>
<br>
🐢🐢🐢
