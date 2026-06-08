# 💰 Personal Expense Tracker

A complete single-page application (SPA) for tracking personal expenses with visual analytics. Built with vanilla JavaScript, Tailwind CSS, and Chart.js.

## ✨ Features

### Core Requirements
- ✅ Add new expense (Title, Amount, Category, Date, Notes)
- ✅ View all expenses sorted by date (most recent first)
- ✅ Edit existing expenses
- ✅ Delete expenses with custom confirmation modal (theme-matching)
- ✅ Total spent summary
- ✅ Category breakdown pie chart

### Bonus Features
- ✅ Filter by date range (from/to)
- ✅ Filter by category dropdown
- ✅ Input validation (no negatives, required fields, proper amount limits)
- ✅ Responsive design (table on desktop, cards on mobile)
- ✅ Smooth UI transitions & error animations
- ✅ Tailwind CSS + Chart.js integration
- ✅ Dark mode toggle with persistent preference
- ✅ LocalStorage data persistence
- ✅ Toast notifications for all actions (add, edit, delete, filter)
- ✅ Character counter for title field (0/100)
- ✅ Keyboard shortcuts (Ctrl+N for new expense, Esc to cancel edit)
- ✅ Custom modal dialog for delete confirmation (replaces browser confirm)
- ✅ Clean, professional design without category-based pastel colors

## 🎨 Color Scheme

| Role | Color | Hex |
|------|-------|-----|
| Primary | Deep Purple | #7E22CE |
| Secondary | Mint Green | #34D399 |
| Accent | Coral Orange | #F97316 |
| Background | Warm White | #FAFAF9 |
| Text | Charcoal | #292524 |

### Dark Mode Colors
- Background: Dark Gray (#111827 / #1F2937)
- Cards: Darker Gray (#1F2937 / #374151)
- Text: Light Gray (#F3F4F6)
- Consistent purple accents throughout

## 🛠️ Technologies Used

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript (ES6+)
- Chart.js 4.4.0
- Font Awesome 6.0.0
- LocalStorage API

## 📂 Project Structure
B0626---Wafa-Batool---Innovaxel---Frontend/
├── index.html # Complete application with all features
└── README.md # Documentation (this file)

## 🚀 How to Run

1. Download or clone this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. No server, build step, or installation required!
4. Data persists automatically via LocalStorage

## 🧪 How to Test

| Action | Steps |
|--------|-------|
| Add Expense | Fill form → Click "Add Expense" → Toast confirmation appears |
| Edit Expense | Click blue edit icon → Form populates → Modify → Click "Update" |
| Delete Expense | Click red trash icon → Custom modal opens → Confirm deletion |
| Filter Expenses | Select date range and/or category → List updates automatically |
| Reset Filters | Click "Reset" button → All filters cleared |
| Dark Mode | Click moon/sun toggle in header → Theme switches globally |
| Keyboard Shortcut | Press `Ctrl+N` (or `Cmd+N` on Mac) → Focus moves to title input |
| Cancel Edit | Press `Esc` while editing → Form resets |
| Mobile View | Resize browser window below 768px or use device toolbar in DevTools |

## 💾 Data Persistence

All expenses are automatically saved to your browser's `localStorage` under the key `pearlledger_expenses`. 

- Refresh the page → Data remains
- Close and reopen browser → Data remains
- Clear browser data → Data will be lost (restores to sample data)

## 📱 Responsive Design

| Breakpoint | Layout |
|------------|--------|
| Desktop (>768px) | Full table view with all columns |
| Mobile (<768px) | Card-based layout with stacked information |

Cards show: Title, Amount, Category, Date, Notes (if present), Edit/Delete buttons|

## ✅ Input Validation

| Field | Validation Rules |
|-------|------------------|
| Title | Required, max 100 characters |
| Amount | Required, positive number, min 0.01, max 999,999,999 PKR |
| Category | Selected from dropdown (default: Food) |
| Date | Required, defaults to today |
| Notes | Optional, max 200 characters |

## 📊 Sample Data

The application includes sample data on first load:

| Title | Amount | Category | Date | Notes |
|-------|--------|----------|------|-------|
| Tests | PKR 5,000 | Health | 15 Jun 2026 | Yearly |
| Monthly checkup | PKR 5,000 | Health | 12 Jun 2026 | M Imp |
| Bills | PKR 30,000 | Utilities | 10 Jun 2026 | Electricity and Gas |
| Groceries | PKR 40,000 | Food | 10 Jun 2026 | Monthly |
| New recipe | PKR 2,000 | Other | 9 Jun 2026 | Random |
| Joggers | PKR 7,000 | Shopping | 8 Jun 2026 | MUST |
| Netflix subscription | PKR 1,100 | Entertainment | 8 Jun 2026 | Monthly |
| New bag | PKR 2,500 | Shopping | 8 Jun 2026 | Emporium |
| Fuel - Petrol | PKR 3,500 | Transport | 4 Jun 2026 | Honda 125 |

## 🎯 Statistics & Analytics

- **Total Spent**: Sum of all expenses in PKR
- **Average Daily**: Average spending per day based on date range
- **Filtered Total**: Sum of currently filtered expenses
- **Top Category**: Highest spending category in filtered view
- **Pie Chart**: Visual breakdown by category (filtered view)

## 🧹 Recent Improvements

1. **Removed pastel colors** from table rows for cleaner professional look
2. **Custom delete modal** replaces browser confirm dialog (theme-aware)
3. **Toast notifications** for all user actions (success, error, info)
4. **Dark mode toggle** with localStorage persistence
5. **Character counters** for title and notes fields
6. **Improved date sorting** (most recent first always)
7. **Mobile card view** with consistent styling
8. **Backdrop blur** on modals for modern aesthetic

## 🌐 Browser Support

| Browser | Minimum Version |
|---------|-----------------|
| Chrome | 60+ |
| Firefox | 60+ |
| Safari | 12+ |
| Edge | 79+ |

## 👩‍💻 Author

**Wafa Batool**  
Frontend Intern Candidate - Innovaxel  
Assessment Submission: B0626

## 📅 Submission Date

June 2026

## 📝 License

This project is submitted as part of a frontend internship assessment for Innovaxel.

---

**Open `index.html` to start tracking your expenses!** 🎉
