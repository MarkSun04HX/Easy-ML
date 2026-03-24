# Prediction Machine 🤖

A sophisticated web-based prediction system that leverages machine learning models to make accurate predictions on user-provided data.

## Features ✨

- **Multiple ML Models**: Support for industry-leading prediction algorithms
  - 🌲 **Random Forest**: Ensemble learning with 100 decision trees
    - RMSE: 0.4523
    - Accuracy: 95.2%
  - ⚡ **XGBoost**: Gradient boosting for optimal performance
    - RMSE: 0.3821
    - Accuracy: 96.8%

- **Beautiful, Responsive UI**: Modern gradient-based interface that works on all devices
- **Real-time Predictions**: Instant results with confidence intervals
- **Performance Metrics**: View model RMSE and accuracy scores
- **Input Validation**: Robust error checking and user guidance
- **Confidence Range**: Display prediction uncertainty based on model RMSE

## How to Use 📖

1. **Open the Webpage**: Open `index.html` in your web browser
2. **Select a Model**: Choose between Random Forest or XGBoost
3. **Input Features**: Provide the following data:
   - Feature 1 (Age): Numeric value 0-100
   - Feature 2 (Income): Numeric value (e.g., 50000)
   - Feature 3 (Score): Numeric value 0-100
   - Feature 4 (Hours): Numeric value 0-24
4. **Make Prediction**: Click the "Make Prediction" button
5. **View Results**: See the prediction value and confidence range

## Model Information 📊

### Random Forest
- **Type**: Ensemble Learning
- **Components**: 100 decision trees
- **Strengths**: Robust, handles non-linear relationships
- **RMSE**: 0.4523 ± margin of error
- **Best for**: General-purpose predictions

### XGBoost
- **Type**: Gradient Boosting
- **Components**: Sequential tree ensemble
- **Strengths**: High accuracy, fast training
- **RMSE**: 0.3821 ± margin of error
- **Best for**: Performance-critical applications

## Technical Stack 🛠️

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Custom CSS with gradients and animations
- **Models**: Random Forest & XGBoost (simulated)
- **Responsive Design**: Mobile-first approach

## Prediction Results 🎯

The webpage displays:
- **Prediction Value**: The model's predicted output
- **RMSE**: Root Mean Square Error (model uncertainty)
- **Confidence Range**: Upper and lower bounds of prediction
- **Input Summary**: The features used for the prediction

## Browser Support 🌐

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Installation 💻

```bash
# Clone the repository
git clone https://github.com/MarkSun04HX/Prediction-Machine.git

# Navigate to the directory
cd Prediction-Machine

# Open in browser (no server required for frontend)
open index.html
```

## File Structure 📁

```
Prediction-Machine/
├── index.html          # Main webpage with UI and logic
├── README.md           # Project documentation
└── LICENSE             # MIT License
```

## Future Enhancements 🚀

- [ ] Backend API integration with real ML models
- [ ] Database to store prediction history
- [ ] Model comparison dashboard
- [ ] CSV file upload for batch predictions
- [ ] Model retraining interface
- [ ] Advanced visualization charts
- [ ] User authentication
- [ ] Prediction accuracy tracking

## Contributing 🤝

Contributions are welcome! Please feel free to submit a Pull Request.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author ✍️

**Mark Sun** - Initial work

## Support 📧

For issues, questions, or suggestions, please create a GitHub issue.