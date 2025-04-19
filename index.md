# Communicate using Markdown
_Organize ideas and collaborate using Markdown, a lightweight language for text formatting._

## Testing adding an Image
![Here's some Ramen to get started](https://images.unsplash.com/photo-1617421753170-46511a8d73fc?q=80&w=3538&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

## Adding code snippet
```python
import time
import os

def animate_text(text, cycles=3):
    for _ in range(cycles):
        for frame in range(10):
            os.system('cls' if os.name == 'nt' else 'clear')
            offset = frame % len(text)
            print(text[offset:] + text[:offset])
            time.sleep(0.1)

animate_text("* Hello, Python is amazing! *")
```

## Adding a task list
- [x] Point 1
- [ ] Point 2
