# Pilates HODU Instructor Education Portal

![Pilates HODU](https://img.shields.io/badge/Pilates-HODU-navy?style=for-the-badge)
![Instructor Portal](https://img.shields.io/badge/Instructor-Portal-gold?style=for-the-badge)
![Medical Pilates](https://img.shields.io/badge/Medical-Pilates™-green?style=for-the-badge)

## 🎯 Project Overview

**Pilates HODU Instructor Education Portal** is a comprehensive educational resource system for Pilates HODU instructors and staff. It provides guides for enhanced program operations along with AI-based educational materials as part of the website renewal.

## 🌟 Key Features

### 📚 Program Guides
- **7 Customized Care Programs** detailed guides
- Operating protocols and lesson plans for each program
- Step-by-step execution checklists
- Professional blog-style detailed content delivery

### 🤖 AI-Based Educational Guides
- **NotebookLM** interactive learning
- Podcast: "Core Principles of 7 Customized Care Programs"
- Q&A through AI interaction

### 🎭 Interactive Elements
- **Mouse-tracking Eye Module**: Attention-grabbing element in hero section
- Smooth scroll animations
- Card hover effects and fade-in animations

### 📖 Educational Resource Downloads
- **PDF Guides**: Detailed program guides and lesson plans
- **Audio Guides**: Audio materials for learning core principles
- Offline learning materials accessible anytime

## 🏗️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **CSS Framework**: Tailwind CSS (CDN)
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Manrope, Inter, Noto Sans KR)
- **Responsive Design**: Mobile-first approach
- **Animations**: Intersection Observer API, CSS Transitions
- **Interactive Elements**: Mouse tracking, Eye movement simulation

## 🎨 Design System

### Color Palette
- **Deep Navy (#001F3F)**: Main brand color
- **Golden Brown (#996515)**: Secondary accent color
- **Warm Beige (#F5F1E8)**: Background color
- **Soft Cream (#FEFCF8)**: Light background

### Typography
- **Korean**: Noto Sans KR
- **English**: Manrope (logo and main text)
- **Display**: Inter (secondary text)

### Logo Design
- **PILATES**: Manrope font, Deep Navy color, Bold (700)
- **HODU**: Manrope font, Golden Brown color, Bold (700)
- **Spacing**: ml-1 (0.25rem) - same spacing as website

## 📱 Page Structure

```
index.html
├── Header (Navigation + PILATES HODU Logo)
├── Hero Section (Interactive Eye Module + Main Introduction)
├── Programs Overview (7 Program Detailed Cards)
│   ├── Pain Rehabilitation Pilates
│   ├── Mannequin Tone Pilates
│   ├── FlexCore Program
│   ├── Golf Pilates
│   ├── Kids/Teen Growth Pilates
│   ├── Prenatal & Postnatal Pilates
│   └── Senior Pilates
├── NotebookLM AI Guide (AI Guide Section)
└── Footer (Contact & Links)
```

## 🚀 Getting Started

### 1. Local Development Environment Setup
```bash
# Clone project
git clone [repository-url]
cd pilatesdhodu-program-guide

# Run local server (Python)
python -m http.server 8000

# Or Node.js
npx serve .

# Or open directly in browser
open index.html
```

### 2. View in Browser
```
http://localhost:8000
```

## 📋 Program Detailed Guides

### 1. **Pain Rehabilitation Pilates**
- **Goal**: Chronic pain relief and functional recovery
- **Target**: Spine disorders, arthritis, musculoskeletal disease patients
- **References**: Program introduction, PART1_Pain Rehabilitation Program Basics (2019), Medical Pilates principles and application
- **Consultation**: Family Medicine/Anti-aging Specialist Lee Yong-seung

### 2. **Mannequin Tone Pilates**
- **Goal**: Weight loss and obesity body type management
- **Target**: Adults requiring weight management
- **References**: Program introduction, PART2_Mannequin Tone Program Basics (2019), Healthy diet Pilates exercises
- **Consultation**: Family Medicine/Anti-aging Specialist Lee Yong-seung

### 3. **FlexCore Program**
- **Goal**: Scoliosis improvement and body type correction
- **Target**: Scoliosis patients, adults needing body type imbalance improvement
- **References**: Program introduction, Scoliosis exercise therapy, Schroth method

### 4. **Golf Pilates**
- **Goal**: Swing improvement and distance enhancement
- **Target**: Golfers wanting to improve performance
- **References**: Program introduction, Golf biomechanics, Medical Pilates™ Golf Master

### 5. **Kids/Teen Growth Pilates**
- **Goal**: Growth promotion and body type correction
- **Target**: Growing children and adolescents
- **References**: Program introduction, Growth period exercise therapy, Adolescent body type correction

### 6. **Prenatal & Postnatal Pilates**
- **Goal**: Prenatal/postnatal management and body type correction
- **Target**: Pregnant women and postpartum women
- **References**: Program introduction, Prenatal exercise therapy, Postpartum recovery exercises

### 7. **Senior Pilates**
- **Goal**: Muscle strength maintenance and balance enhancement
- **Target**: Middle-aged and elderly
- **References**: Program introduction, Elderly exercise therapy, Fall prevention exercises

## 🔗 External Links

- **NotebookLM AI Guide**: [AI Guide Direct Link](https://notebooklm.google.com/notebook/3161dbc2-9c84-4ec6-827f-4c60eb4945ee?artifactId=8d3c9f7b-fa01-44c2-a8a1-01753cf246e0)
- **Official Website**: [Pilates HODU](https://ysl1016.github.io/pilateshodu/)

## 📁 File Structure

```
pilatesdhodu-program-guide/
├── index.html              # Main landing page (latest design)
├── index_backup.html       # Backup file
├── README.md              # Project documentation
├── data/                  # Educational resource files
│   ├── PILATES HODU Program Guides & Lesson Plans.docx.md
│   └── Pilates, From Pain to Dementia Prevention! 7 Customized Care Core Principles Deep Dive.m4a
└── Interactive Eye-Following Card (Community)/  # Design reference project
    ├── src/
    │   ├── App.tsx
    │   ├── components/
    │   │   ├── EyeCard.tsx
    │   │   └── Eye.tsx
    │   └── styles/
    │       └── globals.css
    └── vite.config.ts
```

## 🎯 Target Users

- **Pilates HODU Instructors**
- **New Staff Members**
- **Program Operation Managers**
- **Education and Training Personnel**

## 🔧 Customization

### Color Changes
Modify CSS variables in `index.html` to change brand colors:

```css
:root {
    --deep-navy: #001F3F;      /* Main color */
    --golden-brown: #996515;   /* Secondary color */
    --warm-beige: #F5F1E8;    /* Background color */
    --soft-cream: #FEFCF8;     /* Light background */
}
```

### Font Changes
Modify Google Fonts link to use different fonts:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Manrope:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Content Modifications
Directly modify HTML content in each section to update program information or guide content.

## 🆕 Recent Updates

### v2.0 (2024)
- **Complete Design System Redesign**: Based on Interactive Eye-Following Card project
- **Interactive Eye Module**: Added mouse tracking functionality to hero section
- **Card Size Unification**: Unified layer sizes for all program sections
- **Logo Design Improvement**: Applied PILATES HODU logo identical to website
- **Font System**: Integrated Manrope, Inter, Noto Sans KR
- **Reference Updates**: Added consultation information from Family Medicine/Anti-aging Specialist Lee Yong-seung

### v1.0 (2024)
- Basic program guide structure construction
- Implementation of 7 program detailed content
- AI guide section addition

## 📞 Contact & Support

- **Address**: 2F, 27 Sinbanpo-ro 33-gil, Seocho-gu, Seoul, Republic of Korea
- **Phone**: 02-547-3345
- **Email**: pilateshodu@naver.com

## 📄 License

© 2024 Pilates HODU. All rights reserved.  
Medical Pilates™ is a registered trademark.

---

**🏥 Medical Expertise** | **🎯 Systematic Education** | **🤖 AI-Based Learning** | **👁️ Interactive Experience**