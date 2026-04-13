# CWA to GPA Converter

A comprehensive web-based tool for converting Cumulative Weighted Average (CWA) scores to GPA and calculating semester/cumulative GPA.

## Features

✨ **Three Calculation Modes:**
- **Single Conversion**: Quickly convert any CWA score to GPA with letter grade
- **Semester Calculator**: Calculate GPA for a single semester with multiple courses
- **CGPA Calculator**: Track GPA across multiple semesters and calculate cumulative GPA

🎯 **Flexible Grading Scales:**
- 0-100 point scale (most common)
- 0-10 point scale
- 0-5 point scale

📊 **Smart Features:**
- Credit-weighted GPA calculation
- Dynamic grading conversion tables
- Real-time calculation updates
- Add/remove courses and semesters on the fly
- Beautiful, responsive user interface

## Conversion Scale (0-100)

| CWA Range | GPA  | Grade |
|-----------|------|-------|
| 90-100    | 4.0  | A+    |
| 85-89.99  | 3.9  | A     |
| 80-84.99  | 3.7  | A-    |
| 77-79.99  | 3.3  | B+    |
| 73-76.99  | 3.0  | B     |
| 70-72.99  | 2.7  | B-    |
| 67-69.99  | 2.3  | C+    |
| 63-66.99  | 2.0  | C     |
| 60-62.99  | 1.7  | C-    |
| 50-59.99  | 1.0  | D     |
| 0-49.99   | 0.0  | F     |

## How to Use

### Single Conversion
1. Select your grading scale (0-100, 0-10, or 0-5)
2. Enter your CWA score
3. View the converted GPA, letter grade, and conversion scale

### Semester Calculator
1. Select your grading scale
2. Add courses with:
   - Course name
   - CWA score
   - Credit hours
3. View semester GPA, total credits, and average CWA
4. Add/remove courses as needed

### CGPA Calculator
1. Select your grading scale
2. Click "+ Add Semester" to create semesters
3. For each semester, add courses with:
   - Course name
   - CWA score
   - Credit hours
4. View cumulative GPA across all semesters

## Installation

No installation required! Simply open `index.html` in any modern web browser:
- Double-click the file, or
- Right-click > Open with > Your favorite browser

## Technical Details

- **Pure HTML/CSS/JavaScript** - No external dependencies
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Fast & Reliable** - All calculations happen locally in your browser
- **No Data Storage** - Your data is never sent to any server

## GPA Calculation Formula

**Semester GPA** = Sum(GPA × Credits) / Total Credits

**Cumulative GPA (CGPA)** = Sum of all (GPA × Credits) / Sum of all Credits

## Browser Support

Works in all modern browsers:
- Chrome/Edge (65+)
- Firefox (60+)
- Safari (11+)

## Tips

💡 **Tip 1**: You can add multiple courses to see how different grades affect your overall GPA

💡 **Tip 2**: Adjust credit hours based on your institution's rules

💡 **Tip 3**: Use the CGPA calculator to track your academic progress across semesters

💡 **Tip 4**: Switch between grading scales to see conversions on different systems

## Customization

You can modify the conversion scales by editing the `scales` object in the JavaScript section. Each scale contains:
- `min`: Minimum score in the range
- `max`: Maximum score in the range
- `gpa`: Corresponding GPA value (typically 0-4.0)
- `grade`: Letter grade

## License

Free to use and modify for personal or educational purposes.

---

**Questions or Issues?** 
Make sure to verify your institution's specific GPA calculation method, as different schools may use slightly different conversion scales.
