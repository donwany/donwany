### Hi there 👋

```python
from dataclasses import dataclass, field
from typing import List


@dataclass
class DataProf:
    name: str = "Theophilus Siameh"
    current_role: str = "ML Consultant"
    passions: List[str] = field(
        default_factory=lambda: [
            "artificial-intelligence",
            "data-science",
            "edge-computing",
            "LLMs"
        ]
    )

    def say_hi(self):
        return "Hi! Thanks for dropping by.  👋"


me = DataProf()
print(me.say_hi())
```

<!--
**donwany/donwany** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
