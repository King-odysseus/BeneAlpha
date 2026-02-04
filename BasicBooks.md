# **📚 Basic Accounting Books for Kenyan Businesses**

**Advisor:** Sarah Mwangi, CPA(K) – Accounting Systems Specialist

---

## **⚠️ Critical Disclaimer**

> _This guidance outlines basic accounting requirements for Kenyan businesses. Compliance requirements vary by industry and scale. Always consult with a practicing ICPAK accountant for your specific needs. I provide educational guidance, not professional accounting advice._

---

## **🎯 KRA Mandatory Accounting Records**

### **Legal Requirements (Income Tax Act, Section 55)**

```
BY LAW, EVERY BUSINESS MUST MAINTAIN:
1. Cash book/Bank statements
2. Sales/Income records
3. Purchase/Expense records
4. Assets register
5. Liabilities register
6. Stock/Inventory records (if trading)
7. PAYE records (if employees)
8. VAT records (if registered)
```

**Retention Period:** **7 YEARS** (KRA can audit back 5+ years)

---

## **📒 Core Accounting Books Required**

### **1. Cash Book (Most Critical)**

```
PURPOSE: Records ALL cash movements
FORMAT REQUIRED: Double-entry (Receipts vs Payments)
KRA REQUIREMENT: Must show daily balances

CAN BE DIGITAL? ✅ Yes (Excel/Software)
MUST BE HARD COPY? ❌ No, but recommended backup
```

### **2. Sales/Income Day Book**

```
PURPOSE: Records ALL sales/invoices issued
FORMAT: Date, Invoice No, Customer, Amount, VAT
KRA REQUIREMENT: Serialized invoice numbers

CAN BE DIGITAL? ✅ Yes (ETIMS now digital)
MUST BE HARD COPY? ❌ No, but receipts must be issued
```

### **3. Purchase/Expense Day Book**

```
PURPOSE: Records ALL purchases/expenses
FORMAT: Date, Supplier, Invoice No, Amount, VAT
KRA REQUIREMENT: Original invoices for amounts > KES 24,000

CAN BE DIGITAL? ✅ Yes (Scanned copies acceptable)
MUST BE HARD COPY? ❌ No, but keep original invoices
```

### **4. Assets Register**

```
PURPOSE: Tracks fixed assets and depreciation
FORMAT: Asset, Date, Cost, Depreciation rate, NBV
KRA REQUIREMENT: For capital allowance claims

CAN BE DIGITAL? ✅ Yes (Excel perfect)
MUST BE HARD COPY? ❌ No
```

### **5. Stock/Inventory Register (If Trading)**

```
PURPOSE: Tracks stock movements
FORMAT: Item, Opening, Purchases, Sales, Closing
KRA REQUIREMENT: For cost of goods sold calculation

CAN BE DIGITAL? ✅ Yes
MUST BE HARD COPY? ❌ No
```

### **6. Debtors Ledger**

```
PURPOSE: Who owes you money
FORMAT: Customer, Date, Amount, Payment terms
KRA REQUIREMENT: For bad debt claims

CAN BE DIGITAL? ✅ Yes
MUST BE HARD COPY? ❌ No
```

### **7. Creditors Ledger**

```
PURPOSE: Who you owe money
FORMAT: Supplier, Date, Amount, Due date
KRA REQUIREMENT: For accurate liabilities reporting

CAN BE DIGITAL? ✅ Yes
MUST BE HARD COPY? ❌ No
```

---

## **📊 Excel vs Manual vs Software: Comparison**

### **Option 1: Manual Books (Hard Copy)**

```
✅ ADVANTAGES:
• No technical skills needed
• Always accessible (no power/internet)
• Tangible for KRA inspections
• Low cost (KES 500-2,000 per book)

❌ DISADVANTAGES:
• Prone to errors
• Difficult to analyze
• Bulky storage
• No automatic calculations
• Time-consuming

RECOMMENDED FOR:
• Very small businesses (< KES 100,000/month)
• Elderly business owners
• Areas with poor electricity/internet
```

### **Option 2: Excel/Google Sheets**

```
✅ ADVANTAGES:
• Free/low cost
• Flexible customization
• Formulas reduce errors
• Easy to backup
• Can print hard copies

❌ DISADVANTAGES:
• Manual data entry
• No automatic bank feeds
• Limited reporting
• Version control issues
• Security concerns

RECOMMENDED FOR:
• Small businesses (KES 100,000-500,000/month)
• Tech-savvy owners
• Good basic Excel skills
```

### **Option 3: Accounting Software**

