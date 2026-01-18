# 🚀 PumpIQ - Petrol Pump Management System

**End Your DSR Headaches! Automated Daily Sales Reports in Minutes**

---

## 💡 The Problem We Solve

**Tired of spending 2-3 hours daily on DSR calculations?**

- ✔️ Manual tank dip volume calculations
- ✔️ Confusing meter reading math
- ✔️ Cash counting errors
- ✔️ Credit tracking mess
- ✔️ Variance calculations giving you headaches
- ✔️ Making Excel sheets from scratch daily

### ✅ PumpIQ Does It All in 5 Minutes!

**Just enter the readings → We calculate everything → Professional reports ready!**

No more calculators, no more Excel formulas, no more DSR stress!

---

## 🎯 What PumpIQ Does

### The Smart Way to Handle DSR

1. **Enter tank dip** → We calculate volume
2. **Enter pump readings** → We calculate sales
3. **Count cash** → We calculate totals
4. **Add credits** → We track everything
5. **Click Generate** → Done! ✅

**Everything is automated. Everything is accurate. Every single time.**

---

## ✨ Key Features

### 📊 Automatic Calculations (Your Brain Can Rest!)

- **Tank Dip to Volume** - No more dip charts! Enter cm, get liters instantly (20KL tanks)
- **Fuel Density Calculator** - Calculate MS/HSD density automatically
- **Pump Sales** - Opening + Closing readings = Sales (we do the math!)
- **Cash Variance** - Expected vs Actual = Surplus/Shortage (no calculator needed!)
- **Credit Tracking** - Customer credits tracked with daily totals
- **Vapor Loss Tracking** - Automatic vapor loss calculations with temperature adjustments

### 📈 Professional Reports (Impress Everyone!)

- **Text Report (.txt)** - Complete daily report for each pump
- **Petrol Daily Sales(.xlsx)** - Petrol sales with density & stock
- **Diesel Daily Sales(.xlsx)** - Diesel sales with density & stock  
- **Daily INR Sales(.xlsx)** - 24-hour sales in ₹ with charts

### 💰 Financial Management

- **Credit System** - Track all customer credits with individual customer sheets
- **Digital Payments** - UPI, Cards categorized
- **Cash Counter** - Denomination-wise (₹500 to ₹1)
- **Adjustments** - Expenses, shortages tracked
- **Bank Deposits/Withdrawals** - Track all bank transactions

### ☁️ Google Drive Backup (Optional)

- **Disabled by default** - Your choice to enable
- Auto-upload reports to Drive
- Never lose data
- Access from anywhere

### 📊 Analytics & Insights

- **Cashier Performance** - Who's accurate? Who has shortages?
- **Oil Sales Trends** - What's selling? What's not?
- **Oil Inventory Management** - Track opening stock, purchases, sales
- **Adjustments Tracker** - View all adjustments history
- **Daily/Monthly Charts** - Visual insights

---

## 💻 System Requirements

- **Windows 10 or 11** (64-bit)
- **500 MB free disk space**
- **Internet connection** (for Google Drive backup - optional)
- That's it! 

---

## 📥 Installation

1. **Download** `PumpIQ_Setup.exe`
2. **Run installer** (no admin rights needed!)
3. **Choose installation location** (default: `C:\Users\[YourName]\AppData\Local\PumpIQ`)
4. **Create desktop shortcut** (optional)
5. **Launch PumpIQ!**

### Installation Options

During installation, you can choose:
- ✅ **Desktop icon** - Quick access to PumpIQ
- ✅ **Records folder shortcut** - Direct access to all your reports

**First Launch**: 60-day free trial starts automatically (Full access, no credit card!)

---

## 🎬 Complete User Guide

---

## ⚙️ Setup

- **What to do after installation:** Go to settings and setup all things according to you RO

## 📱 Dashboard - Your Control Center

The **Dashboard** is your home screen showing all available sections.

### What You'll See:

**Navigation Cards:**
- 📝 **Basic Info** - Start here! Island, shift, dates
- 🛢️ **Tank Dip** - Morning tank measurements
- ⛽ **Pump Readings** - Fuel sales from meters
- 🛢️ **Oil Sales** - Lubricant oils (sachets, loose, servo)
- 💳 **Digital Payments** - UPI, card transactions
- 💵 **Cash Count** - Physical cash counting
- 📋 **Credits** - Customer credit tracking
- ⚖️ **Adjustments** - Expenses, shortages, extras
- 📊 **Report Preview** - See & download your report

**Analytics Section:**
- 📊 **Analytics** - Sales trends & insights
- 👤 **Cashier Performance** - Accuracy tracking
- 🛢️ **Oil Analytics** - Lubricant sales analysis
- 📦 **Oil Inventory** - Stock management
- 📈 **Adjustments Tracker** - View all adjustments

### How to Use Dashboard:

1. **Start with Basic Info** (always first!)
2. **Fill sections in any order** (but Tank Dip should be done early morning)
3. **Green checkmarks ✓** show completed sections
4. **Generate Report** when all sections done

---

## 📝 Section 1: Basic Info

**This is your starting point!** Enter basic details about your shift.

### Fields to Fill:

#### 1. **Cashier Name**
- **What to enter:** Your name or the shift operator's name
- **Example:** "Ramesh Kumar"
- **Why:** Tracks who handled this shift (important for performance analytics)

#### 2. **Select Shift**
- **Options:** 
  - **Day Shift (1)** - 6:00 AM to 6:00 PM (12 hours)
  - **Night Shift (2)** - 6:00 PM to 6:00 AM (12 hours)
- **Why:** Reports are named based on shift (AMI1 = Morning Island 1, PMI2 = Evening Island 2)

#### 3. **Island Number**
- **What to enter:** Which fuel island you're operating (1, 2, 3, etc.)
- **Example:** Island 1, Island 2
- **Why:** Multi-island pumps need separate reports for each island

#### 4. **Opening Date**
- **What to enter:** When shift STARTED
- **Example:** 20/01/2025 06:00
- **Format:** DD/MM/YYYY HH:MM
- **Default:** Automatically set based on shift time

#### 5. **Closing Date**
- **What to enter:** When shift ENDED
- **Example:** 20/01/2025 18:00
- **Format:** DD/MM/YYYY HH:MM
- **Default:** Automatically set (12 hours after opening)

### Important Notes:

⚠️ **24-Hour Operations?** If your pump runs continuously without separate shifts:
- The system will detect continuous operation automatically
- Reports will be named appropriately (e.g., PMI1.txt)
---

## 🛢️ Section 2: Tank Dip (Morning Reading)

**Take these readings EARLY MORNING before any sales!**

This section calculates fuel volume from tank dip measurements (for 20KL tanks).

### For MS (Petrol) Tank:

#### 1. **Opening Dip (cm)**
- **What to measure:** Tank dip stick reading in centimeters
- **When:** Early morning before ANY sales
- **Example:** 85 cm
- **Range:** 0-200 cm (depends on your tank)
- **Important:** MUST be done before opening for accurate calculations!

#### 2. **Volume (Liters)** - AUTO CALCULATED
- System converts dip (cm) to volume (liters) using 20KL tank chart
- **Example:** 85 cm = 8,456 liters
- Shows instantly after entering dip

#### 3. **Temperature (°C)**
- **What to measure:** Fuel temperature from thermometer
- **Example:** 28°C
- **Range:** 15-45°C typical
- **Why:** Used for density correction

