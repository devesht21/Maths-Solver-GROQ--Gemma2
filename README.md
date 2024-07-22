
# # Maths Solver Assistant using Langchain and Gemma 2

This project is a Streamlit application that allows users to solve mathematical problems and search for information using the Langchain framework and Groq API. The application integrates multiple tools, including a math problem solver and a Wikipedia search assistant, to provide comprehensive answers to user queries.


You can check the live project [here](https://maths-solver-groq--gemma2.streamlit.app/)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

- Python 3.10 or higher
- [Streamlit](https://streamlit.io/)
- [Langchain](https://github.com/hwchase17/langchain)
- [dotenv](https://pypi.org/project/python-dotenv/)
- [pypdf](https://pypi.org/project/pypdf/)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/devesht21/Maths-Solver-GROQ--Gemma2
   cd Maths-Solver-GROQ--Gemma2

2. Create a virtual environment:

    ```bash
    conda create -p venv python==3.10.0 -y
    conda activate venv

3. Install the required packages:

    ```bash
    pip install -r requirements.txt


4. Run the Streamlit application:

    ```bash
    streamlit run app.py


## Usage

1. Open your web browser and navigate to http://localhost:8501.
2. Enter your Groq API key in the sidebar input box.
3. Enter the question you want to solve in the text area provided.
4. Click the "Find my answer" button.
5. The application will display the response from the assistant agent, which includes a detailed explanation and solution to the math problem.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.



