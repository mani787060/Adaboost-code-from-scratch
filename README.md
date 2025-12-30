# AdaBoost Code From Scratch

This project implements the **AdaBoost (Adaptive Boosting) algorithm from scratch** to understand how boosting works internally, without relying on high-level libraries.

The focus is on **conceptual clarity** rather than performance.

---

## Concepts Covered
- AdaBoost algorithm (from scratch)
- Weak learners using Decision Tree Classifier (stumps)
- Sample weight updating
- Weighted error calculation
- Model weight (alpha) computation
- Decision boundary visualization

---

## Workflow
1. Initialize equal weights for all training samples
2. Train a weak learner (Decision Tree stump)
3. Calculate weighted error
4. Compute model weight (alpha)
5. Update sample weights
6. Repeat for multiple estimators
7. Combine weak learners into a strong classifier
8. Plot decision boundaries to visualize learning

---

## Visualizations
- Decision tree decision boundary
- Combined AdaBoost decision boundary
- Effect of boosting iterations on classification regions

---

## Tech Stack
- Python
- NumPy
- Matplotlib
- Scikit-learn (DecisionTreeClassifier only)

---

## Future Improvements
- Compare with sklearn AdaBoostClassifier
- Add loss curve visualization
- Extend to multi-class AdaBoost
- Implement Gradient Boosting from scratch

