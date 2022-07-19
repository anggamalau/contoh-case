# contoh-case

## **Form Entry Resume**

---

**Personal Details (Single Form Entry)**

- Photo (Input File)
- Wanted Job Title (Textbox)
- First Name (Textbox)
- Last Name (Textbox)
- Email (Textbox)
- Phone (Textbox)
- Country (Textbox)
- City (Textbox)
- Address (Textbox)
- Postal Code (Textbox)
- Driving License (Textbox)
- Nationality (Textbox)
- Place Of Birth (Textbox)
- Date Of Birth (Datepicker)

**Table profile:**

- profile_code (integer, unique)
- wanted_job_title (varchar)
- first_name (varchar)
- last_name (varchar)
- email (varchar)
- phone (varchar)
- country (varchar)
- city (varchar)
- address (varchar)
- postal_code (integer)
- driving_license (varchar)
- nationality (varchar)
- place_of_birth (varchar)
- date_of_birth (date)
- photo_url (varchar)
- experienced (longtext)

**Action:**

- insert data
- update data
- read data
- upload image
- download image
- delete file

---

**Professional Summary (Single Form Entry)**

- Working Experience (Textarea/ Wysiwug)

**Table profile:**

**Action:**

- update data
- read data

---

**Employment History (Multiple Form Entry)**

- Job Title (Textbox)
- Employer (Textbox)
- Start & End Date (Datepicker)
- City (Textbox)
- Description (Textarea)

**Table profile_employment_history:**

- profile_code (integer, foreign key)
- id (integer, unique)
- job_title (varchar)
- employer (varchar)
- start_date (date)
- end_date (date)
- city (varchar)
- description (varchar)

**Action:**

- insert data
- delete data
- read data

---

**Education (Multiple Form Entry)**

- School (Textbox)
- Degree (Textbox)
- Start & End Date (Datepicker)
- City (Textbox)
- Description (Textarea)

**Table profile_education:**

- profile_code (integer, foreign key)
- id (integer, unique)
- school (varchar)
- degree (varchar)
- start_date (date)
- end_date (date)
- city (date)
- description (date)

**Action:**

- insert data
- delete data
- read data

---

**Skills (Multiple Form Entry)**

- Skill (Textbox)
- Level (Dropdown [Novice, Beginner, Skillful, Experienced, Expert])

**Table profile_skill:**

- profile_code (integer, foreign key)
- id (integer, unique)
- skill (varchar)
- level (varchar)

**Action:**

- insert data
- delete data
- read data

---
