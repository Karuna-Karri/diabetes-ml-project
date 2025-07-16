
This project helps you learn **Building and Deploying an ML Model** using a simple and real-world use case: predicting whether a person is diabetic based on health metrics. We’ll go from:

 ✅ Model Training
 ✅ Building the Model locally
 ✅ API Deployment with FastAPI
 
1. Clone the Repo

git clone  https://github.com/Karuna-Karri/diabetes-ml-project
cd diabetes-ml

2. Create Virtual Environment

python -m venv venv
source venv/Scripts/activate

3. Install Dependencies

pip install  uvicorn

Train the Model
python train.py


Run the API Locally
 python -m uvicorn main:app --reload

 Sample Input for /predict

{
  "Pregnancies": 2,
  "Glucose": 130,
  "BloodPressure": 70,
  "BMI": 28.5,
  "Age": 45
}


 
