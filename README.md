# -c#ADO.NET-
# 🦸 Superhero Database System (Windows Forms)

## 📌 Project Overview
This project is a **C# Windows Forms application** developed to manage superhero trainee records for the One Kick Heroes Academy. The system allows assessors to store superhero details, automatically calculate ranks based on exam scores, and generate a summary report for analysis.

Superhero data is stored in a text file (`superheroes.txt`) and displayed in a **DataGridView** for easy viewing and management.

---

## 👩‍💻 My Contribution (Group Project)
My main contribution to this project was working on the **Summary Report functionality**, which includes:
- Calculating total superheroes
- Calculating average age
- Calculating average exam score
- Counting heroes per rank (S, A, B, C)
- Writing the summary results to a file called `Summary.txt`
- Displaying the summary results on the Windows Form

---

## 🛠️ Technologies Used
- C# (.NET Framework)
- Windows Forms
- Text File Handling (`StreamReader`, `StreamWriter`)
- DataGridView
- Object-Oriented Programming (OOP)
- Git & GitHub (Version Control)

---

## 🎯 Features
- Add a new superhero record
- View all superheroes in a DataGridView
- Update superhero information
- Delete superhero records
- Automatically calculate Rank and Threat Level based on exam score
- Generate a summary report and save it to `Summary.txt`

---

## 📊 Ranking System (Based on Exam Score)
- **S-Rank:** 81–100  
- **A-Rank:** 61–80  
- **B-Rank:** 41–60  
- **C-Rank:** 0–40  

Threat level is also assigned based on rank.

---

## 📂 Files Used
- `superheroes.txt` – stores all superhero records  
- `Summary.txt` – stores the generated summary report  

---

## ⚙️ How to Run the Project
1. Clone or download the repository  
2. Open the solution in **Visual Studio**  
3. Run the application  
4. The program automatically creates `superheroes.txt` if it does not exist  
5. Use the form buttons to add, update, delete, view superheroes, and generate the summary report  

---

## 📸 Screenshots
1. **Main Form**
   - Form view.png
2. **Adding a new superhero (input fields filled)**
  - Adding Superhero.png
3. **Update feature (editing hero details)**
    - Update feature.png
4. **Delete feature (hero removed from DataGridView)**
    - Delete feature.png
5. **Summary Report displayed on the form**
   - Summary Report displayed on form.png

---

## 📌 Summary Report Output
The Summary Report includes:
- Total number of superheroes  
- Average age  
- Average exam score  
- Heroes per rank (S, A, B, C)  
- Report generation date  

The report is saved in `Summary.txt`.

---

## 🧠 Concepts Demonstrated
- File handling using text files
- Data validation and error handling
-  using separate layers (Business Logic Layer and Data Layer)
- Automatic calculations based on input values
- Report generation and statistics calculation

---

