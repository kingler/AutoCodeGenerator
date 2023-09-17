# Auto Code Generator
This project is an automatic code generation system that uses the OpenAI API. The system can generate pseudo code and final code, organize the generated code files, select the best model for generating the final code, and evaluate and eliminate pseudo code.
## Scripts
- `Auto_Coder_V.4.py`: The main script that orchestrates the whole process.
- `auto_coder_tools/final_code.py`: Generates the final Python code based on the winning pseudo code.
- `auto_coder_tools/instruction_gen.py`: Generates instructions for pseudo code based on user input.
- `auto_coder_tools/pseudo_eval_eliminate.py`: Evaluates and eliminates pseudo code based on certain criteria.
- `auto_coder_tools/pseudo_gen_concurrent.py`: Generates pseudo code concurrently based on user instructions.
- `auto_coder_tools/write_competitors_to_files.py`: Writes the pseudo code of each competitor to separate files.
## Dependencies
The Python packages that the project depends on are listed in the `requirements.txt` file.
