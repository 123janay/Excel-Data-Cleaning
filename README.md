Excel Data Cleaning:-

I worked on a raw data that had multiple structural and formatting issues. Below is a breakdown of the data cleaning techniques I applied using Excel.

1️⃣ Autofit Rows & Columns
Adjusted uneven rows and columns using Autofit Rows and Columns to ensure proper visibility.
 This made the data clean, readable.

2️⃣ Find & Replace
Company names were too long and inconsistent, so I used Find & Replace to remove unwanted text.
 This standardized the client names and improved overall data clarity.

3️⃣ LOWER() Formula 
Some names were written in all capital letters, affecting readability.
 I used the LOWER() function to convert them into lowercase for a cleaner look.

4️⃣ TRIM() + PROPER() (On Client Names )
Client names had extra spaces and mixed letter cases.
 Using TRIM() removed unnecessary spaces, while PROPER() fixed the Capital letters.

5️⃣ Text to Columns (Department & Region Separation)
Department and region were combined in one column using a hyphen (-).
 I used Text to Columns with hyphen as a delimiter to split them accurately.

6️⃣ Go To Special → Replace Blanks with “NA”
Some columns contained blank cells that could affect analysis.
 I used Go To Special → Blanks and replaced them with NA for consistency.

If you want a practice, I will provide the source file.
