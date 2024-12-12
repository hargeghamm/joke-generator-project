# joke-generator-project
# Joke Generator with GPT-2 A fine-tuned GPT-2 model for generating creative and humorous jokes.
## Setup
1. Clone the repository:

2. Install dependencies:

3. (Optional) Enable GPU for faster performance.

## Usage
- Train the model:

- Generate jokes:
python scripts/generate.py --prompt "Why did the chicken cross the road?"



model.push_to_hub("joke-generator-model")
tokenizer.push_to_hub("joke-generator-model")
