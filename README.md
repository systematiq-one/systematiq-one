<div align="center">
    
![Coding](coding.gif)

</div>

```python
!/usr/bin/env python3

import sys
from time import sleep


class Operative:

    __slots__ = ("_id", "_role", "_certs", "_channels", "_lang")

    def __init__(self) -> None:
        self._id       = "systematiq"
        self._role     = "Data Scientist · Claude Architect"
        self._certs    = ("Google::AI", "IBM::Agentic-AI", "Google::Data-Analytics")
        self._channels = {"web": "systematiq.one", "mail": "the@systematiq.one"}
        self._lang     = ("en_EN", "ro_RO", "ru_RU")

    def whoami(self) -> None:
        for line in (
            f"> id      : {self._id}",
            f"> role    : {self._role}",
            f"> certs   : {' / '.join(self._certs)}",
            f"> lang    : {' '.join(self._lang)}",
            f"> web     : {self._channels['web']}",
            f"> mail    : {self._channels['mail']}",
        ):
            sleep(0.04)
            print(line)

    def __repr__(self) -> str:
        return "<Operative systematiq :: [ REDACTED ] >"

    def disconnect(self) -> None:
        print("\n> signal lost. the rest is silence.")
        sys.exit(0)


if __name__ == "__main__":
    node = Operative()
    node.whoami()
    node.disconnect()
```


<!-- systematiq -->


<div align="center">

<img src="coding.gif" width="500"/>

---

Data Scientist · Claude Architect

[![Website](https://img.shields.io/badge/systematiq.one-000000?style=flat&logo=About.me&logoColor=white)](https://systematiq.one)
[![Email](https://img.shields.io/badge/the@systematiq.one-EA4335?style=flat&logo=Gmail&logoColor=white)](mailto:the@systematiq.one)
</div>

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=Pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=Streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat&logo=Arch-Linux&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=GNU-Bash&logoColor=white)
![JetBrains](https://img.shields.io/badge/JetBrains-000000?style=flat&logo=JetBrains&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat&logo=Obsidian&logoColor=white)

---

## Certifications

[![Google AI](https://img.shields.io/badge/Google_AI-4285F4?style=flat&logo=Google&logoColor=white)](https://alex.braguta.com/certificates/google-ai.pdf)
[![IBM Agentic AI](https://img.shields.io/badge/IBM_Agentic_AI-052FAD?style=flat&logo=IBM&logoColor=white)](https://alex.braguta.com/certificates/ibm-agentic-ai.pdf)
[![Google Data Analytics](https://img.shields.io/badge/Google_Data_Analytics-4285F4?style=flat&logo=Google&logoColor=white)](https://alex.braguta.com/certificates/google-data-analytics.pdf)

