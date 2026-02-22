# DADS5001 Mini Project — LinkedIn Job Postings (2023–2024)

## Project Topic
การวิเคราะห์แนวโน้มตลาดงานบน LinkedIn (ปี 2023–2024): รูปแบบงาน Remote, ระดับเงินเดือนมาตรฐาน (Normalized Salary) และทักษะที่เป็นที่ต้องการ  

## Research Questions (Story)
**5.1 ภาพรวม**
- ช่วงปี 2023–2024 จำนวนประกาศงานบน LinkedIn เปลี่ยนไปอย่างไร (เพิ่ม/ลด) และมีช่วงพีค/ดรอปเดือนไหน

**5.2 งาน Remote**
- สัดส่วนงานที่อนุญาต Remote ในปี 2023–2024 เป็นเท่าไร และแนวโน้มเพิ่มขึ้นหรือลดลงเมื่อเวลาผ่านไป
- งาน Remote มักกระจุกอยู่ในกลุ่มใดมากที่สุด (ประเภทงาน / ระดับประสบการณ์ / อุตสาหกรรม) และกลุ่มใด “Remote น้อยที่สุด”

**5.3 เงินเดือน (Normalized Salary)**
- ภาพรวมการกระจายของเงินเดือนเป็นอย่างไร
- เมื่อเทียบงาน Remote vs ไม่ Remote เงินเดือนต่างกันหรือไม่

**5.4 Skills ที่ตลาดต้องการ**
- Top Skills ที่พบในประกาศงานมากที่สุดคืออะไร และต่างกันไหมระหว่าง Remote vs ไม่ Remote
- Skills ใดสัมพันธ์กับ “เงินเดือนสูง” อย่างชัดเจน
- Skills กลุ่มไหนที่ “พาเงินเดือนขึ้น” มากที่สุดในงาน Remote

**5.5 แบ่ง สายงาน/อุตสาหกรรม**
- เมื่อเทียบเรื่อง Remote, เงินเดือน, Skills สามอย่างนี้ “ไปด้วยกันแบบไหน” (เช่น อุตสาหกรรม A remote เยอะ แต่เงินเดือนไม่สูง vs อุตสาหกรรม B remote ไม่เยอะ แต่เงินเดือนสูง)

**5.6 ความสนใจของตลาด**
- งานแบบไหนคนสนใจ/สมัครเยอะ (views / applies) และเกี่ยวข้องกับ Remote/เงินเดือน/Skills หรือไม่

---

## Dataset Source
- Kaggle: LinkedIn Job Postings (2023–2024)  
  https://www.kaggle.com/datasets/arshkon/linkedin-job-postings

## How to Run
1) Open the notebook in Colab (link will be added after notebook upload).
2) Upload `kaggle.json` (Kaggle API token) when prompted.
3) Click **Runtime > Run all**.

> Note: `postings.csv` is large and is not stored in this GitHub repository.  
> The notebook downloads it directly from Kaggle.

## Repository Structure
- `dataset/` : supporting CSV tables (companies/jobs/mappings)
- `notebooks/` : Colab notebook (`.ipynb`) will be stored here