#### 4. **Observed Density (kg/L)**
- **What to enter:** Density reading from hydrometer
- **Example:** 738
- **Range:** 700 - 800 for MS
- **Optional:** Can calculate this automatically (see below)

#### 5. **Corrected Density (kg/L)** - AUTO CALCULATED
- System corrects observed density based on temperature
- Uses standard formula: D15 = Dt + α(t - 15)
- **Why:** Reports need standard density at 15°C

### For HSD (Diesel) Tank:

Same fields as MS tank:
- Opening Dip (cm)
- Volume (Liters) - auto calculated
- Temperature (°C)
- Observed Density (kg/L)
- Corrected Density (kg/L) - auto calculated

**HSD Density Range:** 0.820-0.860 kg/L

### Important Notes:

⚠️ **Tank Size:** System is calibrated for **20KL (20,000 liter)** tanks only

⚠️ **Timing:** Take dip readings BEFORE any morning sales start

✅ **Vapor Loss:** System automatically calculates vapor loss based on:
- Opening stock (from dip)
- Purchases (if any added)
- Sales (from pump readings)
- Closing stock (next day's opening)

---

## ⛽ Section 3: Pump Readings

**Enter meter readings for each pump nozzle.**

This is where you record fuel sales from your dispensing pumps.

### For Each Pump (Example: Pump 1, Pump 2, etc.):

Each pump has nozzles for different fuel types (MS, HSD, etc.)

#### For Each Nozzle:

##### 1. **Opening Reading**
- **What to enter:** Meter reading at shift START
- **When:** Exactly when shift begins (6 AM / 6 PM)
- **Example:** 12,345.67
- **Format:** Decimal allowed (XX,XXX.XX)
- **Where to find:** Look at pump totalizer receipt
- **Important:** Write this down IMMEDIATELY at shift start!

##### 2. **Closing Reading**
- **What to enter:** Meter reading at shift END
- **When:** Exactly when shift ends (6 PM / 6 AM)
- **Example:** 12,789.45
- **Format:** Decimal allowed (XX,XXX.XX)
- **Important:** MUST be higher than opening reading!

##### 3. **Liters Sold** - AUTO CALCULATED
- System calculates: Closing - Opening
- **Example:** 12,789.45 - 12,345.67 = 443.78 liters
- Shows immediately after entering readings

##### 4. **Amount (₹)** - AUTO CALCULATED
- System calculates: Liters × Rate
- Rate comes from Settings
- **Example:** 443.78 L × ₹106.41/L = ₹47,228
- Updates automatically when readings change

### Smart Features:

✅ **Auto-fill Opening:** System can copy previous closing reading as today's opening (optional)

### Example Configuration:

**Island 1:**
- Nozzle 1: MS (Petrol)
  - Opening: 45,678.90
  - Closing: 46,234.56
  - Sales: 555.66 L
- Nozzle 2: HSD (Diesel)
  - Opening: 78,901.23
  - Closing: 79,456.78
  - Sales: 555.55 L

### Common Issues:

❌ **"Opening is higher than closing"**
- Check you didn't swap the numbers
- Pump meter never goes backward!

❌ **"Sales seem too high"**
- Verify you entered correct numbers
- Check decimal point position
- Compare with yesterday's sales

✅ **Continuous Operation (24-hour):**
- System handles this automatically
- Uses 24hr from settings
- No special action needed!

---

## 🛢️ Section 4: Oil Sales (Lubricants)

**Track lubricant oil sales (engine oils, gear oils, etc.)**

This section manages packaged oils, loose oil, and engine oils.

### 📦 Packaged Oils (Sachets/Bottles)

Track sales of pre-packaged oils by volume.

**Common sizes:** 20ml, 40ml, 60ml, 0.5L, 1.0L.

#### For Each Oil Product:

##### 1. **Sold**
- **What to enter:** Total quantity sold during shift
- **Example:** Sold 8 sachets
- **Units:** Number of pieces

##### 2. **Rate per Unit (₹)**
- **What to enter:** Selling price per piece
- **Example:** ₹10 per 20ml sachet
- **Set in Settings** (can be changed here)

##### 3. **Total Amount (₹)** - AUTO CALCULATED
- Formula: Sold × Rate
- **Example:** 8 sachets × ₹10 = ₹80
- Updates automatically

### 🛢️ Loose Oil (Bulk Oil Sales)

Loose oil sold by liters (not pre-packaged).

#### Fields:

##### 1. **Liters Sold**
- **What to enter:** Total loose oil sold in liters
- **Example:** 15.5 liters
- **Format:** Decimal allowed
- **How to measure:** Use measuring can/jug

##### 2. **Rate per Liter (₹)**
- **What to enter:** Manual rate OR
- **Auto-calculated:** Based on oil purchases (recommended)
- **Example:** ₹340 per liter
- **Smart pricing:** System can calculate rate from your purchase data

##### 3. **Amount (₹)** - AUTO CALCULATED
- Formula: Liters × Rate
- **Example:** 15.5 L × ₹180 = ₹2,790

### 📊 Oil Inventory Management

**Click "Oil Inventory" from Dashboard** to access advanced features:

#### Opening Stock Setup:
- Set opening stock for ALL oils at once
- One-time setup per purchase

#### Purchase Entry:
- Add oil purchases with details:
  - Date of purchase
  - Supplier name
  - Oil type & size
  - Quantity purchased
  - Rate paid

#### Stock Overview:
- See all oil stocks in one place
- Current stock levels

### Important Notes:

⚠️ **Stock Mismatch?** 
- If closing stock ≠ physical count:
- Check if all sales were recorded
- Check for breakage/damage
- Add adjustment in "Adjustments" section

✅ **New Oil Product?**
- Add in Settings → Oil Prices
- Set size, rate, opening stock
- Available immediately in all sections

⚠️ **Rate Changes?**
- Change rate in Settings
- Applies to all future sales
- Old sales keep old rates

---

## 💳 Section 5: Digital Payments

**Record all non-cash payments received during shift.**

Modern payment methods beyond physical cash.

### Payment Types:

#### 1. **UPI Payments (₹)**
- **What to enter:** Total UPI amount received
- **Includes:** 
  - Google Pay (GPay)
  - PhonePe
  - Paytm
  - BHIM
  - Any QR code payments
- **How to calculate:** Check UPI transaction history in app
- **Example:** ₹15,450

#### 2. **Card Swipe (₹)**
- **What to enter:** Total card payment amount
- **Includes:**
  - Credit cards
  - Debit cards
  - Any POS machine transactions
- **How to calculate:** Check POS machine report
- **Example:** ₹8,900
- **Tip:** Keep POS receipts for verification

### Total Digital Payments - AUTO CALCULATED
- System adds: UPI + Card Swipe
- **Example:** ₹15,450 + ₹8,900 = ₹24,350
- Shows in reports and variance calculations

### How Digital Payments Affects:

**Expected Cash = Total Sales - Digital Payments - Credits**

**Example:**
- Total Fuel Sales: ₹1,00,000
- Oil Sales: ₹10,000
- Digital Payments: ₹24,350
- Credits: ₹5,000
- **Expected Cash = ₹1,10,000 - ₹24,350 - ₹5,000 = ₹80,650**

### Common Questions:

**Q: Customer paid part cash, part UPI?**
A: Enter UPI portion here, remaining goes to cash count

**Q: Card machine failed, customer paid cash instead?**
A: Don't enter in digital payments, count as cash

**Q: Got UPI for yesterday's credit?**
A: Enter in Credits section as "credit received", not here

---

## 💵 Section 6: Cash Count

**Count physical cash in hand at shift end.**

This section is CRITICAL for variance calculation.

### Denomination Counter:

Count each denomination separately for accuracy.

#### For Each Denomination:

**Available denominations:**
- ₹500 notes
- ₹200 notes
- ₹100 notes
- ₹50 notes
- ₹20 notes/coins
- ₹10 notes/coins
- ₹5 coins
- ₹2 coins
- ₹1 coins

#### Fields:

##### 1. **Count**
- **What to enter:** Number of pieces for this denomination
- **Example:** 45 pieces of ₹500 notes
- **How:** Count physically, use counting machine if available

##### 2. **Amount (₹)** - AUTO CALCULATED
- Formula: Count × Denomination
- **Example:** 45 × ₹500 = ₹22,500
- Updates as you enter count

### Summary (Auto-calculated):

#### **Total Cash in Hand**
- Sum of all denominations
- **Example:** ₹82,450
- This is your ACTUAL cash

#### **Expected Cash**
- Calculated from: Sales - Digital Payments - Credits + Bank Adjustments
- **Example:** ₹80,650
- This is what you SHOULD have

#### **Cash Variance**
- Calculated: Actual - Expected
- **Positive (+):** Surplus (excess cash) 🎉
- **Negative (-):** Shortage (missing cash) ⚠️
- **Example:** ₹82,450 - ₹80,650 = +₹1,800 (Surplus!)

### Bank Adjustment (Optional):

#### **Bank Deposit/Withdrawal**
- **Deposit (-):** Enter negative amount when depositing to bank
  - Example: Deposited ₹50,000 → Enter -50000
- **Withdrawal (+):** Enter positive amount when withdrawing from bank
  - Example: Withdrew ₹10,000 → Enter +10000
- **Why:** Adjusts expected cash calculation
- **Example:** Deposited ₹50,000, so expected cash reduces by ₹50,000

### Variance Explained:

**Surplus (Positive Variance):**
- You have MORE cash than expected
- Possible reasons:
  - Customer overpaid and you didn't notice
  - Credit payment received and not recorded
  - Previous shortage now recovered
  - Digital payment entered but customer paid cash

**Shortage (Negative Variance):**
- You have LESS cash than expected
- Possible reasons:
  - Counting error (recount!)
  - Gave wrong change to customer
  - Money misplaced
  - Theft/dishonesty
  - Credit given but not recorded

### Best Practices:

✅ **Count Twice:** 
- First count alone
- Second count with witness
- Match both counts

✅ **Use Counting Machine:** 
- Faster and more accurate
- But still verify manually

✅ **Keep Cash Organized:**
- Separate denominations in drawer
- Easier to count and verify

✅ **Record Immediately:**
- Don't wait until end of shift
- Count and record right away

❌ **Never Adjust Manually:**
- If shortage, enter actual cash count
- Don't "fix" numbers to match expected
- Honesty is important for tracking patterns

### Common Issues:

**Q: Big shortage, what to do?**
A: 
1. Recount cash carefully
2. Check if credit was given but not recorded
3. Check if expense was not entered in Adjustments
4. Review all transactions for errors
5. If still short, record honestly and investigate

**Q: Small surplus every day?**
A: 
- Customers might be giving small tips
- Or consistent rounding in your favor
- Document pattern in notes
---

## 📋 Section 7: Credits

**Track all customer credit transactions.**

When customers take fuel/oil now and pay later.

### Credit Entry System:

#### Individual Credit Transaction:

##### 1. **Customer Name**
- **What to enter:** Customer's name or company name
- **Example:** "Ramesh Transport", "Sharma Logistics"
- **Format:** Any text (searchable)
- **Important:** Use consistent naming (same customer, same name!)

##### 2. **Fuel Type**
- **Options:** MS (Petrol), HSD (Diesel)
- **Why:** Different fuel types, different rates

##### 3. **Liters**
- **What to enter:** Quantity taken on credit
- **Example:** 500 liters
- **Format:** Decimal allowed (XX.XX)

##### 4. **Amount (₹)** - AUTO CALCULATED
- Formula: Liters × Rate
- **Example:** 500 L × ₹106.41 = ₹53,205
- Updates automatically

##### 5. **Note (Optional)**
- **What to enter:** Any additional information
- **Examples:** 
  - "Driver: Mohan"
  - "Vehicle: TN37AB1234"
  - "Monthly contract customer"
  - "Payment due 30th"

### Credit Payment (Receiving Payment):

When customer pays their credit:

##### 1. **Select Credit from List**
- Shows all unpaid credits
- Organized by customer

##### 2. **Mark as Paid**
- **Payment Date:** When payment received
- **Island Paid:** Which island received payment
- **Status:** Changes to "PAID ✓"
- **Optional:** Add payment note

### Customer Credit Sheets:

**Individual sheets per customer** (like Excel notebooks!)

**Location:** `records/credits/[Customer Name].xlsx`

**Each sheet tracks:**
- Date of credit
- Fuel type & quantity
- Amount
- Payment status
- Running balance
- Payment history

**Benefits:**
- See customer's complete credit history
- Track payment patterns
- Know total outstanding per customer
- Easy to share with customer for reconciliation

### Credit Summary (Auto-calculated):

#### **Total Credits Given (₹)**
- Sum of all credits given in this shift
- **Example:** ₹85,450

#### **Credits Paid (₹)**
- Credits received/cleared in this shift
- **Example:** ₹30,000

#### **Net Credits (₹)**
- Given - Paid
- **Example:** ₹85,450 - ₹30,000 = ₹55,450
- This amount is deducted from expected cash

### Important Notes:

⚠️ **Delete Credit?**
- Click delete icon (🗑️)
- Enter reason for deletion
- Credit marked as "DELETED ❌"
- Not removed from records (audit trail!)

✅ **Edit Credit?**
- Cannot edit after saving (prevents fraud)
- Delete and re-add if mistake
- Deletion is tracked

⚠️ **Customer Payment Modes:**
- **Cash:** Mark credit as paid, cash goes to Cash Count
- **UPI/Card:** Mark as paid, amount goes to Digital Payments
- **Partial Payment:** Create new credit for remaining amount

✅ **Monthly Settlement:**
- Generate customer credit sheet
- Share with customer
- Mark all as paid when full payment received

### Credit Analytics:

**Dashboard → Cashier Performance** shows:
- Total credits by cashier
- Payment collection rate
- Outstanding amounts
- Trend analysis

---

## ⚖️ Section 8: Adjustments

**Record any non-sales transactions affecting cash.**

Expenses, shortages, extras, or any money in/out.

### Adjustment Types:

#### 1. **Expense (Money Out -)**
Money spent from cashier during shift.

**Examples:**
- Bought cleaning supplies (₹500)
- Paid electricity bill (₹2,000)
- Employee advance (₹1,000)
- Vehicle repair (₹3,500)
- Office supplies (₹800)

**Effect:** Reduces expected cash

#### 2. **Shortage (Money Missing -)**
Cash shortage without clear reason.

**Examples:**
- Counting error discovered
- Customer change error
- Money misplaced
- Theft/dishonesty

**Effect:** Reduces expected cash (to match actual)

#### 3. **Surplus (Extra Money +)**
Extra cash found.

**Examples:**
- Previous shortage recovered
- Found loose change
- Customer overpayment

**Effect:** Increases expected cash

#### 4. **Other (Various)**
Any other adjustment.

**Examples:**
- Owner withdrew cash for personal use
- Deposited extra cash
- Transfer between islands

### Adding an Adjustment:

##### 1. **Type**
- Select: Expense / Shortage / Surplus / Other
- Changes form fields based on type

##### 2. **Description**
- **What to enter:** Clear explanation
- **Examples:**
  - "Electricity bill payment"
  - "Cash shortage - reason unknown"
  - "Found ₹100 under drawer"
  - "Owner withdrawal for home"
- **Important:** Be specific! Helps in tracking patterns

##### 3. **Amount (₹)**
- **What to enter:** Money amount
- **Format:** Positive number (₹)
- **System handles:** Plus/minus automatically based on type
- **Example:** For expense of ₹500, enter: 500

##### 4. **Category (Optional)**
- **Examples:**
  - Utilities
  - Salaries
  - Maintenance
  - Supplies
  - Transport
- **Why:** Helps in expense analysis

##### 5. **Date & Time**
- **Auto-filled:** Current time
- **Can modify:** If adjustment from earlier

##### 6. **Shift & Island**
- **Auto-filled:** Current shift and island
- **Locked:** Can't change (audit trail)

### Adjustments List:

Shows all adjustments for current shift:
- Timestamp
- Type & Description
- Amount (+ or -)
- Running total

**Total Adjustments:** Sum of all adjustments

### How Adjustments Affect Cash:

**Expected Cash Calculation:**
```
Total Sales
- Digital Payments
- Net Credits
+ Surplus Adjustments
- Expense Adjustments
- Shortage Adjustments
+ Other Adjustments
= Expected Cash
```

### Adjustments Tracker (Analytics):

**Dashboard → Adjustments Tracker** shows:
- All adjustments history
- Filter by date range
- Filter by type
- Filter by cashier
- Filter by island
- Export to Excel

**Use cases:**
- Find expense patterns
- Track shortage trends
- Audit trail
- Monthly expense reports
- Cashier accountability

### Best Practices:

✅ **Be Honest:**
- Record ALL adjustments
- Don't hide shortages
- Explain clearly

✅ **Get Approval:**
- Large expenses need owner approval
- Keep receipts/bills
- Attach photo if possible

✅ **Regular Pattern?**
- If same expense weekly/monthly
- Consider separate petty cash system
- Easier than daily adjustments

❌ **Don't Use for:**
- Normal sales (use Credits instead)
- Bank deposits (use Cash Count → Bank Adjustment)
- Fuel purchases (tracked automatically)

### Common Scenarios:

**Scenario 1: Bought cleaning supplies**
- Type: Expense
- Description: "Cleaning supplies - Lizol, Harpic"
- Amount: 450
- Category: Supplies

**Scenario 2: Customer complained, gave refund**
- Type: Expense
- Description: "Customer refund - Wrong fuel dispute"
- Amount: 500
- Category: Refunds

**Scenario 3: Found missing cash later**
- Type: Surplus
- Description: "Yesterday's shortage recovered"
- Amount: 200
- Category: Recovery

**Scenario 4: Owner took money**
- Type: Other
- Description: "Owner personal withdrawal"
- Amount: 5000
- Category: Owner Drawings

---

## 📊 Section 9: Report Preview & Generation

**Final step - Generate and manage your reports!**

### Report Generation:

#### **Click "Generate Report" Button**

System creates:
1. **Text Report (.txt)** - Complete shift report in text format
2. **MS Sales Report (.xlsx)** - Petrol sales with density
3. **HSD Sales Report (.xlsx)** - Diesel sales with density
4. **Daily INR Sales (.xlsx)** - 24-hour sales summary with charts

**File naming:**
- **12-hour shift:** `AMI1.txt` (Morning Island 1), `PMI2.txt` (Evening Island 2)
- **24-hour continuous:** `PMI1.txt`

**Saved in:** `records/reports/YYYY/MM/DD/` (organized by date)

### Report Actions:

#### 1. **📄 View Report**
- Opens in built-in viewer
- Scroll through complete report
- Check all calculations
- **Tip:** Review before printing!

#### 2. **📝 Edit in Notepad**
- Opens .txt report in Notepad
- Make manual corrections if needed
- **Warning:** Only edit if you know what you're doing!
- **Tip:** Better to regenerate than edit manually

#### 3. **🖨️ Render PDF**
- Converts .txt to professional PDF
- Includes:
  - Company watermark (from Settings)
- **Perfect for:** Printing, emailing to owner, official records

#### 4. **☁️ Upload to Google Drive**
- Uploads report to your Drive folder
- **Requires:** Google Drive setup (see below)
- **Benefits:** 
  - Cloud backup
  - Access from anywhere
  - Share with accountant
  - Never lose data

#### 5. **📂 Open Reports Folder**
- Opens Windows Explorer to reports folder
- See all your reports organized by date
- Quick access to any past report

### Report Contents:

**Text Report includes:**

**Section 1: Header**
- Company name, dealer name
- Date, shift, island
- Cashier name

**Section 2: Fuel Sales**
- Each pump's meter readings
- Liters sold per fuel type
- Rate and amount
- Total fuel sales

**Section 3: Oil Sales**
- Packaged oils by size
- Loose oil
- Servo oils
- Total oil sales

**Section 4: Total Sales**
- Fuel + Oil
- GST breakdown
- Grand total

**Section 5: Payments**
- Digital payments (UPI, Card)
- Credits given
- Credits received
- Bank deposits/withdrawals

**Section 6: Cash Count**
- Denomination breakdown
- Total cash in hand

**Section 7: Variance**
- Expected cash
- Actual cash
- Surplus/Shortage
- Variance percentage

**Section 8: Adjustments**
- All adjustments list
- Running totals

**Section 9: Summary**
- Key metrics
- Important notes
- Cashier signature line

### Important Features:

✅ **Cumulative Totals:**
- Reports track running totals across days
- Opening stock from previous closing
- Continuous tracking

⚠️ **First-Time Users (Mid-Year Start):**
If you're starting PumpIQ mid-year (not from starting of RO):

**Problem:** Cumulative totals will be WRONG because system doesn't know previous data.

**Solution: ONE-TIME Manual Adjustment Required!**

1. **For First Report Only:**
   - Generate your first report
   - Find "Cumulative Sales" section in MS/HSD Daily Sales.xlsx on DailySalesRecord folder
   - Manually update to your actual cumulative figures from physical registers

2. **How to calculate:**
   - Check your physical registers/old Excel sheets
   - Enter correct cumulative totals

3. **Example:**
   ```
   Year to date MS sales: 45,67,890 liters (from your old records)
   Today's MS sales: 2,340 liters (from PumpIQ)
   Cumulative MS sales: 45,70,230 liters (update this manually)
   ```

4. **After First Report:**
   - System will track correctly from here
   - No more manual adjustments needed!
   - All future reports will have correct cumulative totals

**Why This Is Important:**
- Authorities check cumulative totals
- Only needed once when starting PumpIQ mid-year

✅ **Automatic from Day 2:**
- All subsequent reports automatically correct
- System maintains continuity
- No manual work needed!

---

## 📊 Analytics Pages

Access from Dashboard → Analytics section

### 👤 Cashier Performance Page

**Track individual cashier accuracy and efficiency**

#### Metrics Tracked:

##### 1. **Variance Analysis**
- How often does cashier have surplus?
- How often does cashier have shortage?
- Average variance amount
- Variance as % of sales

#### Leaderboard:
- Top performing cashiers
- Based on accuracy and sales

**Use for:**
- Performance reviews
- Bonus calculations
- Training needs identification
- Fraud detection

---

### 🛢️ Oil Analytics Page

**Lubricant oil sales tracking and insights**

#### What You'll See:

##### 1. **Know the sold products**
- By quantity and value
- flexible month selection

---

### 📦 Oil Inventory Page

**Complete oil stock management system**

#### Features:

##### 1. **Current Stock Overview**
- All oils with current stock levels
- Stock value (₹)
- Reorder point alerts

##### 2. **Opening Stock Entry**
- Set opening stock for all products
- One-time entry while purchase

##### 3. **Purchase Management**
- **Add Purchase:**
  - Date, Supplier, Invoice #
  - Oil type & quantity
  - Purchase rate
  - Total amount

##### 5. **Reorder Alerts**
- Products below minimum stock
- Recommended order quantity
- Based on sales velocity

##### 7. **Stock Reconciliation**
- Physical stock vs System stock
- Variance reasons:
  - Breakage/Damage
  - Theft
  - Data entry error
  - Samples given
- Add adjustment to match

**Use for:**
- Daily stock monitoring
- Purchase planning
- Theft prevention
- Accurate accounting

---

### 📈 Adjustments Tracker Page

**Complete history of all adjustments**

#### Features:

##### 1. **Filter Options**
- **Date Range:** Today, This Week, This Month, Custom
- **Type:** Expense, Shortage, Surplus, Other
- **Cashier:** All or specific cashier
- **Island:** All or specific island
- **Category:** Filter by expense category

##### 2. **Adjustments List**
Shows all adjustments with:
- Date & Time
- Cashier name
- Type & Description
- Amount (+ or -)
- Category
- Island & Shift

##### 3. **Summary Cards**
- Total Expenses
- Total Shortages
- Total Surplus
- Net Adjustment
- Count of adjustments

##### 4. **Export Options**
- Export to Excel
- Print report
- Email summary

**Use for:**
- Expense tracking
- Budget planning
- Cashier accountability
- Audit trails
- Pattern identification
- Monthly accounting

---

## ⚙️ Settings Page

**Configure PumpIQ for your pump**

Access: Dashboard → ⚙️ Settings (or hamburger menu → Settings)

---

### 🏢 Section 1: Company Branding

**Your identity on all reports and PDFs**

#### Fields:

##### 1. **Company Name**
- **What to enter:** Your petrol pump name
- **Example:** "Sri Venkatesh Fuel Station"
- **Shows on:** All reports, PDFs, splash screen
- **Format:** Up to 100 characters

##### 2. **Dealer Name**
- **What to enter:** Operator name
- **Example:** "IndianOil Corporation Limited"
- **Shows on:** Reports, signature section

---

### ⛽ Section 2: Fuel Prices

**Set current fuel rates**

#### For Each Fuel Type:

##### MS (Petrol) Rate
- **What to enter:** Current selling price per liter
- **Example:** ₹106.41
- **Format:** Decimal (XXX.XX)
- **Updates:** Instantly affects all calculations

##### HSD (Diesel) Rate
- **What to enter:** Current selling price per liter
- **Example:** ₹94.89
- **Format:** Decimal (XXX.XX)

**Note:** Existing reports keep old rates (historical accuracy)

---

### 🏝️ Section 3: Pump Configuration

**Define your pump setup**

#### Number of Islands
- **What to enter:** How many fuel islands you have
- **Example:** 2 (for 2-island pump)
- **Range:** 1-10
- **Effect:** Creates separate reports per island

#### Nozzle per Island
For each island, configure Nozzle:

**Example Configuration:**

**Island 1:**
- Nozzle 1: MS (2 nozzles)
- Nozzle 2: HSD (2 nozzles)

**Island 2:**
- Nozzle 3: MS (4 nozzles)
- Nozzle 4: HSD (4 nozzles)

---

### 🛢️ Section 4: Oil Prices

**Configure all lubricant oils**

#### Packaged Oils:

**For each oil product:**

##### 1. **Size**
- **Options:** 20ml, 40ml, 60ml, 0.5L, 1.0L

##### 2. **Rate (₹)**
- **What to enter:** Selling price per piece
- **Example:** 1L oil = ₹340

#### Loose Oil Pricing:

**Manual Rate:**
- Set fixed rate per liter
- **Example:** ₹180 per liter

---

### 🔧 Section 5: Servo Oils

**Specialty oils configuration**

Same structure as packaged oils:
- Product name (Gear Oil 1L, Brake Fluid, etc.)
- Rate per piece
- Opening stock
- Enable/Disable

**Categories:**
- Gear Oils
- Brake Fluids
- Coolants
- Hydraulic Oils
- Greases

---

### 👥 Section 6: Labour Names

**Cashier/Staff list**

**Why needed:** 
- Dropdown list in Basic Info
- Performance tracking
- Accountability

**Add Staff:**
1. Click "Add Labour"
2. Enter name
4. Save

---

### ☁️ Section 7: Google Drive Setup

**Cloud backup configuration (Optional)**

#### Status:
- **Default:** Disabled ❌
- **To Enable:** Toggle ON ✓

#### Setup Requirements:

**You need 2 things:**

##### 1. **client_secrets.json file**
- OAuth credentials from Google Cloud Console
- Contains API keys
- Enables Drive access

##### 2. **Drive Folder ID**
- ID of folder where reports will be saved
- Looks like: `1a2b3c4d5e6f7g8h9i0j`

#### Complete Setup Guide:

**Step 1: Create Google Cloud Project** (5 minutes)

1. Go to: [console.cloud.google.com](https://console.cloud.google.com)
2. Click "Create Project"
3. Project name: "PumpIQ Backup" (or any name)
4. Click "Create"
5. Wait for project creation

**Step 2: Enable Google Drive API** (2 minutes)

1. In Google Cloud Console, go to: "APIs & Services" → "Library"
2. Search: "Google Drive API"
3. Click on "Google Drive API"
4. Click "Enable"
5. Wait for activation

**Step 3: Create OAuth Credentials** (5 minutes)

1. Go to: "APIs & Services" → "Credentials"
2. Click "Create Credentials" → "OAuth client ID"
3. **If asked to configure OAuth consent screen:**
   - Click "Configure Consent Screen"
   - User Type: **External**
   - App name: "PumpIQ"
   - User support email: your email
   - Developer contact: your email
   - Click "Save and Continue"
   - Scopes: Skip (click "Save and Continue")
   - Test users: Add your Gmail (click "Add Users")
   - Click "Save and Continue"
   - Click "Back to Dashboard"

4. **Now create OAuth client:**
   - Again: "Create Credentials" → "OAuth client ID"
   - Application type: **Desktop app**
   - Name: "PumpIQ Desktop"
   - Click "Create"

5. **Download credentials:**
   - OAuth client created popup appears
   - Click "Download JSON"
   - File downloads (name: `client_secret_XXX.json`)

**Step 4: Setup client_secrets.json** (2 minutes)

1. **Rename downloaded file to:** `client_secrets.json` (EXACTLY this name!)

2. **Place file in PumpIQ folder:**
   - **If installed:** `C:\Users\[YourName]\AppData\Local\PumpIQ\client_secrets.json`
   - **If portable:** `E:\PumpIQ\client_secrets.json` (same folder as PumpIQ.exe)

3. **Verify file exists:**
   ```
   Right-click PumpIQ.exe → "Open file location"
   Check if client_secrets.json is there
   ```

**Step 5: Create Drive Folder** (2 minutes)

1. Open Google Drive: [drive.google.com](https://drive.google.com)
2. Click "New" → "Folder"
3. Name: "PumpIQ Reports" (or any name you want)
4. **Get Folder ID:**
   - Open the folder (double-click)
   - Look at URL in browser:
   ```
   https://drive.google.com/drive/folders/1a2b3c4d5e6f7g8h9i0j
                                            ^^^^^^^^^^^^^^^^^^^^
                                            This is your Folder ID
   ```
   - Copy the Folder ID (the long alphanumeric string)

**Step 6: Configure PumpIQ** (2 minutes)

1. Open PumpIQ → Settings → Google Drive
2. **Enable Google Drive:** Toggle ON ✓
3. **Paste Folder ID:** In "Drive Folder ID" field
4. Click "Save Settings"

**Step 7: First Upload (Authorization)** (2 minutes)

1. Generate any report
2. Click "Upload to Drive"
3. **Browser opens automatically** (if doesn't open, copy URL from app)
4. **Login to Google account** (must be same account as Drive folder)
5. **Warning appears:** "Google hasn't verified this app"
   - Click "Advanced"
   - Click "Go to PumpIQ (unsafe)"
   - This is normal for private apps!
6. **Grant permissions:**
   - Check: "See and download all your Google Drive files"
   - Click "Continue"
7. **Success!** Browser shows "Authentication successful"
8. Close browser
9. Return to PumpIQ
10. Upload completes automatically!

**Step 8: Verify Upload** (1 minute)

1. Open Google Drive
2. Go to "PumpIQ Reports" folder
3. Check if report file is there
4. Success! ✓

#### After First Setup:

**All future uploads are automatic!**
- No more login needed
- Just click "Upload to Drive"
- Files go directly to your folder
- Organized by date

#### Troubleshooting:

**Error: "client_secrets.json not found"**
- Check file name (must be exactly: `client_secrets.json`)
- Check file location (same folder as PumpIQ.exe)
- Check file is not empty (should be ~1KB)

**Error: "Invalid folder ID"**
- Copy folder ID again from Drive URL
- Make sure no spaces before/after
- Must be from same Google account

**Error: "Authentication failed"**
- Delete `token.json` file if exists
- Try authorization again
- Make sure using correct Google account
- Check internet connection

**Error: "Quota exceeded"**
- You hit Google API limits (rare)
- Wait 24 hours
- Or create new Google Cloud project

**Upload hangs/freezes:**
- Check internet connection
- Check file size (very large files take time)
- Check Drive storage not full

#### Security & Privacy:

✅ **Your data stays private:**
- Only YOU can access your Drive folder
- PumpIQ doesn't store your data
- All uploads are direct to YOUR Drive

✅ **Credentials are secure:**
- `client_secrets.json` never leaves your computer
- Token stored locally
- No third-party access

#### Benefits of Drive Backup:

✅ **Never lose data** - Even if computer crashes
✅ **Access anywhere** - Phone, tablet, another PC
✅ **Share with accountant** - Give folder access
✅ **Version history** - Google keeps old versions
✅ **Automatic** - Set and forget!

#### Optional Features:

**Auto-upload on generation:**
- Settings → Enable "Auto-upload reports"
- Every report automatically uploads
- No need to click "Upload" button

**Folder structure:**
- Settings → Enable "Date-based folders"
- Creates: `2025/January/20/AMI1.txt`
- Better organization

---

### 📜 Section 8: License Management

**Activate and manage your PumpIQ license**

#### License Status:

Shows current license state:

**Trial Mode:**
- ✅ Active trial (X days remaining)
- ⏰ Expiring soon (< 3 days)
- ❌ Trial expired

**Licensed Mode:**
- ✅ Active license (valid until DD/MM/YYYY)
- ⏰ Expiring soon (< 30 days)
- ❌ License expired

#### Trial License:

**What you get:**
- **15 days** free trial
- **Full access** to all features
- **No limitations**

**Starts when:** First time you launch PumpIQ

**Trial ending?**
- Warning appears 3 days before expiry
- System reminds daily
- After expiry: Read-only mode (can view old reports, can't create new)

#### Purchasing License:

**Contact us:**
- 📱 WhatsApp: **+91 8110003741** (9 AM - 9 PM IST)
- 📧 Email: **mamallan@protonmail.com**
- 💬 Response time: Within 24 hours

**What we'll ask:**
1. Your company name
2. Number of installations needed (1 computer = 1 license)
3. Hardware ID (shown in Settings)

**License Pricing:**
- **1 Year License:** Contact for pricing
- **Bulk discounts:** 5+ licenses get discount
- **Annual renewal:** At discounted rate

**Payment methods:**
- UPI (GPay, PhonePe, Paytm)
- Bank transfer (NEFT/IMPS/RTGS)
- Cash (if local)

**What you'll receive:**
1. **License Key** (format: XXXX-XXXX-XXXX-XXXX-XXXX-XXXX-XXXX)
2. **Expiry Date** (valid for 1 year from purchase)
3. **Email confirmation** with activation instructions

#### License Activation:

**Enter License Key**

1. Copy license key from email
2. Open PumpIQ → Settings → License
3. Paste in "License Key" field
4. Click "Activate"
5. Success message appears!
6. License status updates to "Active"

#### Hardware ID:

**What is it?**
- Unique identifier for YOUR computer
- Unchangeable (mostly)

**Where to find:**
- Settings → License → Hardware ID
- Copy button to copy to clipboard

**Why needed?**
- Prevents license sharing/piracy
- 1 license = 1 computer only
- We generate license key using your Hardware ID

**Hardware change?**
- Motherboard replacement → Hardware ID changes
- Need new license key
- Contact us - we'll help!
- Old license transferred to new hardware ID

#### Multiple Installations:

**Q: I have 2 computers, need PumpIQ on both?**
A: Buy 2 licenses (1 per computer)

**Q: Discounts for multiple licenses?**
A: Yes! 
- 2-4 licenses: 10% off
- 5-9 licenses: 20% off
- 10+ licenses: 30% off

**Q: Can I transfer license to another computer?**
A: Yes, one-time transfer allowed
- Uninstall from old computer
- Install on new computer
- Contact us with new Hardware ID
- We'll issue updated license key

#### License Renewal:

**When to renew:**
- System warns 30 days before expiry
- Renew anytime within last 30 days
- Early renewal extends from expiry date (no time lost!)

**Renewal pricing:**
- Usually discounted vs new license
- Contact us 1 month before expiry

**Renewal process:**
1. Contact us
2. Make payment
3. We send new license key
4. Activate like normal

#### Troubleshooting:

**Error: "Invalid license key"**
- Check you copied entire key
- Check for extra spaces
- Key is case-sensitive
- Must match your Hardware ID

**Error: "License expired"**
- Check system date/time is correct
- Wrong date causes false expiry
- Renew license if actually expired

**Error: "Hardware ID mismatch"**
- License is for different computer
- Contact us for help
- Don't try to use someone else's key!

**Trial not starting:**
- Check system date is correct
- May have run trial before
- Contact us for help

#### License Terms:

✅ **What's included:**
- 1 year usage
- All features unlocked
- Free updates during license period
- Email support
- WhatsApp support

❌ **What's NOT included:**
- Google Cloud setup (We'll help you if tutorial not enough for you)
- On-line training (available separately)
- Multiple computer installation

**Fair Use Policy:**
- License is for YOUR business use
- Don't share with competitors
- Don't pirate/crack
- Support indie developers! 💪

---

### 💾 Section 9: Data & Backup

**Manage your data and backups**

#### Records Location:

**Shows:** Where all your data is stored

**Development mode:**
```
E:\Scripts\PumpIQ\records\
```

**Structure:**
```
records/
├── reports/           (All DSR reports)
│   ├── 2025/
│   │   ├── January/
│   │   │   ├── 20/
│   │   │   │   ├── AMI1.txt
│   │   │   │   ├── PMI2.txt
│   │   │   │   └── ...
├── Daily Sales record/ (Daily Excel reports)
│   ├── MS_Sales.xlsx
│   ├── HSD_Sales.xlsx
│   └── Daily_INR_Sales.xlsx
│   └── credit ledger.xlsx
```

#### Quick Actions:

##### 1. **Open Records Folder**
- Button opens Windows Explorer
- Go directly to all your data
- Copy files to USB drive
- Email reports

##### 2. **Create Desktop Shortcut**
- Adds "PumpIQ Records" shortcut on desktop
- Quick access without opening app
- One-click to reports folder

##### 3. **Backup Data**
- **Manual backup:**
  - Click "Backup Now"
  - Choose USB drive location
  - Copies entire records folder
  - Compressed ZIP file created
- **Auto backup:**
  - Enable "Daily auto-backup"
  - Backs up to Google Drive (if enabled)
  - Or to specified folder daily

##### 4. **Restore Data**
- Select backup ZIP file
- Click "Restore"
- Extracts to records folder
- **Warning:** Overwrites current data!

#### Data Management:

**Storage used:**
- Shows total size of records folder
- Warns if getting too large (>1GB)

**Cleanup options:**
- Always have physical copy
- Delete old reports (> 1 year)
- Archive to external drive
- Keep last 6 months only

**Export all data:**
- Create complete backup
- All reports + credits + settings
- One ZIP file
- Easy to transfer to new computer

---

### 🔔 Section 10: Notifications & Preferences

**Customize PumpIQ behavior**

#### Notification Settings:

##### 1. **Trial Expiry Warnings**
- When to warn: 7 days, 3 days, 1 day before expiry
- Show popup daily: Yes/No

##### 2. **License Expiry Warnings**
- When to warn: 30 days, 15 days, 7 days before expiry

##### 3. **Cash Variance Alerts**
- Alert if shortage > ₹X
- Alert if surplus > ₹X
- Email/SMS owner (if configured)

##### 4. **Low Stock Alerts**
- Alert when oil stock below minimum
- Daily stock report email

#### Preferences:

##### 1. **Default Shift**
- Auto-select Day/Night based on time
- Or always ask

##### 2. **Auto-save**
- Save sections automatically
- Or require manual save

##### 3. **Decimal Places**
- Money: 0 or 2 decimals
- Liters: 2 or 3 decimals

##### 4. **Date Format**
- DD/MM/YYYY (default)
- MM/DD/YYYY
- YYYY-MM-DD

##### 5. **Language** (Coming soon!)
- English (current)
- Hindi
- Tamil
- Telugu
- More languages planned

---

## 🎯 Best Practices & Pro Tips

### Daily Routine:

**Morning (Shift Start):**
1. ✅ Take tank dip FIRST (before any sales)
2. ✅ Note meter readings at shift start time
3. ✅ Count opening cash (document it!)
4. ✅ Check oil stock levels
5. ✅ Open PumpIQ and fill Basic Info

**During Shift:**
6. ✅ Record credits immediately when given
7. ✅ Note any expenses as they happen
8. ✅ Keep physical cash organized
9. ✅ Track digital payments

**Shift End:**
10. ✅ Note closing meter readings at end time
11. ✅ Count cash carefully (twice!)
12. ✅ Physical oil stock count
13. ✅ Complete all sections in PumpIQ
14. ✅ Generate report
15. ✅ Review report for errors
16. ✅ Upload to Drive (if enabled)
17. ✅ Print PDF for physical records

### Accuracy Tips:

✅ **Double-check meter readings**
- Opening and closing must be logical
- Compare with yesterday
- Huge difference? Recheck!

✅ **Count cash twice**
- First count alone
- Second count with witness
- Match both counts

✅ **Physical stock matches system?**
- If not, add adjustment
- Find reason for difference
- Document it

✅ **Review before generating**
- Click through all sections
- Green checkmarks on all?
- Any warnings?
- Fix before generating report

### Security Tips:

🔒 **Protect your data:**

1. **Passwords:**
   - Lock Windows when away
   - Don't share admin password

2. **Backups:**
   - Enable Google Drive backup
   - Weekly USB backup
   - Keep 2 copies (local + cloud)

3. **Access Control:**
   - Only authorized staff use PumpIQ
   - Monitor who generates reports
   - Audit trail tracks everything

4. **Data Privacy:**
   - Customer data is sensitive
   - Don't share credit sheets
   - GDPR compliant (if applicable)

### Performance Optimization:

⚡ **Keep PumpIQ fast:**

1. **Cleanup old data:**
   - Archive reports > 6 months
   - Keep only recent credits
   - Compress old files

2. **Close other apps:**
   - More RAM = faster
   - Don't run heavy apps alongside

3. **SSD recommended:**
   - Faster than HDD
   - Quicker report generation

4. **Regular updates:**
   - Check for PumpIQ updates
   - New features + bug fixes
   - Automatic update check (if enabled)

---

## 🆘 Troubleshooting

### Common Issues & Solutions:

#### Issue 1: "Data not saving"

**Possible causes:**
- Disk full
- No write permissions
- Antivirus blocking

**Solutions:**
1. Check free disk space (needs 500MB+)
2. Run PumpIQ as Administrator (right-click → Run as admin)
3. Add PumpIQ folder to antivirus exclusions
4. Check if `records` folder exists

---

#### Issue 2: "Report not generating"

**Possible causes:**
- Incomplete data
- File open in another program

**Solutions:**
1. Complete all sections (check green checkmarks)
2. Install Microsoft Excel or LibreOffice
3. Close any open reports
4. Check `records/reports` folder permissions

---

#### Issue 3: "Google Drive upload failing"

**Possible causes:**
- No internet
- Invalid credentials
- Quota exceeded

**Solutions:**
1. Check internet connection
2. Re-authorize Drive access (delete `token.json`, try again)
3. Check Google Drive storage not full
4. Verify `client_secrets.json` exists and valid

---

#### Issue 4: "Cash variance always wrong"

**Possible causes:**
- Digital payments not recorded
- Bank deposit not entered
- Expenses missed
- Credit not recorded

**Solutions:**
1. Double-check digital payments section
2. Add bank deposit with negative (-) amount
3. Add all expenses in Adjustments
4. Verify all credits recorded
5. Recount cash physically

---

#### Issue 5: "Pump readings showing negative"

**Possible causes:**
- Swapped opening/closing
- Meter reset to zero
- Data entry error

**Solutions:**
1. Verify which reading is opening, which is closing
2. If meter reset, note previous closing as backup
3. Re-enter readings carefully
4. Check decimal point position

---

#### Issue 6: "Oil stock not matching"

**Possible causes:**
- Breakage not recorded
- Free samples given
- Theft
- Data entry error

**Solutions:**
1. Physical count vs system count
2. Add adjustment for difference
3. Note reason (breakage/theft/etc)
4. Investigate pattern if recurring

---

#### Issue 7: "License activation failing"

**Possible causes:**
- Invalid key
- Wrong hardware ID
- System date wrong
- Already activated on another PC

**Solutions:**
1. Copy license key exactly (no spaces)
2. Verify Hardware ID matches what we sent
3. Check system date/time is correct
4. Contact us - we'll help!

---

#### Issue 8: "App won't start"

**Possible causes:**
- Corrupted installation
- Missing dependencies
- Antivirus blocking

**Solutions:**
1. Restart computer
2. Reinstall PumpIQ
3. Add to antivirus exclusions:
   - `C:\Users\[You]\AppData\Local\PumpIQ`
4. Install .NET Framework (if missing)

---

#### Issue 9: "Slow performance"

**Possible causes:**
- Too many old reports
- Low disk space
- Background apps
- Low RAM

**Solutions:**
1. Archive old reports (>6 months)
2. Free up disk space (needs 1GB+)
3. Close unnecessary apps
4. Upgrade RAM if < 4GB

---

#### Issue 10: "Reports showing wrong data"

**Possible causes:**
- Used wrong shift's closing data
- Previous report error propagated
- Data entry mistake

**Solutions:**
1. Check Basic Info section (correct shift/island?)
2. Verify previous report closing = today's opening
3. Edit report if minor error
4. Regenerate if major error
5. Fix source data and regenerate
6. Check system Date & Time settings

---

### Getting Help:

**Before contacting support:**

✅ Check this README first
✅ Try suggested solutions above
✅ Note exact error message
✅ Note what you were doing when error occurred
✅ Check if reproducible

**When contacting support:**

📧 **Email:** mamallan@protonmail.com
📱 **WhatsApp:** +91 8110003741

**Include in your message:**
1. Your company name
2. License key (if licensed)
3. Exact error message
4. Steps to reproduce
5. Screenshots (if possible)

**Response time:**
- Critical issues: Within 1 hours
- Other issues: Within 3 hours
- Feature requests: Within 24 hours

**Support hours:**
- Monday-Saturday: 9 AM - 9 PM IST
- Sunday: Emergency only
- 24/7 email (slower response)

---

## 🚀 Advanced Features

### Coming in Version 2.0:

**AI-Powered Features:**

🤖 **Sales Prediction**
- Predict tomorrow's sales based on history
- Seasonal patterns
- Weather-based adjustments
- Plan inventory better

🤖 **Fraud Detection**
- AI alerts for unusual patterns
- Abnormal shortages
- Suspicious credit patterns
- Time-series anomaly detection

🤖 **Smart Pricing**
- Dynamic oil pricing
- Margin optimization

**Mobile App:**

📱 **PumpIQ Mobile** (Android & iOS)
- View reports on phone
- Get alerts
- Approve large expenses
- Monitor remotely
---

## 📞 Support & Contact

### Need Help?

**📱 WhatsApp Support:**
- Number: **+91 8110003741**
- Hours: 9 AM - 9 PM IST (Mon-Sat)
- Response: Usually within 1 hour
- Best for: Quick questions, urgent issues

**📧 Email Support:**
- Email: **mamallan@protonmail.com**
- Response: Within 24 hours
- Best for: Detailed queries, feature requests, bug reports

**💬 What we help with:**
- Installation issues
- License activation
- Feature explanations
- Bug reports
- Feature requests
- Google Drive setup
- Custom requirements

**📖 Self-Help Resources:**
- This README (comprehensive guide)
- In-app help tooltips (hover over ? icons)
- YouTube tutorials (coming soon)
- PDF manual (downloadable from website)

### Business Inquiries:

**🏢 Bulk Licensing:**
- 5+ pumps get discount
- Custom payment terms
- Training included
- Priority support

**🤝 Partnerships:**
- Oil companies
- Accounting firms
- POS vendors
- Interested? Contact us!

**💼 Custom Development:**
- Need features specific to your pump?
- Integrations with your systems?
- White-label version?
- Let's discuss!

---

## 📜 Legal & Licensing

### Software License:

**© 2025 PumpIQ. All rights reserved.**

**License Type:** Proprietary Commercial Software

**Terms:**
- 1 license = 1 computer installation
- Non-transferable (except one-time)
- No source code access
- No reverse engineering
- No redistribution
- No resale

**Permitted:**
- Install on your computer
- Create backups
- Use for your business
- Generate unlimited reports

**Not Permitted:**
- Share with competitors
- Crack/bypass license
- Modify executable
- Decompile/reverse engineer
- Resell/redistribute

### Data Privacy:

**Your data stays YOUR data:**
- We don't collect your business data
- Reports stored locally only
- Google Drive: YOUR account, YOUR control
- No analytics/tracking (except license validation)

**What we collect:**
- License activation: Hardware ID, activation date
- Support: Issues you report
- Updates: Anonymous version check

**GDPR Compliant:**
- If applicable to your region
- Right to data deletion
- Right to data export
- No third-party sharing

### Warranty & Liability:

**Warranty:**
- Software provided "AS IS"
- We fix bugs promptly
- Free updates during license period
- But no guarantee of 100% bug-free

**Liability:**
- Use at your own risk
- We're not liable for:
  - Data loss (make backups!)
  - Calculation errors (verify critical data!)
  - Business losses
  - Tax issues
- Maximum liability: License fee paid

**Your Responsibilities:**
- Keep backups
- Verify critical calculations
- Use licensed software only
- Keep license safe

### Third-Party Components:

PumpIQ uses:
- Python (PSF License)
- Flet (Apache 2.0)
- OpenPyXL (MIT)
- Pandas (BSD)
- Google Drive API (Google ToS)

All licenses available on request.

---

<h2>Screenshots</h2>

<p align="center">
  <img src="screenshots/Screenshot 2025-10-20 213558.png" width="300">
  <img src="screenshots/Screenshot 2025-10-20 213611.png" width="300">
  <img src="screenshots/Screenshot 2025-10-20 213624.png" width="300">
</p>

<p align="center">
  <img src="screenshots/Screenshot 2025-10-20 213709.png" width="300">
  <img src="screenshots/Screenshot 2025-10-21 091252.png" width="300">
  <img src="screenshots/Screenshot 2025-10-21 091321.png" width="300">
</p>

<p align="center">
  <img src="screenshots/Screenshot 2025-10-21 091339.png" width="300">
  <img src="screenshots/Screenshot 2025-10-21 091447.png" width="300">
  <img src="screenshots/Screenshot 2025-10-20 172348.png" width="300">
</p>

<p align="center">
  <img src="screenshots/Screenshot 2025-10-21 092053.png" width="300">
</p>

## 🎉 Thank You!

Thank you for choosing **PumpIQ**!

I am a one man team dedicated to making petrol pump management easier.

Your feedback helps me improve. If you have suggestions, issues, or just want to say hi, reach out!

**Made with ❤️ for Pump Owners who Value Their Time**

Stop spending hours on DSR. Start focusing on growing your business.

---

**🌟 Happy Pumping! 🌟**

---

**Version:** 1.0.0  
**Last Updated:** January 2025  
**Next Update:** Version 2.0 (AI features!)

---

© 2025 PumpIQ. All rights reserved.
