# 🧪 AA Test Analysis Tool

A comprehensive statistical validation tool for experimental setup testing.

## 🚀 Live Demo

Visit the live demo: [https://yourusername.github.io/aa-test-analysis](https://yourusername.github.io/aa-test-analysis)

## 📋 Features

- **Sample Data Generation**: Creates 10,000 synthetic users with realistic behavior patterns
- **Random Assignment**: Consistent hash-based user grouping (like real A/B testing platforms)
- **Statistical Analysis**: Multiple statistical tests including:
  - Sample Ratio Mismatch detection
  - Chi-square tests for conversion rates
  - T-tests for continuous metrics
  - Two-proportion Z-tests
- **Interactive Dashboard**: Real-time results with visual feedback
- **Mobile Responsive**: Works on all devices

## 🔬 What is AA Testing?

AA testing validates your experimental infrastructure by:
- Splitting users into two identical groups
- Applying the same treatment to both groups
- Checking for unexpected differences
- Ensuring your randomization works correctly

## 📊 Key Metrics Analyzed

- **Conversion Rate**: Percentage of users who convert
- **Revenue**: Average revenue per user
- **Page Views**: Average pages viewed per session
- **Sample Ratio**: Verification of equal group sizes

## 🎯 Expected Results

For a properly functioning AA test:
- P-values > 0.05 (not statistically significant)
- Group sizes within 1-2% of each other
- Small, random differences between groups
- Overall test assessment: PASSED

## 🛠️ Technical Implementation

- **Frontend**: Pure HTML, CSS, JavaScript
- **Statistics**: Custom implementation of statistical tests
- **Data Generation**: Realistic user behavior simulation
- **Deployment**: GitHub Pages ready

## 📈 Usage

1. Click "Run AA Test Analysis"
2. Wait for data generation (10,000 users)
3. Review statistical results
4. Check final assessment
5. Use insights to validate your A/B testing setup

## 🔧 Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. No build process required - pure client-side application

## 📄 License

MIT License - feel free to use and modify for your projects.

## 🤝 Contributing

Contributions welcome! Please feel free to submit pull requests.

---

Built with ❤️ for data-driven experimentation
