
# 🧠 SAT-Solving for Adversary Emulation Using Grover’s Quantum Algorithm

This project explores the application of Boolean Satisfiability Solving (SAT Solving) to enhance **Adversary Emulation** and **Red Teaming** methodologies. It introduces a novel approach by leveraging **Grover’s quantum search algorithm**, implemented in **Qiskit**, to tackle the complex constraint-solving problems often encountered in emulation planning and attacker behavior modeling.

Traditional tools like the MITRE ATT&CK Navigator offer valuable visualizations and structured matrices, but often fall short when dealing with subtle or numerous constraints required for realistic red team operations. Classical SAT solvers can address many of these constraints; however, their efficiency degrades rapidly with scale due to the computational complexity of Boolean path chaining.

By reframing the constraint problem as a quantum search problem, this project demonstrates how **quantum speed-up** can improve the analysis and execution of complex emulation scenarios. Grover’s algorithm enables evaluation across all input combinations to identify those that satisfy defined conditions, offering an approximation of a **Quantum SAT Solver** purpose-built for adversarial engagements.

This implementation supports the ideas discussed in the article:  
🔗 [SAT-Solving Implementations for Adversary Emulation Tools](https://www.linkedin.com/pulse/sat-solving-implementations-adversary-emulation-tools-vel%25C3%25A1zquez-/)

---

## 📦 Deployment

To run this project locally from a terminal:

1. **Convert the Jupyter Notebook to a Python script** using the `nbconvert` tool:
   ```bash
   jupyter nbconvert --to script your_notebook.ipynb
   ```

2. **Verify** the `.py` file has been created in your working directory.

3. **Run the script** using Python:
   ```bash
   python your_notebook.py
   ```

---

## 📚 Documentation & Resources

- [IBM Quantum Experience](https://quantum-computing.ibm.com/)
- [Awesome Qiskit Learning Resources](https://qiskit.org/learn)
- [MITRE ATT&CK Enterprise Tactics](https://attack.mitre.org/tactics/enterprise/)
- [Attacking the Quantum Internet](https://arxiv.org/abs/2005.04617)

---

## 👥 Authors

- [@fvelazquez](https://github.com/fvelazquez-X)

---

## 💬 Feedback

If you have feedback, suggestions, or encounter issues, feel free to contact:  
📧 **jvelazquez@notlan.mx**

---

## 📝 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
