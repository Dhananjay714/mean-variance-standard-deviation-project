📊 Mean, Variance, and Standard Deviation Calculator

A Python project to calculate the mean, variance, standard deviation, maximum, minimum, and sum of a given 3×3 matrix of numbers using NumPy.

This project was built as part of a data analysis learning exercise.

📦 Features
- Converts a list of 9 numbers into a 3×3 NumPy array
- Computes:
  - Mean
  - Variance
  - Standard Deviation
  - Maximum
  - Minimum
  - Sum
- Provides results:
  - Along rows
  - Along columns
  - For the entire matrix (flattened)

🗂️ Project Structure
.
├── mean_var_std.py       # Core calculation logic
├── main.py               # Script to test your function
├── test_module.py        # Unit tests for verification
└── README.txt             # Project description (this file)

🛠️ Requirements
- Python 3.x
- NumPy

Install required package:
pip install numpy

▶️ How to Run
Run the program using:
python main.py

✅ Example
from mean_var_std import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
print(result)

Output:
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.67, 0.67, 0.67], 6.67],
  'standard deviation': [[2.45, 2.45, 2.45], [0.82, 0.82, 0.82], 2.58],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}

🧪 Run Tests
To verify everything works:
python -m unittest test_module.py

🌐 Project Link
🔗 View Project on GitHub: https://github.com/Dhananjay714/mean-variance-standard-deviation-project

📌 Author
Dhananjay Wadhi
