# AU CGPA Calculator

A modern, feature-rich CGPA (Cumulative Grade Point Average) calculator for **Annamalai University** students. Calculate semester GPA, cumulative CGPA, plan your target grades, and even scan grade cards with OCR.

# LIVE APP LINK
https://jagadeeswari99.github.io/CGPA_Calculator/

## Features

📊 **Semester GPA Calculator** - Compute your semester GPA by entering subject names, credits, and grades

🎓 **CGPA Tracker** - Track GPAs across multiple semesters and calculate cumulative CGPA

🎯 **What-If Planner** - Find out what GPA you need in upcoming semesters to hit your target CGPA

📸 **Grade Card Scanner** - Upload screenshots of your AU grade cards and OCR automatically extracts grades and calculates GPA

📋 **Grade Guide** - View the Annamalai University grading scale and classification system

## Grading Scale

| Grade | Point | Percentage |
|-------|-------|-----------|
| S     | 10    | 90-100%   |
| A     | 9     | 80-89%    |
| B     | 8     | 70-79%    |
| C     | 7     | 60-69%    |
| D     | 6     | 50-59%    |
| E     | 5     | 40-49%    |
| RA    | 0     | <40%      |

## Classifications

| CGPA Range    | Classification                |
|---------------|-------------------------------|
| 8.25 – 10.0   | 🏆 First Class with Distinction |
| 6.5 – 8.24    | 🎖 First Class                |
| 5.5 – 6.49    | 👍 Second Class               |
| Below 5.5     | ⚠ Pass Class / Needs Improvement |

## How to Use

### Locally

1. **Python**:
   ```bash
   cd CGPA_Calculator
   python3 -m http.server 8000
   ```
   Open `http://localhost:8000` in your browser.

2. **Node.js**:
   ```bash
   npx http-server -p 8000
   ```

3. **Live Server (VS Code)**:
   - Install Live Server extension
   - Right-click on `index.html` → Open with Live Server

### On GitHub Pages

1. Go to your repository **Settings** → **Pages**
2. Select **Deploy from a branch** → **main**
3. Your site will be live at: `https://YOUR-USERNAME.github.io/CGPA_Calculator`

## GPA Formula

```
GPA = Σ(Credit × Grade Point) / Σ(Credits)

CGPA = Σ(Sem Credits × Sem GPA) / Σ(All Credits)
```

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Modern dark theme with gradients and animations
- **JavaScript** - All calculations and interactions
- **Tesseract.js** - OCR for grade card scanning
- **Google Fonts** - Typography

## Features in Detail

### 📊 Semester GPA
1. Set the number of subjects and default credits
2. Enter subject names, credits, and grades
3. Click "Calculate Semester GPA" to see results
4. View subject breakdown and copy results to clipboard

### 🎓 CGPA
1. Add completed semesters with their GPA and total credits
2. Calculate cumulative CGPA across all semesters
3. View semester-wise breakdown with visual progress bars

### 🎯 What-If Planner
1. Enter your current CGPA and credits completed
2. Set credits remaining and target CGPA
3. Get the required GPA for upcoming semesters
4. See if your goal is achievable

### 📸 Grade Card Scanner
1. Click to upload or drag-drop a grade card image
2. OCR automatically extracts grades from the image
3. View detected grades and calculated GPA
4. Note: Credits are estimated—verify manually for accuracy

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (responsive design)

## Notes

- All calculations are done **client-side** — no data is stored or sent to servers
- The OCR feature works best with clear, high-contrast images
- Credits detected by OCR should be manually verified for accuracy

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.