```
✅ ADVANTAGES:
• Automatic calculations
• Bank feeds integration
• Professional reports
• ETIMS integration
• Multi-user access
• Audit trail

❌ DISADVANTAGES:
• Monthly costs (KES 3,000-10,000)
• Learning curve
• Internet dependency
• Vendor lock-in risk

RECOMMENDED FOR:
• Growing businesses (> KES 500,000/month)
• Multiple employees
• Need for financing
• Expansion plans
```

---

## **📋 Minimum Books for Airbnb Business**

### **For Benealpha Ltd (Airbnb Startup)**

```
PRIORITY 1 (MUST HAVE):
1. CASH BOOK: All money movements
2. SALES BOOK: Airbnb income records
3. EXPENSE BOOK: All business costs
4. ASSETS REGISTER: Property, furniture, equipment
5. GUEST REGISTER: Legal requirement for hospitality

PRIORITY 2 (RECOMMENDED):
6. FIXED ASSET SCHEDULE: Depreciation calculations
7. LOAN LEDGER: Director's loan tracking
8. TAX RECONCILIATION: Airbnb withholding vs actual tax
9. BUDGET vs ACTUAL: Monthly performance tracking
```

---

## **💼 Specific Excel Templates for Airbnb**

### **Template 1: Combined Cash & Bank Book (Excel)**

| Date       | Description        | Receipt No | Cash In | Cash Out | Bank In | Bank Out | Balance |
| ---------- | ------------------ | ---------- | ------- | -------- | ------- | -------- | ------- |
| 01/03/2024 | Airbnb Payout      | INV001     |         |          | 75,000  |          | 75,000  |
| 02/03/2024 | Cleaning Service   |            |         | 2,500    |         |          | 72,500  |
| 03/03/2024 | Utility Bill       |            |         |          |         | 5,000    | 67,500  |
| 04/03/2024 | Guest Cash Payment | INV002     | 8,000   |          |         |          | 75,500  |

**Excel Formulas to Include:**

```excel
Balance Formula: =Previous Balance + Cash In + Bank In - Cash Out - Bank Out
Monthly Total: =SUM(range)
VAT Calculation: =Amount * 0.16
Depreciation: =Cost * Depreciation Rate / 12
```

### **Template 2: Airbnb Income Tracker (Excel)**

| Booking Date | Guest Name | Nights | Daily Rate | Gross Income | Airbnb Fee | Cleaning | Net Income | Payment Method | Status    |
| ------------ | ---------- | ------ | ---------- | ------------ | ---------- | -------- | ---------- | -------------- | --------- |
| 01-05/03     | John Smith | 4      | 5,000      | 20,000       | 600        | 1,500    | 17,900     | M-Pesa         | Completed |
| 10-12/03     | Jane Doe   | 2      | 7,500      | 15,000       | 450        | 1,500    | 13,050     | Bank           | Completed |
| 15-20/03     | Family     | 5      | 6,000      | 30,000       | 900        | 1,500    | 27,600     | Credit Card    | Upcoming  |

### **Template 3: Expense Categorization (Excel)**

| Date       | Category          | Supplier | Amount | VAT | Total | Payment Method | Receipt Kept? |
| ---------- | ----------------- | -------- | ------ | --- | ----- | -------------- | ------------- |
| 05/03/2024 | Utilities         | KPLC     | 3,200  | 512 | 3,712 | M-Pesa         | Yes           |
| 10/03/2024 | Cleaning Services | CleanPro | 4,000  | 640 | 4,640 | Cash           | Yes           |
| 15/03/2024 | Repairs           | Handyman | 2,500  | 0   | 2,500 | Cash           | Yes           |
| 20/03/2024 | Marketing         | Facebook | 5,000  | 800 | 5,800 | Card           | Yes           |

### **Template 4: Fixed Assets Register (Excel)**

| Asset        | Date Acquired | Cost        | Depreciation Rate | Useful Life | Monthly Depn | Accumulated | NBV         |
| ------------ | ------------- | ----------- | ----------------- | ----------- | ------------ | ----------- | ----------- |
| Sofa Set     | 01/03/2024    | 85,000      | 10%               | 10 years    | 708          | 708         | 84,292      |
| Refrigerator | 01/03/2024    | 65,000      | 12.5%             | 8 years     | 677          | 677         | 64,323      |
| TV           | 01/03/2024    | 45,000      | 25%               | 4 years     | 938          | 938         | 44,062      |
| **Total**    |               | **195,000** |                   |             | **2,323**    | **2,323**   | **192,677** |

---

## **📜 Legally Required Manual/Hard Copy Books**

### **Books That MUST Be Physical/Hard Copy:**

