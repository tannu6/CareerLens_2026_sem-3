# 🎯 CareerLens

**CareerLens** is an intelligent career assessment and skill‑development web application designed to empower students in discovering and improving their strengths across multiple career fields.
Built with **Flask, HTML, CSS, JavaScript, and Bootstrap**, CareerLens provides personalized assessments, progress tracking, and curated learning resources.

---

# 🚀 Features

## 🧭 Multi‑Field Career Assessment

* Users can select **up to 5 career fields** out of **27 available fields**.
* Each selected field contains **20 assessment questions**.
* Questions evaluate core skill dimensions:

  * Analytical
  * Technical
  * Communication
  * Leadership

📊 A total of **80 questions per field** are stored in the system for varied assessments.

---

## 📈 Skill Analysis & Progress Tracking

* Individual **field‑wise skill scores** calculated from assessment responses.
* Overall skill score derived from all attempted fields.
* Visual progress tracking with:

  * Field‑specific skill graph
  * Overall skill growth graph
* Users can monitor **daily skill improvement trends**.

---

## 📧 Automated Result Email

* After completing an assessment:

  * Detailed result report generated
  * Skill scores summarized
  * Sent directly to user email

---

## 📚 Learning Resource Recommendations

* CareerLens suggests curated **free learning resources** based on skill gaps.
* Users can:

  * View resources per field
  * Enroll directly via provided links

---

# 🏗️ System Workflow

1. User registers/logs in
2. Selects up to 5 career fields
3. Completes 20‑question assessment per field
4. System evaluates skill categories
5. Results displayed with graphs
6. Report emailed to user
7. Progress tracked daily
8. Learning resources recommended

---

# 🧠 Career Fields Coverage

CareerLens includes **27 career domains**, such as:

* Software Development
* Data Science
* Cybersecurity
* Design
* Management
* Communication & Media
* and more...

---

# 🛠️ Tech Stack

**Frontend**

* HTML5
* CSS3
* JavaScript
* Bootstrap

**Backend**

* Python Flask

**Database**

* MySQL (or compatible relational database)

**Other Integrations**

* Email SMTP service (result delivery)
* Chart/Graph library for visualization

---

# 📊 Skill Evaluation Logic

Each answer contributes to one or more skill categories:

| Skill Area    | Description                  |
| ------------- | ---------------------------- |
| Analytical    | Problem solving & reasoning  |
| Technical     | Domain & practical knowledge |
| Communication | Expression & clarity         |
| Leadership    | Decision & initiative        |

Scores are normalized per field and aggregated for overall skill index.
# ▶️ Running the Project

## 1️⃣ Clone Repository

```
git clone https://github.com/yourusername/careerlens.git
cd careerlens
```

## 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

## 3️⃣ Setup Database

* Import provided SQL file
* Configure DB credentials in `app.py`

## 4️⃣ Run Server

```
python app.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

# 🎯 Purpose of CareerLens

CareerLens aims to:

* Help students identify strengths & weaknesses
* Provide structured career direction
* Enable data‑driven skill growth
* Bridge gap between skills and career paths

---

# 👩‍💻 Author

**Tannu Sharma**
Computer Science Student
CareerLens Project Developer

---

# 📜 License

This project is for educational and research purposes.

---

⭐ *CareerLens — Analyze Skills. Discover Paths. Grow Daily.*
