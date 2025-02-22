# IARagMysqlQuestion

This project demonstrates how to build a chatbot that interacts with a MySQL database using LangGraph, LangSmith, LangChain-GROQ, and other Python libraries.

## Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/melenas1414/IARagMysqlQuestion
   cd IARagMysqlQuestion
   ```

2. **Create a virtual environment and activate it:**

   ```sh
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
   ```

3. **Install the required dependencies:**

   ```sh
   pip install -U langgraph langsmith langchain-groq mysql-connector-python python-dotenv
   ```

4. **Set up environment variables:**

   Copy the `env.example` file to `.env` and fill in the required values.

   ```sh
   cp env.example .env
   ```

   Edit the `.env` file to include your MySQL database credentials and other necessary configurations.

   ```plaintext
   GROQ_API_KEY=your_groq_api_key
   MYSQL_HOST=your_mysql_host
   MYSQL_USER=your_mysql_user
   MYSQL_PASSWORD=your_mysql_password
   MYSQL_DB=your_mysql_db
   MYSQL_PORT=your_mysql_port
   TABLES=your_table_names_comma_separated
   ```

## Usage

1. **Run the Jupyter Notebook:**

   Open the `chatwithgroq-getsql.ipynb` notebook in Jupyter and run the cells to interact with the chatbot.

   ```sh
   jupyter notebook chatwithgroq-getsql.ipynb
   ```

2. **Interact with the chatbot:**

   Follow the instructions in the notebook to ask questions about the database and receive SQL queries and natural language responses.

## Project Structure

- `env.example`: Example environment variables file.
- `chatwithgroq-getsql.ipynb`: Jupyter Notebook demonstrating the chatbot interaction.
- `README.md`: This file.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](./LICENSE) file for details.
