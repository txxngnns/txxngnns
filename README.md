> writing code, breaking stuff, idling

```python
class Profile:
    def __init__(self):
        self.stack = ["Python", "Lua", "SQF", "DM", "HTML"]
        self.tools = ["VS Code", "Git"]
        self.status = "idling"

    def current_activity(self):
        return "shitcoding useless tools & reading docs"
