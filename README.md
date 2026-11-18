# EXL / Lincoln Financial — Multi-Team BPO Payroll Portal

An executive-grade, fully interactive web application designed for BPO team leaders and managers to calculate complex call centre payroll (pro-rata base salaries, night shift differentials, overtime, tiered QA/CSAT incentives, WFH stipends, and statutory tax deductions) and instantly export formatted `.xlsx` spreadsheets.

---

## Features

* **Multi-Team & Process Workspaces:** Create, rename, delete, and switch between multiple call centre teams or processes (e.g., *Lincoln Annuities*, *Claims Support*, *Night Queue*), with all data persisting securely via browser `localStorage`.
* **Complete BPO Calculation Engine:** Automatically computes hourly rates from scheduled monthly days/hours, pro-rata base pay for new joiners or leavers, night shift differentials, overtime multipliers, tiered QA performance bonuses ($\ge 95\%$ = 12%, $88\text{--}94\%$ = 6%), and statutory deductions (PAYE + UIF/Social Security).
* **Direct Table Editing:** Edit any employee's name, ID, role, status, base salary, days worked, night hours, overtime hours, QA score, manual bonus, WFH stipend, or tax percentage directly in the grid, with all totals recalculating instantly.
* **Next Payroll Run Rollover:** Easily carry over team members, base salaries, tax rates, and stipends into the next month while resetting monthly variable hours with a single click.
* **Professional Excel Exports (`.xlsx`):** Powered by SheetJS, export single-team registers or a consolidated multi-team workbook complete with detailed policy audit logs.
* **Lincoln Financial Corporate Styling:** Built with a polished executive aesthetic featuring deep burgundy crimson (`#862633`), rich navy blue (`#002D62`), and warm gold (`#C59B27`) accents.

---

## Running the Application

### Option A: Local Run (Zero Setup)
1. Save the code as **`index.html`**.
2. Double-click **`index.html`** to open it in any modern browser (Google Chrome, Microsoft Edge, or Safari).

### Option B: Hosting on GitHub Pages (Access Anywhere / iPhone 16)
1. Create a public repository on GitHub (e.g., `bpo-payroll-portal`).
2. Upload **`index.html`** to the root directory of your repository.
3. Go to your repository **Settings** > **Pages**.
4. Under **Build and deployment**, set the source branch to `main` (or `master`) and `/ (root)`, then click **Save**.
5. Open your live GitHub Pages URL in Safari on your iPhone, tap **Share**, and select **"Add to Home Screen"** to use it like a native app.

---

## Data Backup & Portability
* **Auto-Save:** All rosters and payroll edits automatically save to your browser's local storage.
* **JSON Backup / Restore:** Click **Backup JSON** in the top header anytime to download a backup file of all your teams and records, and use **Restore JSON** to load them onto another computer or device.
