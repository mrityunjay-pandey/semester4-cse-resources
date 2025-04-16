# Semester 4 CSE Resources Website

A simple and modern website to organize and share Semester 4 CSE study materials including syllabus, notes, assignments, and solutions.

## Features

- Clean and modern design
- Responsive layout that works on all devices
- Easy navigation between subjects
- Organized resource structure
- Smooth animations and transitions

## Directory Structure

```
├── index.html          # Main website page
├── styles.css          # Website styling
├── script.js           # Website interactivity
└── subjects/           # Subject-specific resources
    ├── ds/            # Data Structures
    ├── dbms/          # Database Management
    ├── cn/            # Computer Networks
    ├── os/            # Operating Systems
    └── dm/            # Discrete Mathematics
```

## How to Use

1. Clone or download this repository
2. Open `index.html` in your web browser
3. To add new resources:
   - Create appropriate directories under the `subjects` folder
   - Add your files (PDFs, PPTs, etc.) to the respective subject folders
   - Update the links in `index.html` if needed

## Adding New Resources

1. For each subject, create the following structure:
   ```
   subjects/[subject-code]/
   ├── syllabus.pdf
   ├── notes/
   │   ├── unit1.pdf
   │   ├── unit2.pdf
   │   └── ...
   ├── assignments/
   │   ├── assignment1.pdf
   │   ├── assignment1-solution.pdf
   │   └── ...
   └── ppts/
       ├── unit1.pptx
       ├── unit2.pptx
       └── ...
   ```

2. Make sure to name your files consistently and descriptively

## Customization

- To change colors: Edit the color values in `styles.css`
- To add new subjects: Copy and modify a subject card in `index.html`
- To modify animations: Edit the JavaScript code in `script.js`

## Browser Support

The website is compatible with all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available for personal and educational use. 