# 🔬 Experiment 8  
**Name:** Akshit Chordia  
**PRN:** 24070123008 
**Class:** ENTC A1  

## 📌 Title  
**Multidimensional Arrays**  

---

## 🎯 Aim  
To study and implement operations on **multidimensional arrays (2D arrays)** such as input/output, addition, multiplication, transpose, and diagonal summation.  

---

## 📚 Theory  
A **2D array** is an array of arrays, often used to represent matrices or tables in rows and columns.  

- **Declaration:** `int arr[rows][cols];`  
- **Accessing element:** `arr[i][j]`  
- **Applications:** Matrix operations, image processing, tabular data storage, simulations, etc.  

---

## ⚙️ Programs, Algorithms & Explanations  

### 1️⃣ Input and Display a 3×3 Matrix  
**Algorithm:**  
1. Declare a 3×3 matrix.  
2. Take input for all 9 elements.  
3. Print elements in matrix form.  

**Explanation:**  
This builds the foundation of handling 2D arrays with nested loops.  

---

### 2️⃣ Matrix Addition  
**Algorithm:**  
1. Input dimensions of both matrices (must be equal).  
2. Read elements of both matrices.  
3. Add corresponding elements into a result matrix.  
4. Print the result.  

**Explanation:**  
Addition is **element-wise**, requiring equal-sized matrices.  

---

### 3️⃣ Matrix Multiplication  
**Algorithm:**  
1. Input dimensions of both matrices.  
2. Check condition: `columns1 == rows2`.  
3. Multiply using nested loops (row × column rule).  
4. Print the result matrix.  

**Explanation:**  
Each element of the result is obtained by multiplying row elements of the first matrix with column elements of the second and summing them.  

---

### 4️⃣ Matrix Transpose  
**Algorithm:**  
1. Input matrix of size `rows × cols`.  
2. Create another matrix of size `cols × rows`.  
3. Assign `transpose[j][i] = original[i][j]`.  
4. Display the transpose.  

**Explanation:**  
The **transpose** swaps rows and columns (flips over the main diagonal).  

---

### 5️⃣ Sum of Diagonal Elements  
**Algorithm:**  
1. Input size of the matrix.  
2. Ensure it is square (`rows == cols`).  
3. Loop `i = 0 → n-1` and add `arr[i][i]`.  
4. Print the sum.  

**Explanation:**  
The **main diagonal** consists of elements where row index = column index.  

---

## ✅ Conclusion  
- Learned how to declare, input, and display **2D arrays**.  
- Implemented **matrix operations**: addition, multiplication, transpose, and diagonal sum.  
- These are fundamental operations widely used in **mathematics, computer graphics, data processing, and scientific computing**.  

---
