# **Data Sweeper** 🧹📊

**Data Sweeper** is a **Streamlit-based web application** that allows users to upload, clean, visualize, and convert CSV and Excel files effortlessly. The app provides data cleaning features such as duplicate removal and filling missing values, along with file format conversion and visualization.

## **Features** 🚀
✅ Upload multiple files (CSV & Excel)  
✅ Clean data (remove duplicates, fill missing values)  
✅ Select specific columns for conversion  
✅ Visualize numerical data using bar charts  
✅ Convert files between CSV and Excel formats  
✅ Download the cleaned and converted files  

## **Installation** 🛠️

### **1. Clone the Repository**
```sh
git clone https://github.com/your-username/data-sweeper.git
cd data-sweeper
```

### **2. Create a Virtual Environment (Optional)**
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### **3. Install Dependencies**
```sh
pip install -r requirements.txt
```

## **Usage** ▶️
Run the Streamlit app using:
```sh
streamlit run app.py
```
Then open the **local URL** provided in the terminal (e.g., `http://localhost:8501`).

## **Project Structure** 📂
```
data-sweeper/
│── app.py                # Main Streamlit app
│── requirements.txt      # Required Python packages
│── README.md             # Project documentation
```

## **Requirements** 📌
The app uses the following Python libraries:
- **streamlit**
- **pandas**
- **openpyxl** (for Excel support)

Install dependencies using:
```sh
pip install streamlit pandas openpyxl
```

## **Screenshots** 🖼️
(Add screenshots of your app running to make it more appealing!)

## **Contributing** 🤝
Feel free to fork this repository, submit issues, or contribute by making pull requests.

## **License** 📝
This project is licensed under the **MIT License**.
