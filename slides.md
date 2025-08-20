---
marp: true
theme: default
paginate: true
paginate-format: 'Page %n of %t'
style: |
  section {
    font-family: 'Segoe UI', sans-serif;
    padding: 2em;
  }
  h1, h2 {
    color: #0078d7;
  }
  code {
    background: #f5f5f5;
    padding: 4px;
    border-radius: 4px;
  }
  footer {
    color: #888;
    font-size: 0.8em;
    text-align: right;
  }
---

<!-- _class: lead -->

# 📘 Product Documentation with Marp  
### For Software Engineering Teams  
📧 **22f2000895@ds.study.iitm.ac.in**

<footer>Welcome to our documentation approach</footer>

---

# 🎯 Goals

- Maintainable in Git
- Easy format conversion (PDF, PPTX, HTML)
- Dev-friendly + user-centric
- Works well with CI/CD pipelines

---

<!-- _backgroundImage: url('./assets/background.jpg') -->
<!-- _color: white -->

# 🚀 Why Good Documentation Matters

- Reduces support requests  
- Speeds up onboarding  
- Improves user satisfaction  
- Supports scalability

---

# 🔧 Tooling Stack

- **Marp CLI** for format conversion
- **Markdown** for simplicity
- **KaTeX** or **MathJax** for equations
- **Git + GitHub** for version control

---

# 🔢 Algorithmic Complexity Example

Consider **binary search**:

$$
T(n) = T\left(\frac{n}{2}\right) + O(1) \Rightarrow T(n) \in O(\log n)
$$

Used in search optimizations throughout the system.

---

# 💻 Sample Code Snippet

```python
def binary_search(arr, target):
    low, high = 0, len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            low = mid + 1
        else:
            high = mid - 1
    return -1

---
<!-- _backgroundImage: url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80') -->
<!-- _color: white -->

---
# 🚀 Why Good Documentation Matters

- Reduces support requests  
- Speeds up onboarding  
- Improves user satisfaction  
- Supports scalability
---
