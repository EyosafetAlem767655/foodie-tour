```markdown
# Foodie Tour Generator

A one‐day “foodie tour” web app built as a Jupyter notebook and served via [Voilà](https://github.com/voila-dashboards/voila).  
Enter three cities and instantly get:
1. Indoor/outdoor dining suggestion based on today’s weather  
2. Three iconic local dishes per city  
3. Top‐rated restaurants (if available) displayed on an interactive map with Google-style pins  
4. A breakfast–lunch–dinner narrative  

---

## 📦 Repository Structure

```

foodie-tour/
├── .gitignore
├── README.md
├── requirements.txt
└── FoodieTour.ipynb

````

- **`.gitignore`** — ignores caches, virtual‐envs, notebook checkpoints  
- **`requirements.txt`** — all Python dependencies  
- **`FoodieTour.ipynb`** — the interactive notebook UI  
- **`README.md`** — this file  

---

## 🛠️ Prerequisites

- **Python 3.8+**  
- **git**  
- **A GitHub account** (to clone/push if desired)  
- **Jupyter Notebook/Lab** (optional, only if you want to run it as a notebook)  

---

## 🚀 Quickstart

1. **Clone the repo**  
   ```bash
   git clone https://github.com/EyosafetAlem767655/foodie-tour.git
   cd foodie-tour
````

2. **Create & activate a virtual environment**

   * macOS / Linux

     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   * Windows PowerShell

     ```powershell
     python -m venv venv
     Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
     . .\venv\Scripts\Activate.ps1
     ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Register the notebook kernel**

   ```bash
   pip install ipykernel
   python -m ipykernel install --user --name foodie-tour --display-name "Python (foodie-tour)"
   ```

5. **Set your Julep API key**
   Obtain your key from [Julep](https://docs.julep.ai) and export it:

   * macOS / Linux

     ```bash
     export JULEP_API_KEY="eyJhbGciOiJIUzUxMiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMmQyNmE1Mi1lZjFlLTU5MmItOWVmYS0wY2MwMGY1YjIyZWEiLCJlbWFpbCI6ImV5b3NhZmV0YWxlbUBnbWFpbC5jb20iLCJpYXQiOjE3NTE4NzQzOTksImV4cCI6MTc1MjQ3OTE5OX0.q1YrKA0ZhxBPkomGfhjvhFVyoO4rHj_t5rIeR3BKcFijNFvguTOG9Mio9VaVFSZvkeXXUOyBEkHv2x6q86IUBg"
     ```
   * Windows PowerShell

     ```powershell
     $Env:JULEP_API_KEY="eyJhbGciOiJIUzUxMiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMmQyNmE1Mi1lZjFlLTU5MmItOWVmYS0wY2MwMGY1YjIyZWEiLCJlbWFpbCI6ImV5b3NhZmV0YWxlbUBnbWFpbC5jb20iLCJpYXQiOjE3NTE4NzQzOTksImV4cCI6MTc1MjQ3OTE5OX0.q1YrKA0ZhxBPkomGfhjvhFVyoO4rHj_t5rIeR3BKcFijNFvguTOG9Mio9VaVFSZvkeXXUOyBEkHv2x6q86IUBg"
     ```

6. **Trust the notebook** (optional—suppresses Voilà warnings)

   ```bash
   jupyter trust FoodieTour.ipynb
   ```

7. **Launch the app with Voilà**

   ```bash
   voila FoodieTour.ipynb
   ```

   Voilà will build and serve a standalone web app. By default it opens at:

   ```
   http://localhost:8866
   ```

8. **(Alternative) Run as a standard notebook**

   ```bash
   jupyter notebook        # or `jupyter lab`
   ```

   Then open `FoodieTour.ipynb`, “Run All” cells, and interact within the notebook UI.

---

## 📋 requirements.txt

```
julep
requests
geopy
folium
ipywidgets
voila
ipykernel
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to your branch: `git push origin feature/YourFeature`
5. Open a Pull Request

---

