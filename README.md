

Fun command to check if GPUs are available and what they are.

```python
import torch
torch.cuda.is_available()
[print(torch.cuda.get_device_properties(i)) for i in range(torch.cuda.device_count())];
```
