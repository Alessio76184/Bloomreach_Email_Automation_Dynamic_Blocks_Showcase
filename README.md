# 📦 Repository: Bloomreach Email Dynamic Blocks – Showcase Only

**Description:**
This repository demonstrates a dynamic email automation system using Bloomreach, where products are automatically populated in emails based on pre-selected items or recommendation algorithms. Each block is designed to adapt dynamically to the data provided by Bloomreach's recommendation engine, enabling scalable and personalised campaigns.

Additionally, users can easily adjust the number of items displayed and the currency symbol (whether it appears before or after prices) directly in the Bloomreach block preview interface. This flexibility allows marketers to customise content presentation according to the specific needs of each campaign, market, or brand.

This repository showcases a collection of reusable, production-quality email block designs built for Bloomreach-powered campaigns. These blocks have been implemented using robust, Outlook-compatible HTML, inline CSS, and dynamic templating logic (e.g., {% %}, {{ }}), and have been successfully deployed in real-world eCommerce campaigns.

> ⚠️ **Note**: The actual HTML code has been removed from this repository to respect confidentiality agreements. The designs and logic documented here represent the structure and features of the original work but do not include proprietary client code.

---

## 📁 Folder Structure

```plaintext
assets/
├── minimal_three_col_block.png
├── three_column_discount_grid.png
├── two_column_discount_block.png
├── two_column_outlook_safe_block.png
```

---

## 🔧 Features Overview

### ✅ Common Features (All Blocks)
- Designed for use with `recommendations(params.recommendationID, params.itemsCount)`
- Display product `title`, `image`, `url`, and optionally `brand`
- Responsive and table-based for maximum email client compatibility
- Inline CSS for consistent rendering across Gmail, Outlook, Apple Mail, etc.

### ⚙️ Conditional Features (Available in Specific Blocks)
- **Auto-calculated discounts** when `discount_percentage` is not available
- **Title truncation** for long product names (to maintain layout integrity)
- **Fallback table structures** for Outlook rendering (in select blocks)
- **Price formatting** (whole number detection, strike-through original price, etc.)

---

## 🧩 Available Blocks

### 🔹 `minimal_three_col_block.html`

![Minimal Three Column Block](assets/minimal_three_col_block.png)

- 3-column layout  
- Displays **image**, **brand**, and **title**  
- No prices or discounts  
- Ideal for new arrivals or inspiration blocks

---

### 🔹 `three_column_discount_grid.html`

![Three Column Discount Grid](assets/three_column_discount_grid.png)

- 3-column layout  
- Full pricing display with **auto-calculated discounts**  
- Displays **image**, **brand**, **title**, **price**, and **discount badge**  
- Title truncates after seven words  
- Optimised for compact yet rich promo sections

---

### 🔹 `two_column_discount_block.html`

![Two Column Discount Block](assets/two_column_discount_block.png)

- 2-column layout  
- Includes **price**, **original price**, and **discount badge**  
- Minimal fallback for MS Outlook  
- Balanced design for primary product promotion

---

### 🔹 `two_column_outlook_safe_block.html`

![Two Column Outlook Safe Block](assets/two_column_outlook_safe_block.png)

- 2-column layout  
- Uses **conditional tables** for bulletproof Outlook rendering  
- Full content with fallback logic and styling  
- Most reliable across all email clients

---

## 📬 Compatibility

- ✅ Gmail, Outlook (via conditional tables), Apple Mail, Yahoo
- 📱 Mobile responsive
- 🧱 Table-based for layout stability

---

## 📝 Usage Disclaimer
These designs are provided as a **portfolio showcase only**. The code and logic behind the blocks are part of client-owned systems and are not available for distribution.

If you would like more information or custom email design work, feel free to get in touch with [GitHub profile](https://github.com/Alessio76184) or LinkedIn.

---

## 👨‍💻 Author
**Alessio Casablanca**  
Conversion Strategist & Frontend Developer

---

## 📄 License
This project is shared as a **non-distributable showcase** only. All rights to the underlying source code and logic are retained by the original client. No license applies.
