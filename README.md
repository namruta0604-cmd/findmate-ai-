# FindMate AI — Quick Run Instructions

Project directory: `C:\Users\first\.gemini\antigravity\scratch\findmate-ai`

### 1. Start the Flask AI Backend (Terminal 1)
```powershell
cd C:\Users\first\.gemini\antigravity\scratch\findmate-ai\backend
py -m pip install flask flask-cors
py app.py
```
* The API will run at `http://localhost:5000`.

### 2. Start the React Frontend Dashboard (Terminal 2)
```powershell
cd C:\Users\first\.gemini\antigravity\scratch\findmate-ai\frontend-app
cmd.exe /c "npm run dev"
```
* Open `http://localhost:5173` in your web browser.

---

### Key Capabilities Built
1. **Explainable AI Matching**: Weighted formula combining NLP description similarity (35%), age compatibility (20%), location proximity (20%), date delta (15%), and clothing overlap (10%).
2. **Side-by-side Case Comparison**: Visual percentage breakdown for each feature.
3. **Interactive Intake**: Forms to submit new missing person reports and found person records.
4. **Mock Dataset**: Pre-seeded with realistic cases for immediate live demonstration.
