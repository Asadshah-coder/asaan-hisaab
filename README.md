# Asaan Hisaab — Free Online Calculators & Tools for Pakistan

10 free, mobile-friendly calculator tools built as single self-contained HTML files
(no build step, no dependencies). Each tool works in two ways:

- **`tools/*.html`** — standalone page, open directly in any browser.
- **`tools/*-elementor.txt`** — same code formatted for pasting into an
  Elementor **HTML widget** (or a WordPress Gutenberg **Custom HTML** block).

Live site: https://gold-sparrow-236252.hostingersite.com/

## Tools

| # | Tool | File |
|---|------|------|
| 1 | Zakat Calculator | `zakat-calculator` |
| 2 | Salary Tax Calculator (Pakistan, FY 2026-27 slabs) | `salary-tax-calculator` |
| 3 | Age Calculator | `age-calculator` |
| 4 | BMI Calculator | `bmi-calculator` |
| 5 | Percentage Calculator | `percentage-calculator` |
| 6 | EMI Calculator (Pakistan) | `emi-calculator` |
| 7 | GPA / CGPA Calculator (Pakistan) | `gpa-calculator` |
| 8 | Unit Converter (length, weight, temperature) | `unit-converter` |
| 9 | Currency Converter (USD / PKR / AED / SAR, editable rates) | `currency-converter` |
| 10 | Freelancer Tax Calculator (0.25% PSEB, Section 154A) | `freelancer-tax-calculator` |

## Usage

**Standalone:** open any `tools/*.html` file in a browser — everything
(CSS + JS) is inline, no server needed.

**WordPress + Elementor:**
1. Edit the tool page → add an **HTML** widget.
2. Copy the matching `tools/<name>-elementor.txt` and paste it in.
3. Publish.

**WordPress + Gutenberg:** add a **Custom HTML** block and paste the same file.

## Notes

- Tax slabs, currency rates and gold/silver prices are Pakistan-specific and
  change over time — verify against official sources (FBR / Finance Act) and
  update the defaults before treating any figure as authoritative.
- Currency default at time of writing: 1 USD = PKR 277.40 (27 Sep 2026).
  The converter's rates are editable on the page itself.
- All calculations run locally in the visitor's browser; no data leaves the page.

## License

Free to use and modify.

Portfolio: https://asadbukhari.site
