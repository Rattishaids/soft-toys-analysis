# soft-toys-analysis
 ****📊 Soft Toys Analysis Report****
An interactive web-based data visualization dashboard built using React, Recharts, and Tailwind CSS to analyze soft toy product data from a CSV file.

# 🚀 Features
📈 Brand Performance Analysis
Visualizes top brands by frequency and market share.

# 💰 Price vs. Rating Correlation
Shows how product prices relate to customer ratings.

# 🌟 Review & Rating Leaders
Highlights top 5 products based on reviews and ratings.

# 📂 CSV Integration
Loads and parses soft_toys_data.csv using PapaParse.

# 🧰 Tech Stack
Frontend: HTML, Tailwind CSS, React (via CDN)

Visualization: Recharts (BarChart, PieChart, ScatterChart)

Data Parsing: PapaParse for CSV processing

JS Runtime: Babel (standalone for JSX support in browser)

# 📁 File Structure
bash
Copy
Edit
soft-toys-analysis/
│
├── index.html             # Main app (contains all code)
├── soft_toys_data.csv     # Your dataset file (place it locally)
└── README.md              # Project documentation
# 🛠️ How to Run
You can run this project locally without any server — just follow these steps:

Download or Clone the project:

bash
Copy
Edit
git clone https://github.com/your-username/soft-toys-analysis.git
cd soft-toys-analysis
Place your CSV file
Ensure soft_toys_data.csv is present in the same directory as index.html.

Open index.html in browser
Double-click or open it via any web browser:

perl
Copy
Edit
file:///.../soft-toys-analysis/index.html
✅ That’s it — your dashboard will load automatically!

# ⚠️ Notes
You must update the loadFileData() function in index.html to handle actual CSV reading logic. Currently, loadFileData("soft_toys_data.csv") won’t work unless the file is hosted or loaded manually.

For local file reading, consider using an <input type="file"> element or converting to a React/Webpack project.

# 📸 Screenshots

![Screenshot 2025-06-03 103240](https://github.com/user-attachments/assets/cf6e843e-e49f-4403-b912-43d6fd674922)

![Screenshot 2025-06-03 103254](https://github.com/user-attachments/assets/296af3a2-b446-472c-988d-451b51ea4ea4)

![image](https://github.com/user-attachments/assets/73d743b1-a26f-4fb5-8dc7-5d7f479fd9ac)


# 📄 License
MIT © RATTISHKUMAR 

# 🌟 Support This Project
If you found this project helpful or interesting:

***⭐ Star this repo***
***🔁 Share it with your friends***
***🧠 Fork and improve it***

# Thank you for your support! ❤️
