# UP Robotics × Omnify AI — Full Enrollment System

> Fully functional AI-powered enrollment with real UP Robotics data

## 🚀 How to Use

Open `index.html` in any browser. Three main sections:

### 1. Enroll Tab — Complete Registration Flow

**Step 1: Create Child Profile**
- Enter child's name, age (3-14), grade (1-9)
- Select interests from 12 categories (Robotics, Coding, Python, Minecraft, LEGO, etc.)

**Step 2: AI Recommendations**
- AI scores all 46+ programs based on grade match + interest alignment
- Shows match percentage for each program
- Filter by All / Camps / Programs
- Click "Enroll" to add to cart

**Step 3: Add Sibling**
- Add second child with their own profile
- **AI detects if both siblings can join the SAME camp** (grade overlap check)
- Shows camps where both children are eligible together
- "Enroll Both" button adds both kids to same camp with 10% discount

**Step 4: Checkout**
- Review all enrollments with full schedule details
- Automatic sibling discount (10%) when multiple children enrolled
- Secure checkout with confirmation

### 2. Calendar Tab — Full Schedule View

- Interactive monthly calendar showing all programs
- Color-coded by type: Camps (gold), Programs (purple), Parties (coral)
- Click any day to see which programs run that date
- Full program list below calendar with all details
- Navigate between months

### 3. Admin Tab — Add & Manage Programs

**Add New Program/Camp/Party:**
- Name, type (Summer Camp / Program / Party)
- Price, duration, start/end dates
- Days of week, time slots
- Available spots, emoji icon
- Select applicable grade levels
- Add custom tags

**Manage Programs:**
- View all programs in list
- Delete programs
- New programs immediately appear in AI recommendations and calendar

## 📊 Real Data Included

**38 Summer Camps** — $475 to $695
- Robot Explorers (multiple themes & dates)
- Competitive Robotics Bootcamp
- Python Coding
- Tech Pioneers: Intro to Robotics
- Minecraft Coding
- Tech Pioneers: Obstacles and Crazy Creations
- 3D Printing Camp

**7 After-School Programs** — $175 to $275 (4 weeks)
- Advanced Robotics, 3D Printing, Marine Robotics
- Intro to Robotics, LEGO Robotics
- Robot Explorers, Python Coding with AI

**1 Birthday Party** — $450
- Robot Builders Birthday Bash

## 🧠 AI Engine

The recommendation algorithm scores each service:
- **Grade match**: 40 points (child's grade must be in program's grade list)
- **Interest alignment**: 35 points (program tags match child's selected interests)
- **Availability bonus**: 5 points (more spots = higher score)
- **Price sensitivity**: 5 points (lower price = higher score)
- Results sorted by score, shown with match percentage

## 👫 Sibling Same-Camp Logic

When two children are added:
1. System finds all camps where BOTH children's grades are eligible
2. Displays these camps with combined pricing (10% discount)
3. "Enroll Both" button adds both children to the same camp
4. Cart shows sibling discount automatically

## 📅 Calendar System

- All programs plotted on calendar by date range
- Programs appear on every day between start and end dates
- Click any day to see detailed program list for that date
- Admin-added programs appear immediately

---

*Built for Omnify Design Assessment — May 2026*
*Data from uproboticstech.getomnify.com*
