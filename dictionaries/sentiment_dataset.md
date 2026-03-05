# Data Dictionary — sentiment_dataset.csv

## Columns
- `text`: input text
- `label`: one of {positive, neutral, negative}
- `notes`: optional rater notes / ambiguity

## Label rules
- positive: overall positive sentiment
- neutral: factual/mixed/no clear sentiment
- negative: overall negative sentiment

## Common edge cases
- sarcasm
- mixed sentiment
- implicit negativity without explicit language
