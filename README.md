# Hi there, I'm Simranjot! 👋 🚀

I am a highly driven **Full-Stack Developer** and final-year Computer Science & Engineering undergraduate. I specialize in building decoupled web microservices, designing high-throughput relational databases, and implementing scalable backend application logic using Python and JavaScript frameworks.

- 🎓 **Education:** B.Tech in Computer Science & Engineering @ Lyallpur Khalsa College Technical Campus 2023-2027
- ⚡ **Core Focus:** Backend Engineering, Decoupled Architectures, Asynchronous Web Protocols, and API Performance Optimization
- 💼 **Looking for:** Graduate Software Engineering roles, Full-Stack Developer positions, or Technical Internships

---

## 🛠️ Technical Stack & Domain Expertise

<table>
  <tr>
    <td align="center" width="25%"><strong>Backend Core</strong></td>
    <td align="center" width="25%"><strong>Frontend Web</strong></td>
    <td align="center" width="25%"><strong>Databases & Storage</strong></td>
    <td align="center" width="25%"><strong>DevOps & Tools</strong></td>
  </tr>
  <tr>
    <td valign="top">
      • Python / Django / Flask<br>
      • FastAPI / RESTful APIs<br>
      • WebSockets (Async)<br>
      • OOP / System Debugging
    </td>
    <td valign="top">
      • JavaScript (ES6+)<br>
      • HTML5 / CSS3<br>
      • Bootstrap Framework<br>
      • Responsive UI Design
    </td>
    <td valign="top">
      • PostgreSQL<br>
      • MySQL<br>
      • RDBMS Architecture<br>
      • ACID Transactions
    </td>
    <td valign="top">
      • Git / GitHub Workflows<br>
      • Docker Containerization<br>
      • Postman API Testing<br>
      • Linux Environments
    </td>
  </tr>
</table>

---

## 🚀 Highlighted Engineering Projects

### 🛍️ FUZEE – AI-Powered Apparel E-Commerce Platform
A production-ready, full-stack apparel e-commerce system built with clear boundary limits between systemic components.

Use code with caution.
Frontend Layer (JS, HTML5, CSS3, Bootstrap)
│
▼
Decoupled API Routing (RESTful)
│
▼
Backend Logic Core (Django / Flask)
│
┌───────────┴───────────┐
▼                       ▼
Database Layer (PostgreSQL)   ML Recommendation Engine

#### Key Engineering Features:
* **Decoupled State Management:** Built isolated modules managing state mutations independently across user authentication flows, active transactional shopping carts, and dynamic inventory ledgers.
* **Database Performance Tuning:** Configured a scalable relational database schema in PostgreSQL utilizing explicit foreign key constraints, targeted search indexing, and performance-tuned transactional executions to eliminate race conditions.
* **Low-Latency Communication:** Engineered asynchronous REST API execution contexts within the framework layers to sustain responsive JSON body deliveries and safe thread handling under concurrent query stresses.

#### 🗄️ Database Schema & Relational Model (FUZEE)
┌───────────────┐          ┌───────────────┐          ┌───────────────┐
│   User Profile │1        │     Order     │1        │   Order_Item  │
├───────────────┤          ├───────────────┤          ├───────────────┤
│ id (PK)       ├─────────►│ id (PK)       ├─────────►│ id (PK)       │
│ email         │          │ user_id (FK)  │          │ order_id (FK) │
│ password_hash │          │ total_price   │          │ product_id(FK)│
└───────────────┘          └───────────────┘          │ quantity      │
└───────────────┘
▲
┌───────────────┐                                             │1
│    Product    │1────────────────────────────────────────────┘
├───────────────┤
│ id (PK)       │
│ title, price  │
│ stock_count   │
└───────────────┘

#### ⚙️ Setting Up FUZEE Locally
```bash
# Clone the repository
git clone https://github.com
cd fuzee-ecommerce

# Initialize the python environment wrapper
python -m venv venv
.\venv\Scripts\activate

# Install the application packages
pip install -r requirements.txt

# Execute migrations and run server
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

---

### 🤝 SEWA-360 – Intelligent Community Resource-Sharing Ecosystem
A centralized resource-matching community utility application optimized to balance localized supply streams with critical civic demands.

Client-Side UI ──> [ FastAPI Router ] ──> [ Location Preprocessing ]
│
▼
Relational Storage Matrix <──────────────── PostgreSQL Ledger

#### Key Engineering Features:
* **High-Performance Asynchronous Routing:** Leveraged FastAPI's concurrent execution matrix to handle heavy transactional payloads and maintain non-blocking client-server I/O cycles.
* **Complex Multi-Tier Relational Integrity:** Engineered a PostgreSQL schema featuring nested relational logic to support structural database dependencies and track real-time resource allocation states seamlessly.
* **Geospatial & Proximity Processing:** Implemented robust vector-based location preprocessing algorithms to sort, categorize, and rank emergency dispatch tasks based on dynamic proximity and optimal routing metrics.

#### 🗄️ Database Schema & Relational Model (SEWA-360)
┌───────────────┐          ┌───────────────┐          ┌───────────────┐
│   User_Node   │1        │ Request_Ticket│1        │  Match_Ledger │
├───────────────┤          ├───────────────┤          ├───────────────┤
│ id (PK)       ├─────────►│ id (PK)       ├─────────►│ id (PK)       │
│ full_name     │          │ user_id (FK)  │          │ ticket_id (FK)│
│ contact_info  │          │ resource_type │          │ supply_id (FK)│
└───────────────┘          └───────────────┘          │ routing_metric│
└───────────────┘
▲
┌───────────────┐                                             │1
│  Supply_Node  │1────────────────────────────────────────────┘
├───────────────┤
│ id (PK)       │
│ capacity      │
│ gps_coords    │
└───────────────┘

#### ⚙️ Setting Up SEWA-360 Locally
```bash
# Clone the repository
git clone https://github.com
cd sewa-360

# Setup system environment
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt

# Run the asynchronous server
uvicorn main:app --reload
```

---

## 📈 Certifications & Training
- **Full Stack Web Development with AI** – 8-Week Professional Certification, *Internshala Trainings*
- **AI/ML Engineering Training** – Hands-on Enterprise Sprints, *Sensation Software and Solution, Mohali*
- **Elements of AI** – Core Systems Architecture & Theory, *University of Helsinki*
- **Cloud Computing Architecture Certification** – Enterprise Infrastructure & Virtualization Frameworks

---

## 🤝 Connect with Me
- **LinkedIn:** [://linkedin.com](https://://linkedin.com)
- **GitHub:** [://github.com](https://://github.com)
- **Email:** simranjotdevops11@gmail.com
