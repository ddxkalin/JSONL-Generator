# JSONL - Generator

The purpose of this JSONL - Generator is to generate two output files: `train_file.jsonl` and `valid_file.jsonl`.
The output files are going to be used for fine tunning an local LLM on MacOS using the Apple’s MLX framework.

The Input for the generator should be an JSON file called `instructions.json` which will contain questions generated via Llama3-8b LLM.
