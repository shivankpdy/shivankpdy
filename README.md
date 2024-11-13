```python
from universe.galaxy.earth import Shivank

class Shivank:
    def __init__(self):
        self.profession = "Ethical Hacker and Programmer"
        self.company = "Ghost Squad, Inc."
        self.specialties = ["Machine Learning", "Web Development", "Ethical Hacking"]
        self.goals = [
            "Develop innovative software for Ghost Squad, Inc.",
            "Advance in the fields of AI and ML",
            "Create cutting-edge hacking tools"
        ]

    def coding_style(self):
        return {
            "language": "Python",
            "style_guide": "PEP 8",
            "code_quality_tools": ["pylint", "black", "flake8"]
        }

    def frameworks_and_tools(self):
        return {
            "ml_frameworks": ["TensorFlow", "Keras"],
            "web_frameworks": ["Django"],
            "ethical_hacking_tools": ["Metasploit", "Nmap", "Wireshark", "John the Ripper"]
        }

    def __str__(self):
        return (
            f"Hello, I'm Shivank, a {self.profession} at {self.company}.\n"
            f"My specialties include {', '.join(self.specialties)}.\n"
            f"My current goals are to:\n"
            + "\n".join([f"- {goal}" for goal in self.goals])
        )

shivank = Shivank()
print(shivank)
print("\nCoding Style Profile:", shivank.coding_style())
print("\nFrameworks & Tools:", shivank.frameworks_and_tools())
```
