
# SAT-Solving implementations to Adversary Emulation tools using Grover's Quantum algorithm

In an effort to enhance the development of Adversarial Emulation engagements and Red Teaming exercises, we present the following proposal using Boolean Satisfiability Solving (SAT Solving) which can be very useful to evaluate commonly known attacker concepts such as tactics, techniques and procedures, through a logical strategy, improving the efficiency and the effectiveness of emulation tools and plans. While there are already widely utilized modular tools and also well-structured applications composed of matrices or graphical layouts such as MITRE ATT&CK navigator, designed to be simple and generic, there are subtle (and numerous) constraints to be identified and analyzed towards a successful Red team operation. For a reasonable number of constraints a classical computer might be sufficient for analyzing them and generating a result with any SAT solver extension, but as this number increases the boolean-path chaining problems this type of tools are designed to solve are computationally intensive, hence the necessity for a quantum speed up arises. However, it is possible to recast this problem into a search problem being able to explore over every combination of inputs and determine which inputs evaluate to “True” given our initial constraints. Grover's search quantum algorithm capabilities in solving satisfiability problems, implemented in Qiskit, will show its advantages over the classical way approach giving an approximation of a Quantum SAT solver tool to tackle these adversary emulation matters.

This code was utilzed for supporting the experiment described at: https://www.linkedin.com/pulse/sat-solving-implementations-adversary-emulation-tools-vel%25C3%25A1zquez-/


## Authors

- [@fvelazquez](https://www.github.com/fvelazquez-X)


## Acknowledgements

 - [Awesome qiskit learning resources]( https://qiskit.org/learn)
 - [Atacking the quantum internet](https://arxiv.org/abs/2005.04617)
 - [Enterprise tactics. ATT&CK](https://attack.mitre.org/tactics/enterprise/)


## Deployment

To run this project from a terminal using jupyter notebook:

- Firstly, you need to convert the jupyter notebook file which is in the format .ipynb to .py format using the jupyter nbconvert tool.
```bash
jupyter nbconvert --to <output format> <input notebook>
```

 Whereas, the <output format> is the desired output format. And the <input notebook> is the jupyter notbook filename.

- Verify whether .py file is created in your working directory.

- Finally, you could run a jupyter notebook .ipynb file from command prompt using the converted .py file as shown below.

```bash
   python MyFirstNotebook.py
```

## Documentation

[IBM Quantum Experience](https://quantum-computing.ibm.com/)


## Feedback

If you have any feedback, please reach out to us at jvelazqu@redhat.com


## 🚀 About Me

- 🔭 I’m an offensive security passionate working at [Red Hat](https://www.redhat.com/en)  
  

-  🔎 I’m currently learning more about [Quantum Technologies](https://quantum-explore.com/en/master/)   
  

- 📖 I recently wrote a book on Offensive Quantum Computing. Available at [Amazon](https://www.amazon.com/Introduction-Adversarial-Quantum-Computing-Practice-ebook/dp/B09YMJXQTX/ref=sr_1_1?crid=3VZONRJBAP2G3&keywords=fernando+velazquez+quantum&qid=1654154138&sprefix=%2Caps%2C138&sr=8-1)!!  
  

- ⚡ I publish articles on technology topics at  [Meer](https://www.meer.com/en/authors/390-fernando-velazquez)  


## License

[MIT](https://choosealicense.com/licenses/mit/)

