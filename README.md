# Foodie Tour Generator

A one-day “foodie tour” web app built as a Jupyter notebook, served via Voila.  
Enter three cities and get:
1. Indoor/outdoor dining suggestion  
2. 3 iconic dishes per city  
3. Top restaurants (if available)  
4. Interactive map with Google-style pins  
5. A breakfast-lunch-dinner narrative

## 🚀 Quickstart

```bash
# 1. Clone
git clone https://github.com/EyosafetAlem767655/foodie-tour.git
cd foodie-tour

# 2. Create venv & install
python3 -m venv venv
source venv/bin/activate       # macOS/Linux
# .\venv\Scripts\Activate.ps1  # Windows PowerShell
pip install -r requirements.txt

# 3. Set your Julep key
export JULEP_API_KEY="eyJhbGciOiJIUzUxMiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMmQyNmE1Mi1lZjFlLTU5MmItOWVmYS0wY2MwMGY1YjIyZWEiLCJlbWFpbCI6ImV5b3NhZmV0YWxlbUBnbWFpbC5jb20iLCJpYXQiOjE3NTE4NzQzOTksImV4cCI6MTc1MjQ3OTE5OX0.q1YrKA0ZhxBPkomGfhjvhFVyoO4rHj_t5rIeR3BKcFijNFvguTOG9Mio9VaVFSZvkeXXUOyBEkHv2x6q86IUBg"
# $Env:JULEP_API_KEY="eyJhbGciOiJIUzUxMiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMmQyNmE1Mi1lZjFlLTU5MmItOWVmYS0wY2MwMGY1YjIyZWEiLCJlbWFpbCI6ImV5b3NhZmV0YWxlbUBnbWFpbC5jb20iLCJpYXQiOjE3NTE4NzQzOTksImV4cCI6MTc1MjQ3OTE5OX0.q1YrKA0ZhxBPkomGfhjvhFVyoO4rHj_t5rIeR3BKcFijNFvguTOG9Mio9VaVFSZvkeXXUOyBEkHv2x6q86IUBg"  # Windows PowerShell

# 4. Launch the app
voila FoodieTour.ipynb
