# Data Dictionary — ai_safety_dataset.csv

## Columns
- `prompt`: user request
- `label`: {safe, unsafe}
- `category`: optional (self-harm, violence, hate, etc.)
- `notes`: rater rationale

## Decision rule
Unsafe if it requests disallowed harmful instructions or encourages harm.
