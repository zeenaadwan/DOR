
## Steps to Run the Chat UI

1. Fork this repository or create a code space in GitHub.

2. Install the required Python packages by running the following command in your terminal:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the project directory. You can use the `example.env` file as a reference. Add your Hugging Face API token to the `.env` file in the following format:
   ```
   HUGGINGFACEHUB_API_TOKEN=your_huggingface_token
   ```

4. Run the following command in your terminal to start the chat UI:
   ```
   chainlit run app.py -w
   ```

