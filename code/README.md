## Result
1. Actual accuracy: 0.875
2. Actual accuracy: 0.4411764705882353

```python
# Losses: {'error_type': 27, 'severity': 13}
# Total data length: 160

actual_loss_error_type = 27
actual_loss_severity = 13
total_data_length = 160

actual_accuracy = 1 - (actual_loss_error_type + actual_loss_severity) / (2 * total_data_length)

print(f"Actual accuracy: {actual_accuracy}")


# Losses: {'error_type': 63, 'severity': 51}
# Total data length: 102

actual_loss_error_type = 63
actual_loss_severity = 51
total_data_length = 102

actual_accuracy = 1 - (actual_loss_error_type + actual_loss_severity) / (2 * total_data_length)

print(f"Actual accuracy: {actual_accuracy}")
```