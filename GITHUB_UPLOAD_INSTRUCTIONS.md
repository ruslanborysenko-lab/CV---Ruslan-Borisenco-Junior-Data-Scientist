# 📤 GitHub Upload Instructions

## Przygotowanie do publikacji CV na GitHub

### ✅ Pliki gotowe do upload

W folderze `/Users/borysenkoruslan/Desktop/od_zera_do_ai/modul_12/CV/` znajdują się:

```
✓ cv_ruslan_borisenco_PL.ipynb          # Polski notebook CV
✓ cv_ruslan_borisenco_EN.ipynb          # Angielski notebook CV
✓ cv_structure.ipynb                    # Szablon (opcjonalny)
✓ LinkedIn_Job_Description_Junior_Data_Scientist.txt
✓ PROJECT_DESCRIPTION_CV_LINKEDIN_*.txt (9 plików)
✓ requirements.txt                      # Zależności Python
✓ README.md                             # Dokumentacja repozytorium
✓ .gitignore                            # Reguły ignorowania plików
```

---

## 🚀 Krok po kroku - Upload na GitHub

### Opcja 1: GitHub Web Interface (najprostsze)

1. **Utwórz nowe repozytorium na GitHub**
   - Przejdź na https://github.com/new
   - Repository name: `cv`
   - Description: `Professional CV - Junior Data Scientist | 9 ML/AI Projects`
   - Visibility: Public lub Private (wybierz według preferencji)
   - **NIE** zaznaczaj "Add a README file" (mamy już własny)
   - Kliknij "Create repository"

2. **Upload plików przez web interface**
   - Na stronie nowego repo kliknij "uploading an existing file"
   - Przeciągnij wszystkie pliki z folderu CV
   - Commit message: `Initial CV upload - 9 projects portfolio`
   - Kliknij "Commit changes"

### Opcja 2: Git Command Line (profesjonalne)

1. **Inicjalizacja Git w folderze CV**
```bash
cd /Users/borysenkoruslan/Desktop/od_zera_do_ai/modul_12/CV
git init
git add .
git commit -m "Initial CV upload - 9 projects portfolio"
```

2. **Połączenie z GitHub**
```bash
# Utwórz repo na GitHub (patrz Opcja 1, punkt 1)
# Następnie:
git remote add origin https://github.com/ruslanborysenko-lab/cv.git
git branch -M main
git push -u origin main
```

---

## 📝 Przed publikacją - Checklist

### Sprawdź i zaktualizuj (jeśli potrzeba):

- [ ] **Email** w README.md: `ruslanborysenko@gmail.com` ✓
- [ ] **Telefon** w README.md: `730 837 748` ✓
- [ ] **LinkedIn** w README.md: `linkedin.com/in/ruslan-borisenco-60a56319b` ✓
- [ ] **GitHub username** w README.md: `ruslanborysenko-lab` ✓
- [ ] **Uruchom notebooki** aby wygenerować `.md` pliki:
  ```bash
  jupyter notebook cv_ruslan_borisenco_PL.ipynb
  # Run all cells, zapisz plik .md
  jupyter notebook cv_ruslan_borisenco_EN.ipynb
  # Run all cells, zapisz plik .md
  ```

### Opcjonalnie dodaj:

- [ ] Screenshot wygenerowanego CV (PNG/PDF) do folderu `screenshots/`
- [ ] LICENSE file (MIT lub Apache 2.0)
- [ ] CHANGELOG.md jeśli planujesz aktualizacje

---

## 🎯 Po publikacji

### 1. Sprawdź repo
Odwiedź: `https://github.com/ruslanborysenko-lab/cv`

### 2. Dodaj link do LinkedIn
W sekcji "Featured" na LinkedIn dodaj:
- Tytuł: "My CV - 9 ML/AI Projects"
- URL: `https://github.com/ruslanborysenko-lab/cv`

### 3. Wygeneruj PDF
```bash
# Z poziomu folderu CV:
pandoc cv_ruslan_borisenco_PL.md -o cv_ruslan_borisenco_PL.pdf
pandoc cv_ruslan_borisenco_EN.md -o cv_ruslan_borisenco_EN.pdf
```

### 4. Dodaj badges do README (opcjonalnie)
```markdown
![GitHub last commit](https://img.shields.io/github/last-commit/ruslanborysenko-lab/cv)
![GitHub repo size](https://img.shields.io/github/repo-size/ruslanborysenko-lab/cv)
```

---

## 🔒 Prywatność

### Jeśli chcesz ukryć dane osobowe w public repo:

W **README.md** zmień:
```markdown
# BYŁO:
- **Email**: ruslanborysenko@gmail.com
- **Phone**: 730 837 748

# ZMIEŃ NA:
- **Email**: Available on request
- **Phone**: Available on request
```

W **notebookach** (`.ipynb`) zmień:
```python
# BYŁO:
email: ruslanborysenko@gmail.com <br>
tel: 730 837 748 <br>

# ZMIEŃ NA:
email: [available on request] <br>
tel: [available on request] <br>
```

---

## ✨ Tips & Best Practices

1. **Repository name**: `cv` jest krótkie i proste
2. **Description**: Użyj keywords: `data-science`, `machine-learning`, `portfolio`, `cv`, `resume`
3. **Topics/Tags**: Dodaj na GitHub: `data-science`, `machine-learning`, `python`, `jupyter-notebook`, `cv`, `resume`, `portfolio`
4. **README**: Mamy już profesjonalny README.md z pełną dokumentacją
5. **Updates**: Gdy dodasz nowe projekty, zaktualizuj notebooki i wygeneruj nowe CV

---

## 🆘 Troubleshooting

### Problem: "git command not found"
**Rozwiązanie**: Zainstaluj Git:
```bash
# macOS
brew install git

# Lub pobierz z https://git-scm.com/
```

### Problem: "Permission denied (publickey)"
**Rozwiązanie**: Skonfiguruj SSH lub użyj HTTPS:
```bash
# HTTPS (prostsze):
git remote set-url origin https://github.com/ruslanborysenko-lab/cv.git
```

### Problem: Notebook nie generuje .md pliku
**Rozwiązanie**: Sprawdź czy ostatnia komórka się wykonała:
```python
with open("cv_ruslan_borisenco_PL.md", "w", encoding="utf-8") as f:
    f.write(cv_md)
```

---

## 📞 Potrzebujesz pomocy?

Jeśli masz problemy z uploadem:
1. Sprawdź dokumentację GitHub: https://docs.github.com/en/get-started
2. Użyj GitHub Desktop app (GUI alternative): https://desktop.github.com/
3. Skontaktuj się ze mną na LinkedIn

---

**Powodzenia z publikacją CV! 🚀**

Data utworzenia: Grudzień 2025  
Autor: Ruslan Borisenco
