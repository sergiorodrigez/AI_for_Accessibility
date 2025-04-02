# AI for Accessibility

This project is a Final Year Project developed at the ICAI School of Engineering (Universidad Pontificia Comillas). It presents a web application powered by AI, aimed at supporting people with speech impairments by guiding them to share stories and thoughts in a friendly, structured way. The application transforms their responses into personalized audio using text-to-speech synthesis.

## Features

- Guided conversation system using OpenAI API
- Personalized voice synthesis with Microsoft Azure
- Accessible web interface for users with speech disorders
- Secure and scalable backend using Flask and SQLite
- Responsive frontend with HTML, CSS, and Bootstrap
- Agile development methodology (Scrum-based)

## Technologies

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Flask, SQLAlchemy
- **AI APIs**: OpenAI (text generation), Azure TTS (voice synthesis)
- **Database**: SQLite

## System Architecture

![image](https://github.com/user-attachments/assets/21fe22ba-5e2a-4730-b6e7-17a21b6bcdc6)


## Screenshots

### User Flow

<img src="img/login_screen.png" width="500"/>
*From: Figura 25 – Inicio de Sesión*

<img src="img/start_screen.png" width="500"/>
*From: Figura 26 – Pantalla de Inicio*

<img src="img/conversation.png" width="500"/>
*From: Figura 29 – Conversación*

<img src="img/results.png" width="500"/>
*From: Figura 30 – Resultados de la Conversación*

## How It Works

1. User logs in and is guided through simple, conversational questions.
2. The system uses OpenAI to structure the input into a meaningful story.
3. Azure Text-to-Speech transforms the story into audio in a natural-sounding voice.
4. The final output is a downloadable audio file the user can listen to and share.

## Results

The system was tested with various user flows and produced high-quality, coherent audio outputs. Usability and accessibility were central design criteria, with successful implementation in all tested scenarios.

## Future Work

- Voice customization per user
- Story saving and retrieval
- Forum features with AI moderation
- Multilingual support

## Author

- Sergio Rodríguez García  
  Final Year Project – Telecommunications Engineering  
  Universidad Pontificia Comillas – ICAI

## License

For educational purposes only.