```
1. GUEST REGISTER (For hospitality businesses)
   • Legal requirement under Tourism Act
   • Must be available for police inspection
   • Format: Physical book at property
   • Details: Guest name, ID/passport, nationality, dates

2. MINUTE BOOK (For companies)
   • Records board meetings and resolutions
   • Required by Companies Act
   • Can be digital but physical recommended
   • Must be available for registrar inspection

3. SHARE REGISTER (For companies)
   • Records share ownership and transfers
   • Required by Companies Act
   • Can be digital but physical recommended
```

### **Special Note for Airbnb:**

```
GUEST REGISTER EXCEPTIONS:
• Digital guest registers ARE acceptable IF:
  1. Approved by county government
  2. Can be produced immediately during inspection
  3. Contains all required information
  4. Backed up regularly

RECOMMENDATION:
• Start with physical guest register
• Transition to digital once established
• Keep backup/parallel system for 3 months
```

---

## **⚖️ KRA Acceptance of Digital Records**

### **Official KRA Position (iTax Guidelines):**

```
ACCEPTABLE DIGITAL FORMATS:
✅ Excel spreadsheets (with formulas)
✅ PDF copies of invoices/receipts
✅ Scanned documents
✅ Accounting software exports
✅ Digital bank statements
✅ ETIMS electronic invoices

REQUIREMENTS FOR DIGITAL RECORDS:
1. Must be readable/searchable
2. Must have audit trail
3. Must be backed up regularly
4. Must be accessible during audit
5. Must cover 7-year period
```

### **During KRA Audit:**

```
YOU MUST PROVIDE:
1. Electronic copies of all records
2. Access to accounting software
3. Bank statements (digital or printed)
4. Supporting documents (scanned)
5. Explanation of accounting system

RECOMMENDED PRACTICE:
• Monthly: Print summary reports
• Quarterly: Archive digital records
• Annually: Print full set for backup
• Always: Have both digital and physical backup
```

---

## **💡 Hybrid System Recommendation**

### **For Benealpha Ltd (Airbnb Business):**

```
RECOMMENDED APPROACH: 70% Digital, 30% Physical

DIGITAL (Excel/Software):
1. Cash book and bank reconciliation
2. Income and expense tracking
3. Assets register and depreciation
4. Tax calculations and filings
5. Financial reports and analysis

PHYSICAL (Hard Copy):
1. Guest register (mandatory)
2. Minute book (company requirement)
3. Share register (company requirement)
4. Important contracts/agreements
5. Original permits and licenses
```

### **Monthly Process:**

```
WEEK 1 (Record Keeping):
• Update Excel cash book daily
• Scan all receipts immediately
• Update guest register (physical)
• File documents (physical)

WEEK 2 (Reconciliation):
• Reconcile bank statements
• Update expense tracker
• Calculate depreciation
• Prepare tax provisions

WEEK 3 (Reporting):
• Generate monthly reports
• Print summary for records
• Backup all digital files
• Archive previous month

WEEK 4 (Review):
• Review financial performance
• Plan for next month
• Meet with accountant
• File any tax returns
```

---

## **🚀 Step-by-Step Setup Process**

### **Week 1: Foundation Setup**

```
DAY 1-2: EXCEL TEMPLATES
• Download or create templates
• Set up formulas and formatting
• Test with sample data
• Create backup system

DAY 3-4: PHYSICAL BOOKS
• Purchase guest register book
• Purchase minute book (company)
• Purchase file folders
• Set up filing system

DAY 5-7: PROCESS SETUP
• Define daily recording process
• Train staff (if any)
• Set up digital storage
• Test full system
```

### **Week 2: Implementation**

```
DAY 1-3: DATA MIGRATION
• Record opening balances
• Input existing transactions
• Reconcile with bank
• Verify accuracy

DAY 4-5: TESTING
• Run sample reports
• Check calculations
• Test backup/restore
• Identify issues

DAY 6-7: GO LIVE
• Start daily recording
• Monitor for issues
• Make adjustments
• Document procedures
```

---

## **📊 Transition Plan: Excel → Software**

### **When to Upgrade from Excel:**

```
TRIGGERS FOR UPGRADING:
1. Monthly turnover > KES 500,000
2. More than 50 transactions/month
3. Need for ETIMS integration
4. Seeking business financing
5. Multiple properties/locations
6. Hiring employees with PAYE
```

### **Recommended Transition Path:**

```
PHASE 1: EXCEL FOUNDATION (Months 1-3)
• Learn basic accounting in Excel
• Establish good habits
• Build historical data

PHASE 2: QUICKBOOKS STARTER (Months 4-6)
• QuickBooks Simple Start
• Manual data entry
• Basic reporting

PHASE 3: FULL QUICKBOOKS (Month 7+)
• QuickBooks Online
• Bank feeds integration
• ETIMS integration
• Professional reporting
```

