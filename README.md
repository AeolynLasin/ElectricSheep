# ElectricSheep
# 🧠 Electric Sheep: Presumption-Free Personality Assessment via LLMs  
*An open framework for bias-free psychological profiling through dynamic dialogues*  

> **Note**: This is a **conceptual prototype** from independent research. Implementation contributions welcome!

## 🚀 Core Innovations  
1. **Red Lines Ruleset**  
   - Prohibits self-referential questions (*"Describe yourself"*) → Eliminates self-presentation bias  
   - Bans preset options (*"A or B?"*) → Prevents framing effects  
   - [View rule design](figures/redlines.pdf)  

2. **Dynamic Assessment Engine**  
   - Generates context-aware follow-up questions based on user responses  
   - Terminates when sufficient personality evidence is collected  
   - [See workflow](figures/workflow.pdf)  

## ⚙️ Usage (Theory-Only Version)  
### For Researchers  
```bash
# 1. Compile paper (requires LaTeX)
pdflatex paper.tex

# 2. Cite this work
@misc{ElectricSheep2025,
  author = {AeolynLasin},
  title  = {Electric Sheep: Presumption-Free Personality Assessment},
  year   = {2025},
  url    = {https://github.com/AeolynLasin/ElectricSheep/}
}
