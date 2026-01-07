# calculator

## DevOps : Culture, Méthodes et Outils - TD1
Ce TD a pour but de nous faire manipuler GitHub afin de :
 - collaborer efficacement sur un dépôt GitHub
 - configurer un environnement de développement reproductible
 - appliquer les bonnes pratiques Git (branches, commits, PR)
 - utiliser les tests unitaires dans un workflow DevOps
 - sécuriser l’intégration du code via une Pull Request

### Installation des dépendances
```bash
pip install -r requirements.txt
```

### Exécuter l'application
#### Sum
Example : 
```bash
python src/main.py -op sum -val1 1 -val2 2
```

#### Moy
Example :
```bash
python src/main.py -op moy -val1 1 -val2 2
```

### Exécuter les tests
```bash
python -m coverage run -m unittest tests/test_calculator.py
coverage report -m
```
