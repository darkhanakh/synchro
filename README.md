# 🎯 Synchro

**Unlocking Shared Academic Time at Nazarbayev University**

Synchro is a web-based utility designed to simplify the complex task of coordinating academic and social schedules among friends and peers at Nazarbayev University. Say goodbye to manually cross-referencing multiple PDF timetables! 📚✨

## 🤔 The Problem

Frustrated by the manual effort of cross-referencing multiple PDF timetables to find:
- A common study slot 📖
- A shared lecture 👥
- Just time to grab coffee? ☕

Synchro streamlines this process by intelligently analyzing uploaded class schedules.

## ✨ What It Does

Synchro provides a clear, aggregated view of the academic commitments of a group of students with two primary functions:

### 1. 🎓 Identify Common Lectures
Instantly highlight which specific classes are shared among uploaded schedules:
- "Calculus I (LEC)" 
- "Introduction to Programming (LAB)"

Perfect for finding study group members, collaborative project partners, or knowing who's in the same lecture hall.

### 2. 🕐 Pinpoint Overlapping Free Time
Identifies precise time slots when all (or a selected subset) of the group are simultaneously free from academic obligations. Crucial for planning:
- Meetings 🤝
- Social gatherings 🎉
- Shared study sessions 📚

## ⚙️ How It Works

### 1. 📄 PDF Schedule Upload
Users upload PDF files containing their academic timetables from the student portal or registrar.

### 2. 🧠 Intelligent PDF Parsing
Robust PDF parsing mechanism extracts structured data:
- **Text Extraction**: Reading raw text content from PDFs
- **Pattern Recognition**: Identifying course codes, names, types (Lecture, Lab, Seminar), days, and times across varying NU department layouts

### 3. 📊 Data Normalization & Representation
Raw schedule data is normalized into standardized, machine-readable format where each academic commitment becomes a distinct time interval.

### 4. 🔍 Algorithmic Analysis
- **Common Lecture Detection**: Compares course names and sections across schedules for exact matches
- **Time Interval Intersection**: Uses efficient algorithms to find genuinely shared free periods by intersecting inverse busy schedules

### 5. 🖥️ Interactive Display
Intuitive user interface presents processed information, allowing users to:
- View shared lectures
- Browse overlapping free time slots
- Filter by day or time of day

## 🛠️ Technology Stack

- **Frontend**: Next.js (React) for fast, responsive, modern UI
- **Package Manager**: pnpm for efficient dependency management  
- **Styling**: Tailwind CSS for utility-first styling
- **PDF Processing**: Robust PDF text and table extraction libraries

## 🚀 Getting Started

```bash
# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd synchro

# Install dependencies
pnpm install

# Start development server
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🎯 Target Audience

Nazarbayev University students seeking to effortlessly align their busy academic lives and make the most of their shared time with peers.

---

*Synchro aims to be the go-to tool for NU students to coordinate their schedules efficiently and never miss an opportunity to connect! 🎓*
