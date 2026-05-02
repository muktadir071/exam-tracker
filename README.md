# 🌸 HSC Study Tracker

A beautiful, modern study progress tracker specifically designed for HSC (Higher Secondary Certificate) students. Track your chapter-wise preparation across multiple subjects with an intuitive interface.

## ✨ Features

- **📊 Real-time Progress Tracking**: Track completion status for CQ (Constructed Questions) and MCQ (Multiple Choice Questions) for each chapter
- **⏱️ Exam Countdown**: Live countdown timer to your HSC exam date
- **🎨 Beautiful Dark Theme UI**: Modern gradient design with smooth animations
- **🌸 Animated Background**: Floating flower animations for a calming study environment
- **🔗 Shareable Progress**: Generate shareable links to show your progress to friends
- **💾 Local Data Persistence**: All progress automatically saved to browser storage
- **📱 Mobile Optimized**: Fully responsive design for studying on any device
- **🎉 Milestone Celebrations**: Confetti animations when reaching 25%, 50%, 75%, and 100% completion

## 🏆 Supported Subjects

- **পদার্থ** (Physics) - ⚛️
- **রসায়ন** (Chemistry) - 🧪
- **জীববিজ্ঞান** (Biology) - 🔬
- **গণিত** (Mathematics) - 📐
- **ইংরেজি** (English) - 📚

Each subject contains 2 papers with multiple chapters per paper.

## 🚀 How to Use

### Getting Started
1. Open the application in your web browser
2. You'll see the HSC Tracker dashboard with a countdown timer

### Tracking Your Progress
1. **Select a Subject**: Click on the subject tabs to view chapters
2. **Mark Completion**: For each chapter, toggle:
   - **CQ Button**: Mark when you've practiced constructed questions
   - **MCQ Button**: Mark when you've practiced multiple choice questions
3. **View Progress**: 
   - Overall progress bar at the top shows your total completion
   - Individual subject progress is shown per paper
   - Statistics card displays: ✅ Done, 🔄 Partial, 📌 Pending chapters

### Sharing Your Progress
1. Click the **"🔗 Progress শেয়ার করো"** button
2. Copy the generated link
3. Share with friends or teachers to showcase your preparation

### Data Management
- Click the **🗑️** button to reset all progress (requires confirmation)
- All data is stored locally in your browser

## 🛠️ Technical Details

- **Pure Frontend**: No backend required, no server dependencies
- **Technology Stack**: HTML5, CSS3, JavaScript (Vanilla)
- **No Dependencies**: Works offline, no npm packages needed
- **Browser Storage**: Uses localStorage for data persistence
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop

## 📅 Exam Date

The app is configured for HSC Exam: **July 2, 2026**

To modify the exam date, edit the `updateCountdown()` function in the JavaScript code and change:
```javascript
const examDate = new Date(2026, 6, 2, 9, 0, 0).getTime();
```

## 🎨 Color Scheme

- **Pink**: #ff6b9d - Primary action
- **Purple**: #a855f7 - Secondary elements
- **Blue**: #3b82f6 - Physics subject
- **Green**: #22c55e - Completion indicator
- **Dark Background**: #0f0a1e

## 📝 Data Format

Progress is saved as JSON in localStorage with the structure:
```json
{
  "subject_id": {
    "paper_index": {
      "chapter_index": {
        "cq": boolean,
        "mcq": boolean
      }
    }
  }
}
```

## 🌐 Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile Browsers: ✅ Full support

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Muktadir071** - HSC Study Tracker Creator

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs as issues
- Suggest improvements
- Submit pull requests with enhancements

## 💡 Tips for Effective Study

1. Set realistic daily goals
2. Track both CQ and MCQ to ensure balanced preparation
3. Focus on subjects with lower completion rates
4. Review chapters before marking as complete
5. Share your progress to stay motivated
6. Use the countdown to manage your study timeline

---

**Happy Studying! 🎯📚** \nGood luck with your HSC examinations!