---

## **💰 Cost Comparison**

### **Excel System Costs:**

```
INITIAL COSTS:
• Microsoft Excel/Google Sheets: KES 0-2,400/year
• Training (basic Excel): KES 5,000-10,000
• Backup storage: KES 1,000-2,000/year
• Printing/stationery: KES 3,000-5,000/year

ONGOING COSTS:
• Time: 10-15 hours/month (owner's time)
• Accountant review: KES 5,000-10,000/month
• Total: KES 8,000-17,000/month (mostly time)
```

### **Accounting Software Costs:**

```
INITIAL COSTS:
• QuickBooks Online: KES 5,000 setup
• Training: KES 10,000-20,000
• Implementation: KES 15,000-30,000

ONGOING COSTS:
• Subscription: KES 3,500-7,000/month
• Accountant: KES 3,000-6,000/month
• Total: KES 6,500-13,000/month
```

### **Manual System Costs:**

```
INITIAL COSTS:
• Accounting books: KES 2,000-5,000
• Filing system: KES 1,000-3,000
• Training: KES 3,000-6,000

ONGOING COSTS:
• Stationery: KES 2,000-4,000/month
• Accountant: KES 8,000-15,000/month (more work)
• Total: KES 10,000-19,000/month
```

---

## **✅ Compliance Checklist**

### **KRA Minimum Requirements Met?**

- [ ] **Cash/Bank records:** Complete and up to date
- [ ] **Sales records:** All invoices documented
- [ ] **Purchase records:** All expenses with receipts
- [ ] **Assets register:** All fixed assets recorded
- [ ] **Tax calculations:** Accurate and timely
- [ ] **Backup system:** Both digital and physical
- [ ] **7-year retention:** System in place

### **Additional for Airbnb:**

- [ ] **Guest register:** Physical book maintained
- [ ] **County permits:** Displayed and valid
- [ ] **Insurance:** Current and adequate
- [ ] **Safety records:** Fire, health certificates
- [ ] **Employee records:** If applicable (PAYE, NSSF, NHIF)

---

## **🔐 Security & Backup Procedures**

### **For Excel Systems:**

```
DAILY:
• Save to cloud (Google Drive, OneDrive)
• Email copy to yourself
• External hard drive backup (weekly)

MONTHLY:
• Print summary reports
• Burn to CD/DVD (optional)
• Store offsite copy

QUARTERLY:
• Full system backup
• Test restore procedure
• Archive previous quarters
```

### **For Physical Books:**

```
SECURITY:
• Fireproof safe for important documents
• Limited access to financial records
• Serial numbering of receipts
• Regular inventory of books

BACKUP:
• Photocopy critical pages
• Digital photos of guest register
• Cloud storage of important documents
```

---

## **🎯 Final Recommendation for Benealpha**

### **Starting Point (Months 1-3):**

```
USE: EXCEL + PHYSICAL GUEST REGISTER
REASON:
• Low cost during startup phase
• Flexibility to learn and adjust
• Meets all legal requirements
• Easy transition later

TEMPLATES NEEDED:
1. Combined Cash & Bank Book
2. Airbnb Income Tracker
3. Expense Categorization Sheet
4. Fixed Assets Register
5. Tax Reconciliation Sheet
```

### **Growth Phase (Months 4-12):**

```
UPGRADE TO: QUICKBOOKS ONLINE
TRIGGERS:
• Consistent monthly revenue
• Multiple transactions
• Need for professional reporting
• ETIMS requirement activation

TRANSITION PROCESS:
• Parallel run for 1 month
• Accountant assistance
• Data migration service
• Staff training
```

### **Long-Term (Year 2+):**

```
IDEAL: FULLY INTEGRATED SYSTEM
COMPONENTS:
• QuickBooks Online (accounting)
• ETIMS integration (tax compliance)
• Property management software
• Digital guest registration
• Automated bank feeds
```

---

**🏁 Key Takeaway:** You can absolutely start with Excel—it's KRA-compliant, cost-effective, and flexible. The ONLY mandatory physical book for your Airbnb business is the **Guest Register**. Everything else can be digital from day one. Start simple, build good habits, and upgrade when the business justifies it.

**Would you like me to:**

1. **Share ready-to-use Excel templates** specifically for Airbnb accounting?
2. **Provide a sample Guest Register format** that meets Kenyan legal requirements?
3. **Create a monthly accounting checklist** with specific weekly tasks?
4. **Explain how to transition from Excel to QuickBooks** when you're ready?
