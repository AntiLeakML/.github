This organization represents AntiLeak ML Team, brought together by working on the [**Antileak-ML - VS Code Extension**](https://github.com/AntiLeakML/antileak-ml)

**Antileak-ML** is a Visual Studio Code extension designed to help developers detect and prevent data leakage in Python scripts and Jupyter Notebooks. It analyzes your code for potential data leakage issues and provides visual feedback directly in the editor, making it easier to identify and fix problems.

This is an engineering project realized by a team of engineering students at EFREI (École d'Ingénieurs Généraliste du Numérique).

The team is composed of :

    - Achraf BEN BACCAR
    - Nathan CARLIER
    - Thierno-Sadou DIALLO
    - Danny GRAINE
    - Léo PETIT
    - Emerick SZONYI


## Core concepts

This projects aims at detecting data leakages in machine learning projects, by running a static analysis of the code through a VS Code extension.

There are 3 kinds of leakages that our extension is able to detect:

- ### Preprocessing Leakage:
  When training data and test data are preprocessed (transformed) together, test data sometimes influences the transformations of the training data
  
- ### Overlap Leakage:
  A type of data leakage in machine learning that occurs when training and test sets share similar or identical data. This distorts the model's evaluation, as it has already seen samples from the test set during training, leading to an overestimation of its performance
  
- ### Multitest Leakage:
  A type of data leakage that occurs when the same test set is used several times to evaluate a model, distorting the real evaluation of its performance

## Contact

For questions, feedback, or support, please open an issue on the [GitHub repository](https://github.com/AntiLeakML/antileak-ml).

---

Enjoy using **Antileak-ML** to detect and prevent data leakage in your Python and Jupyter projects! 🚀
