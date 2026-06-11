# Lipinski-s-rule-of-five
bash
git clone https://github.com/magury13851386/Lipinski-s-rule-of-five.git
cd Lipinski-s-rule-of-five
یک فایل جدید به نام README.md بسازید
با هر ویرایشگر متنی (Notepad، VS Code، ...) فایلی با این نام در پوشه پروژه ایجاد کنید.

محتوای README را در آن کپی کنید (متن زیر را داخل فایل بچسبانید).

فایل را ذخیره کنید.

تغییرات را به گیت‌هاب بفرستید:

bash
git add README.md
git commit -m "Add README file"
git push
متن README.md که می‌توانید کپی کنید (نسخه سفارشی‌شده برای پروژه خودتان)
markdown
# Lipinski's Rule of Five - Data Analysis

This project applies **Lipinski's Rule of Five** to a dataset of chemical compounds to evaluate drug-likeness. The dataset contains 500 synthetic compounds with four key properties: molecular weight (MW), LogP, hydrogen bond acceptors (HBA), and hydrogen bond donors (HBD).

## Objective
- Generate a dataset with realistic distributions of these four properties.
- Determine how many compounds violate the Rule of Five.
- Visualize the distribution of violations and compare pass/fail groups.

## Requirements
Install the required Python libraries:

```bash
pip install -r requirements.txt
How to Run
Clone this repository.

Make sure you have Jupyter Notebook or VS Code with Python extension.

Open Lipinski_rule_of_five.ipynb.

Run all cells sequentially.

Key Results
Pass rate: 17.8% (89 out of 500 compounds) passed all criteria.

Average values for pass vs. fail:

Property	Pass (mean)	Fail (mean)
MW	363.4	533.9
LogP	2.15	3.29
HBA	4.78	7.62
HBD	2.23	3.90
Limitations
The dataset is artificially generated (random uniform distributions) for educational purposes. For real-world applications, consider using actual chemical databases like ChEMBL or ZINC, and compute features with RDKit.

Future Improvements
Replace synthetic data with real SMILES strings.

Add RDKit for precise physicochemical calculations.

Build a predictive model for drug-likeness.

License
MIT

text

> **نکته:** می‌توانید هر قسمتی از این متن را مطابق پروژه خود تغییر دهید. مثلاً اگر از دیتاست واقعی استفاده کردید، قسمت «Limitations» را حذف یا اصلاح کنید.

---

## چگونه تصویر (مثلاً نمودار) به README اضافه کنیم؟

1. در مخزن خود، یک پوشه به نام `images` بسازید (از دکمه «Add file» -> «Create new file» و نام `images/.gitkeep` بنویسید تا پوشه خالی بماند یا بعداً تصاویر را آپلود کنید).
2. تصاویر خود را (مثلاً اسکرین‌شات از نمودارهای نوت‌بوک) داخل پوشه `images` آپلود کنید (با دکمه «Upload files»).
3. در فایل README.md، جایی که می‌خواهید تصویر نشان داده شود، بنویسید:
   ```markdown
   ![نمودار توزیع وزن مولکولی](images/mw_distribution.png)
