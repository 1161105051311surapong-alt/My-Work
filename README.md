# My-Work
# QA Portfolio - Surapong

## 👨‍💻 About Me
Software Quality Assurance with 3 years of professional experience in Manual Testing. I specialize in designing comprehensive Test Scenarios, ensuring system reliability through Regression Testing, and providing detailed Bug Reports. I have a strong background in creating Technical Documentation and User Manuals for executive review.

## 🧪 Skills
- **Testing:** Manual Testing, Exploratory Testing, Regression Testing, UAT Support
- **Documentation:** Test Case Design, Bug Reporting, System Manuals (Google Docs/Markdown)
- **Technical:** SQL (Basic), Basic Automation (Robot Framework, Playwright)

## 📂 Manual Testing Projects

### 👥 People Counting System (Visitor Analytics)
*ระบบวิเคราะห์และสรุปยอดผู้เข้าใช้บริการแบบ Real-time พร้อมกราฟเปรียบเทียบ*

**Key Contributions:**
- **Analytical Testing:** ทดสอบความถูกต้องของรายงานเชิงวิเคราะห์ เช่น Visitor Summary และ Heat Map
- **UI/UX Verification:** ตรวจสอบการแสดงผลกราฟ (Comparison Chart) ให้สอดคล้องกับฟิลเตอร์ที่เลือก (Branch, Area, Gate)
- **Data Integrity:** ตรวจสอบการดึงข้อมูลจากฐานข้อมูลให้ตรงกับตัวเลขที่แสดงบนหน้า Dashboard

**Sample Test Scenarios:**
| Test Case ID | Test Scenario | Expected Result | Priority |
|:--- |:--- |:--- |:---:|
| **Analysis** | Filter data by "Whole Year" and "Monthly" | Graph must display 12 data points correctly | High |
| **Comparison** | Compare "Current Period" vs "Previous Period" | Data lines must show clearly with distinct colors | High |
| **Heat Map** | View "Traffic Density" by Hour | Color intensity must reflect the actual visitor volume | Medium |

> [!IMPORTANT]
> **[👉 View Full Test Cases (Google Sheets)](https://docs.google.com/spreadsheets/d/19PnDrhMjITO8yMNb4Y3bl-yCyW_ofouHqyaetL64U5g/edit?gid=1368308075#gid=1368308075)**


### 📺 Smart Signage Management System

**Key Contributions:**
- **System Integration Testing:** ทดสอบการส่งข้อมูลระหว่าง CMS และตัวเครื่อง Player (Box/Screen)
- **Edge Case Testing:** ออกแบบเคสทดสอบสำหรับสถานการณ์ไม่ปกติ เช่น เน็ตหลุดระหว่างอัปโหลด หรือการอัปเดตเฟิร์มแวร์ล้มเหลว
- **UI/UX Testing:** ตรวจสอบความถูกต้องของการจัดวางเนื้อหา (Layout) บนความละเอียดหน้าจอที่แตกต่างกัน

**Sample Test Scenarios (Selected from Full Doc):**
| Test Case ID | Test Scenario | Expected Result | Priority |
|:--- |:--- |:--- |:---:|
| **CMS - Command** | ส่งคำสั่ง "Restart" จากระบบหลังบ้านไปยังจอ | จอปลายทางต้องเริ่มการทำงานใหม่ทันที | Critical |
| **Connectivity** | ทดสอบการทำงานในขณะที่ Wi-Fi หลุด | จอต้องแสดงเนื้อหาเดิมที่ Offline Cache ไว้ได้ | High |
| **Media Quality** | อัปโหลดวิดีโอที่มีความละเอียดสูงเกินสเปคจอ | ระบบต้องมีการแจ้งเตือนหรือคัดกรองไฟล์ที่เล่นไม่ได้ | Medium |

> [!IMPORTANT]
> **[👉 View Full Signage Test Cases (Google Sheets)](https://docs.google.com/spreadsheets/d/1RkQkpERGHm8tKr3OYxBQx9EOpLsEwfu3S3N3GxW9sQA/edit?gid=1760342799#gid=1760342799)**


#### 🐛 Bug Reporting & Tracking (Highlights)
ตัวอย่างการพบปัญหาและติดตามการแก้ไขจากโปรเจกต์ Signage:

| Issue Description | Category | Severity | Status |
|:--- |:--- |:---:|:---:|
| ระบบไม่แสดงสถานะ Online/Offline ของหน้าจอแบบ Real-time | Connectivity | High | **Fixed** |
| หน้าจอไม่เล่นไฟล์วิดีโอแบบวนลูป (Looping) เมื่อถึงเวลาที่กำหนด | Playback | High | **Fixed** |
| ปุ่มกดแก้ไขข้อมูลผู้ใช้ (Edit) ในหน้า CMS ไม่ตอบสนอง | UI/UX | Medium | **Fixed** |

> [!IMPORTANT]
> **[👉 ดูรายการ Bugs และการติดตามผลทั้งหมด (Google Sheets)](https://docs.google.com/spreadsheets/d/1RkQkpERGHm8tKr3OYxBQx9EOpLsEwfu3S3N3GxW9sQA/edit?gid=1670982995#gid=1670982995)**

## 📫 Contact
- **Email:** 1161105051311.surapong@gmail.com
- 
