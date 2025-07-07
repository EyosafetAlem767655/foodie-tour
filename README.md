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
export JULEP_API_KEY="your_julep_key_here"
# $Env:JULEP_API_KEY="your_julep_key_here"  # Windows PowerShell

# 4. Launch the app
voila FoodieTour.ipynb
