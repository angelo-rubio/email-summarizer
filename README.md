# Email Summarizer and Responder

This project demonstrates the use of OpenAI's GPT-4o-mini model to generate mock emails, summarize them, and propose responses. The emails are created in a random language (English, Spanish, or Japanese), summarized in English, and then a response is proposed in the original language.

## Features

- Generates mock emails in English, Spanish, or Japanese.
- Summarizes emails in English.
- Proposes responses in the original language of the email.

## Prerequisites

- Python 3.11 or later
- Required Python packages:
  - `openai`
  - `python-dotenv`
  - `requests`
  - `IPython`

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd email-summarizer

2. Install the required Python packages:
pip install openai python-dotenv requests ipython


 3. Create a .env file in the root directory and add your OpenAI API key:
 OPENAI_API_KEY=your_openai_api_key

## Usage
Open the email_summarizer.ipynb notebook in Jupyter or any compatible IDE (e.g., Visual Studio Code with Jupyter extension).

Run the cells in sequence:

- The first cell imports the required libraries and loads the API key.
- The second cell validates the API key.
- The third cell initializes the OpenAI client.
- The fourth cell generates a mock email.
- The fifth cell summarizes the email and proposes a response.
- View the generated email, its summary, and the proposed response in the notebook's output.


### Example Output

Generated Email : 

``` bash
Dear Carlos,

Espero que te encuentres bien. Quería tomarme un momento para agradecerte por tu apoyo en el proyecto de desarrollo de software que hemos estado ejecutando. Tu experiencia fue invaluable y los comentarios que proporcionaste al equipo realmente marcaron la diferencia.

Además, quería preguntarte si estarías disponible para una reunión la próxima semana, el martes 10 de octubre, a las 10:00 a.m. en nuestra oficina de Madrid. Me gustaría discutir algunas actualizaciones y asegurarme de que todos estemos alineados antes de la próxima fase del proyecto.

Aprecio mucho tu colaboración y espero tu respuesta.

Saludos cordiales,

Mark Thompson  
Project Manager  
Tech Innovations Ltd.
```

### Summary
Mark Thompson, the Project Manager at Tech Innovations Ltd., expressed appreciation for Carlos's support on the software development project, highlighting the value of his expertise and feedback. He also requested a meeting on Tuesday, October 10th, at 10:00 a.m. in their Madrid office to discuss updates and ensure alignment for the next phase of the project.


### Proposed Response

``` bash
Estimado Mark,

Gracias por tus amables palabras. Fue un placer colaborar en el proyecto. 

Confirmo mi disponibilidad para la reunión el martes 10 de octubre a las 10:00 a.m. en la oficina de Madrid. Espero con interés discutir las actualizaciones contigo.

Saludos cordiales,

Carlos
```

License
This project is licensed under the MIT License. See the LICENSE file for details. 