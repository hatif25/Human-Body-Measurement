# 3D Body Measurements from Images

Extract **22+ accurate body measurements** (height, waist, chest, etc.) from a single 2D photo using AI.  
Outputs: **3D model (.obj) + measurements (CSV) + visual report**.

## How It Works
1. **Input**: Full-body image (tight clothing, neutral pose)
2. **AI Processing**:  
   - HMR model predicts 3D body shape (SMPL)  
   - Custom logic calculates metrics from 3D mesh
3. **Output**:  
   - Real-world measurements (cm/inch)  
   - 3D model for visualization  

## Quick Start
```bash
pip install -r requirements.txt
python run.py --image person.jpg --height_cm 175
