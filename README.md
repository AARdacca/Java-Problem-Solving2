# 📘 Java Problem Solving Exercises

**📄 [View Code & Output on Google Docs](https://docs.google.com/document/d/1zKmDUObmGlSxFw9a1TOGYZ8KwSIVHDM2/edit?usp=sharing&ouid=102981712591594829857&rtpof=true&sd=true)**

This project showcases a series of Java programming problems designed to practice fundamental problem-solving, algorithm design, and Java syntax. Each problem is paired with a brief explanation of the logic used to solve it.

---

## 🔢 Problem Statements & Approaches

Each question is followed by the marks allocated:

### 1. **Find the 2nd Highest CGPA** (Marks: 10)
- **Input**: `[3.50, 3.52, 3.43, 3.63, 3.48, 3.32, 3.30, 3.60, 3.86, 3.75]`
- **Approach**: Linear traversal to identify the highest and second-highest CGPAs without sorting.

---

### 2. **Sort CGPAs in Descending Order** (Marks: 10)
- **Approach**: Manual sorting using nested loops (no use of `Arrays.sort()`).

---

### 3. **Binary Search on CGPA** (Marks: 5)
- **Input**: User-entered CGPA
- **Approach**: Sort the array in ascending order and perform binary search manually.

---

### 4. **Random Integer Array: Min & Max** (Marks: 5)
- **Approach**: Generate 10 random numbers and find the minimum and maximum values through iteration.

---

### 5. **Break Down an Amount into Notes** (Marks: 10)
- **Input**: `546`
- **Output**:
  ```
  500 1
  20 2
  5 1
  1 1
  ```
- **Approach**: Use modulus and division to calculate note counts for each denomination.

---

### 6. **Print Number Pattern** (Marks: 5)
```
12345
1234
123
12
1
12
123
1234
12345
```
- **Approach**: Use nested loops to build the pattern symmetrically.

---

### 7. **Find the Two Smallest Heights** (Marks: 10)
- **Input**: Heights of 10 babies (in cm)
- **Approach**: Manual comparison during array traversal to find the two smallest unique values.

---

### 8. **Text Statistics** (Marks: 5)
- **Input**: "I am a SQA Engineer"
- **Output**:
  - Words: 5  
  - Characters (no space): 15  
  - Vowels: 8  
  - Consonants: 7
- **Approach**: Loop through characters and classify them using helper methods.

---

### 9. **Binary String Validator** (Marks: 5)
- **Input**: `1001` → ✅ Valid  
- **Input**: `2001` → ❌ Invalid  
- **Approach**: Check each character; if all are `0` or `1`, it's valid.

---

### 10. **Random Password Generator (8 characters)** (Marks: 5)
- **Rules**:
  - At least 1 uppercase letter
  - At least 1 lowercase letter
  - At least 1 digit
  - At least 1 special character
- **Sample Output**: `1eGh$3pH`
- **Approach**: Use `Random` and character pools to generate and shuffle a valid password.

---

### 11. **Remove Vowels from a String** (Marks: 5)
- **Input**: "I am a SQA Engineer"  
- **Output**: "m sq ngnr"
- **Approach**: Loop through characters and skip vowels.

---

### 12. **Extract Prices & Apply Discount** (Marks: 10)
- **Input**: Sentence containing prices.
  - Laptop: 85000 tk
  - Mouse: 2500 tk
- **Output**: Total after 15% discount
- **Approach**: Use Regex to extract numbers, calculate total and discount.

---

### 13. **Extract Transaction ID from HTML** (Marks: 5)
- **Input**:
  ```html
  <p>Transaction Id: TXN1234</p>
  ```
- **Output**: `Transaction Id: TXN1234`
- **Approach**: Use Jsoup to parse and extract data using selectors.

---

### 14. **Validate IP Address** (Marks: 5)
- **Rules**:
  - Must have 4 parts
  - First part must not start with 0 or be a single digit
- **Examples**:
  - `192.168.0.1` → ✅ Valid  
  - `172.16.56` → ❌ Invalid  
  - `0.0.0.1` → ❌ Invalid  
  - `1.12.72.2` → ❌ Invalid  
- **Approach**: Split string and validate each segment.

---

### 15. **Distribute 15 Questions Worth 100 Marks** (Marks: 5)
- **Condition**: Some questions are worth 5 marks, others 10
- **Output**:
  ```
  5 marks question is 10  
  10 marks question is 5
  ```
- **Approach**: Loop through possible combinations and check total marks.

---

## 📥 How to Submit
1. Create the project using IntelliJ Community Edition.
2. Assign meaningful class names for each Java file.
3. Copy your program codes into a Google Doc and attach screenshots of outputs.
4. Add `.idea`, `build`, and `.gradle` to `.gitignore`.
5. Upload the entire project to GitHub.
6. Add the Google Doc file link to the `README.md`.

---

## 📙 Technologies Used
- Java (JDK 8+)
- Scanner, Random, StringBuilder
- Jsoup (for HTML parsing)
- Regex for string extraction

---

## 👨‍💼 Author
**Ali Ahasan**
