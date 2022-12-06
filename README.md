<h1 align='center'> Aloha! :wave:</h1>


<h3>
    
```python
from dataclasses import dataclass,asdict
 
@dataclass
class DataScience:
    languages: tuple[str, ...] = ("Python", "R")
    tools    : tuple[str, ...] = ("ScikitLearn", "PyTorch", "SpaCy","HuggingFace", "Scrapy")
    databases: tuple[str, ...] = ("SQLite", "MySQL")
    skills   : tuple[str, ...] = ("Machine Learning", "Deep Learning", "Forecasting", "NLP", "Statistics")
    socialmedia  : str             = field(default="Anonymous!", 
                                       metadata={
                                        'Blogs': 'https://s-b-iqbal.github.io/Reflexione/',
                                        'Twitter': '@MusingIqbal'})


me = DataScience()
print(asdict(me))
```
</h3>

---

<!-- BLOGPOSTS:END -->


<!--
**S-B-Iqbal/S-B-Iqbal** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

