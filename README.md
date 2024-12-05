#Español
---

## Juego de Dibujo Interactivo

### Descripción
Esta es una aplicación web responsiva de juegos que combina **React** para el frontend y **Python** con **FastAPI** para el backend. El objetivo del juego es replicar un dibujo dado utilizando el mouse (o el dedo, si se juega desde un dispositivo móvil) dentro de un tiempo límite. Al finalizar, el dibujo del usuario se envía al backend, donde un modelo de machine learning evalúa la similitud con el dibujo original y asigna un puntaje. La aplicación incluye varios niveles que se desbloquean a medida que el usuario supera los niveles anteriores.

### Características
- **Interfaz de Usuario**: 
  - Dibujo original mostrado en un lado de la pantalla.
  - Área de dibujo interactiva para el usuario.
  - Temporizador que limita el tiempo para completar el dibujo.
- **Backend**:
  - Implementado con **FastAPI**.
  - Utiliza machine learning para evaluar la similitud entre el dibujo del usuario y el original.
  - Calcula y devuelve un puntaje basado en la precisión del dibujo.
- **Progresión de Niveles**:
  - Varios niveles de dificultad.
  - Niveles desbloqueables al superar los anteriores.

### Tecnologías Utilizadas
- **Frontend**: React, HTML, CSS, JavaScript
- **Backend**: Python, FastAPI
- **Machine Learning**: TensorFlow/Keras (o cualquier otra librería de ML que prefieras)
- **Otros**: Axios para las solicitudes HTTP, Bootstrap para el diseño responsivo

### Instalación y Uso
1. Clona el repositorio:
   ```bash
   git clone https://github.com/Ender-osur/my-draw.git
   cd my-draw
   ```

2. Configura el entorno del backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Inicia el servidor de FastAPI:
   ```bash
   uvicorn main:app --reload
   ```

4. Configura e inicia el frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

### Contribuciones
¡Las contribuciones son bienvenidas! Si deseas contribuir, por favor abre un issue o envía un pull request.

### Licencia
Este proyecto está bajo la Licencia MIT.

---


#Inglés
---

## Interactive Drawing Game

### Description
This is a responsive web application game that combines **React** for the frontend and **Python** with **FastAPI** for the backend. The goal of the game is to replicate a given drawing using the mouse (or finger, if playing on a mobile device) within a time limit. Once the drawing is completed or the time runs out, the user's drawing is sent to the backend, where a machine learning model evaluates its similarity to the original drawing and assigns a score. The application includes multiple levels that can be unlocked as the user progresses.

### Features
- **User Interface**:
  - Original drawing displayed on one side of the screen.
  - Interactive drawing area for the user.
  - Timer to limit the drawing time.
- **Backend**:
  - Implemented with **FastAPI**.
  - Uses machine learning to evaluate the similarity between the user's drawing and the original.
  - Calculates and returns a score based on the drawing's accuracy.
- **Level Progression**:
  - Multiple levels of difficulty.
  - Unlockable levels as previous ones are completed.

### Technologies Used
- **Frontend**: React, HTML, CSS, JavaScript
- **Backend**: Python, FastAPI
- **Machine Learning**: TensorFlow/Keras (or any other ML library of your choice)
- **Others**: Axios for HTTP requests, Bootstrap for responsive design

### Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Ender-osur/my-draw.git
   cd my-draw
   ```

2. Set up the backend environment:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Start the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

4. Set up and start the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

### Contributions
Contributions are welcome! If you would like to contribute, please open an issue or submit a pull request.

### License
This project is licensed under the MIT License.

---
