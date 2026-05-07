# 🚀 QUICK START GUIDE - ASD Screening Prediction System

## ⚡ Fastest Way to Get Started (2 options)

### Option 1: Double-Click (Easiest)
1. Double-click `run_app.bat` (on Windows Command Prompt)
2. The app will automatically open in your browser

### Option 2: PowerShell (Recommended)
1. Right-click `run_app.ps1`
2. Select "Run with PowerShell"
3. The app will automatically open in your browser

---

## ✅ Manual Setup (If the above doesn't work)

### Step 1: Open Command Prompt/PowerShell
- Windows: Press `Win + R`, type `cmd` or `powershell`, press Enter
- Or: Search for "Command Prompt" or "PowerShell" in Windows Search

### Step 2: Navigate to Project Folder
```bash
cd e:\Downloads\Chhaya_project_deploment
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Start the App
```bash
streamlit run streamlit_app.py
```

### Step 5: Open in Browser
- The browser should open automatically
- If not, go to: http://localhost:8501

---

## 🎯 Once the App is Running

### 1️⃣ Home Page
- Understand the dataset
- View feature information

### 2️⃣ Model Training (First Time)
- Click "Train All Models" button
- Wait 2-5 minutes for training to complete
- View performance results

### 3️⃣ Make Prediction
- Adjust slider values for screening features
- Click "Predict" button
- See predictions from both ML models and ANN

### 4️⃣ Model Comparison
- View ROC curves
- Compare model performance metrics
- See visual rankings

---

## 🆘 Troubleshooting

| Problem | Solution |
|---------|----------|
| "Python not found" | Install Python from python.org |
| "pip command not found" | Python not in PATH. Reinstall Python with "Add Python to PATH" checked |
| "Module not found" | Run: `pip install -r requirements.txt` again |
| "CSV file not found" | Make sure `Autism_Screening_Data_Combined.csv` is in the same folder |
| Port 8501 already in use | Run: `streamlit run streamlit_app.py --server.port 8502` |
| TensorFlow installation slow | Be patient, it's a large library (5-15 minutes) |
| App won't open in browser | Manually go to http://localhost:8501 |

---

## 🌐 Accessing from Other Devices (Advanced)

To access from another computer on your network:

1. Find your computer's IP address:
   - Windows: Open CMD and type `ipconfig`
   - Look for IPv4 Address (usually starts with 192.168.x.x)

2. On another device, go to:
   ```
   http://YOUR_IP_ADDRESS:8501
   ```
   Example: http://192.168.1.100:8501

---

## 💡 Pro Tips

✅ First load will train models automatically  
✅ Subsequent loads will be faster (cached)  
✅ Keep browser tab open while making predictions  
✅ Use Ctrl+C in terminal to stop the server  
✅ Close app with the X button or Ctrl+C  

---

## 📞 Need More Help?

1. Check the full README.md file
2. Visit: https://docs.streamlit.io/
3. Verify all files are in the correct directory

---

## 📊 What This App Does

- ✅ Trains 8 ML models
- ✅ Trains an Artificial Neural Network
- ✅ Compares model performance
- ✅ Makes predictions on new data
- ✅ Visualizes results with charts
- ✅ All from a web browser!

---

**Enjoy! 🎉**
