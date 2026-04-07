# Model Card – Hiring Bias Detection Model

## Model Details
- Model Type: Logistic Regression
- Developed for: Educational / Demonstration purposes
- Tool Used: Fairlearn

## Intended Use
This model is designed to simulate a hiring decision system based on candidate features.

## Features Used
- Gender
- Experience

## Performance
The model predicts whether a candidate is selected or not based on input features.

## Ethical Considerations
The inclusion of gender as a feature introduces bias in decision-making.

## Fairness Evaluation
- Male selection rate: 1.0
- Female selection rate: 0.0

This indicates a strong bias in favor of male candidates.

## Limitations
- Small dataset
- Biased feature (gender)
- Not suitable for real-world deployment

## Risks
- Discrimination against female candidates
- Unfair hiring practices

## Mitigation Strategies
- Remove gender feature
- Use fairness-aware algorithms
- Regular audits of model behavior
