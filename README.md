
## 4. Load API Keys
Use the provided setup code.

## 5. Run the Notebook Cells
Proceed step-by-step:
- Configure LLM
- Define agents
- Define tasks
- Create crew
- Run the research pipeline
- Download the generated report

---

"""
}

# Save files
paths = []
for filename, content in files.items():
    path = f"/mnt/data/{filename}"
    with open(path, "w", encoding="utf-8") as f:
        f.write(content)
    paths.append(path)

paths
