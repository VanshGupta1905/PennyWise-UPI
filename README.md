# PennyWise-UPI

 ## Project Link
    https://penny-wise-upi.streamlit.app/

### UPI Application with Payment Analysis Dashboard

Welcome to the **UPI Application with Payment Analysis Dashboard**! This project combines a UPI-like system for managing user accounts and transactions with interactive dashboards to analyze payment trends. 🎉

---

## Features 🚀

### **1. UPI Application**  
A mock implementation of a UPI system with the following functionalities:  
- **Add Account**: Create a new user with UPI ID, phone number, and name.  
- **Request Money**: Request a specific amount from another user.  
- **Approve/Reject Requests**: Handle pending payment requests.  
- **Check Balance**: View your current balance.  
- **Transaction History**: Review past transactions.  
- **Profile Management**: Update user details like name and phone number.  
- **Generate QR Code**: Create QR codes for UPI IDs.  
- **View All Users**: Explore all registered users (mock data).

> Note: This is a demo version and does not connect to real banking APIs. 🙃

---

### **2. Payment Services Analysis Dashboard**  
Visualize payment trends using dummy datasets.  
- Analyze transaction volumes, customer engagement, and market share.  
- View insights for different banks or payment gateways over 2020 and 2021.  
- Graphs include line plots, bar charts, and pies for a clear picture of trends.  

---

### **3. Personal Payment Analysis**  
Explore personal financial data (with dummy records):  
- Monthly income vs. expenses.  
- Category-wise spending trends.  
- Daily and monthly transaction patterns.  
- Balance tracking over time.

---

## Demo Instructions 👨‍💻
1. Clone the repo:
   ```bash
   git clone https://github.com/VanshGupta1905/PennyWise-UPI.git
   cd upi-dashboard
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```
4. Open the app in your browser at [localhost:8501](http://localhost:8501).  

---

## About the Data 📊
The project uses **dummy datasets** for demonstration purposes. Feel free to replace them with real data for meaningful analysis.  
- `data.csv` and `data_2.csv`: Mock data for payment gateway analysis (2020-2021).  
- `personal_data.csv`: Sample data for personal payment tracking.

---

## Future Scope 🌟
- Integrating with real UPI/IMPS APIs for actual transactions.  
- Adding advanced analytics and machine learning models for trend predictions.  
- Supporting multiple user roles (e.g., merchants, admins).

---

This project is a fun way to explore UPI systems and payment analytics. Contributions and feedback are always welcome! 
