# text-to-sql
llama + SQL + PyGWalker + Flask

**TO DO**
- [x] basic functioning flask application to load model, get text and convert to SQL
- [x] Search database based on schema and tables
- [x] Added manual verification process before executing the SQL query
- [x] change GPT to llama for sql generation
- [X] create a select all and unselect all functionality based on schema and tables
- [X] added few validations and preloader
- [X] change the db creds to come from UI instead of .env
- [ ] fine-tune code-llama-instruct model with custom SQL datasets
    - [X] prepared dataset "shiroyasha13/llama_text_to_sql_dataset" (will increase data size)
    - [X] prepared the fine-tuning code and tested the functionality in colab
    - [ ] fine-tuning "TheBloke/CodeLlama-7B-Instruct-GPTQ" (6-bit quuantized) model with SageMaker
    - [ ] test the updated model and based on results upload to huggingface and use the model
- [ ] Replace the standard code-llama-instruct-7B with fine-tuned model
- [ ] store the response history for current session ( testing feasibility )
- [ ] Adding documentation to code and this repo
