### Hi there 👋

![Data Science](https://img.shields.io/badge/Data%20Science-Passing-success)

```python
class DanteGrasselli:

    def __init__(self):
        self.name = 'Dante Grasselli'
        self.position = 'AI & ML Associate Manager | Data Scientist | Artificial Intelligence | AIOps | Generative AI'
        self.linkedin = 'https://www.linkedin.com/in/dantegrasselli/'
        self.location = 'São Paulo, Brasil'
        self.code = {
            'languages': ['Python', 'SQL', 'R'],
            'platforms': ['Dynatrace', 'Azure', 'AWS'],
            'skills': ['API REST', 'Big Data', 'Machine Learning', 'AIOps', 'Generative AI'],
            'tools': ['TensorFlow', 'PyTorch', 'Scikit-learn', 'Pandas']
        }
        self.languages = ['Português', 'Espanhol', 'Inglês']
        self.certifications = [
            'Big Data Fundamentos 2.0',
            'Python 3 - Curso Completo do Básico ao Avançado'
        ]
        self.publications = [
            'Avaliação do potencial de utilização de chá verde como substituo parcial ou total de lúpulo em cerveja tipo pilsner'
        ]
        
    def experience(self):
        return {
            'Accenture Brasil': [
                {
                    'role': 'AI & ML Associate Manager',
                    'period': 'dezembro de 2022 - Presente'
                },
                {
                    'role': 'Data & AI Specialist',
                    'period': 'dezembro de 2021 - novembro de 2022'
                },
                {
                    'role': 'Data & AI Analyst',
                    'period': 'maio de 2018 - novembro de 2021'
                }
            ]
        }
        
    def education(self):
        return [
            {
                'institution': "Let's Code",
                'degree': 'Especialização, Data Science',
                'period': '2019 - 2021'
            },
            {
                'institution': 'Universidade Brasil',
                'degree': 'Química Industrial, Química',
                'period': '2012 - 2015'
            },
            {
                'institution': 'Gama Academy',
                'degree': 'Extensão, Inteligência Artificial',
                'period': '2018 - 2018'
            }
        ]

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = DanteGrasselli()
    print(me)
```
