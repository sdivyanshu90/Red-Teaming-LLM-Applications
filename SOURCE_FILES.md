**Notebook source files**

The source companions below preserve notebook cell order and explanations in readable code blocks. Python uses `# %%` cell markers; TypeScript uses `// %%`. The original notebooks retain their saved visualizations and course context. GitHub language statistics exclude `.ipynb` files through `.gitattributes` and count eligible implementation source normally.

Use the original notebook's environment, dependency versions, datasets, credentials and working directory. This conversion does not supply missing course helpers or fill exercise placeholders. It does not execute training, external APIs, shell commands or setup cells during validation. Review setup and execution cells before running a whole lesson.

Run ordinary Python companions with `python "path/to/lesson.py"`, or open their cells in an editor supporting Python percent scripts. Files marked **IPython** retain notebook magics and shell commands: install IPython in the lesson environment and run `ipython "path/to/lesson.py"`. Files marked **async** have an `async def main()` entry point; run the whole script to preserve its event loop. Script validation checks Python syntax, not availability or behavior of the original dependencies.

TypeScript companions preserve the Deno runtime identified by their notebooks. Run them in the original Deno environment with the permissions and dependencies required by that lesson. Repeated notebook declarations use mutable bindings and reassignment in the script. React component variants are separate `.tsx` modules in the adjacent `.components` directory; the lesson's frontend-injection helpers still require the original course environment. No Python translation is implied for TypeScript code.

| Notebook | Source companion | Execution notes |
|---|---|---|
| [notebooks/L1_Overview_of_LLM_vulnerabilities.ipynb](notebooks/L1_Overview_of_LLM_vulnerabilities.ipynb) | [notebooks/L1_Overview_of_LLM_vulnerabilities.py](notebooks/L1_Overview_of_LLM_vulnerabilities.py) | Python |
| [notebooks/L2_Red_teaming_LLMs.ipynb](notebooks/L2_Red_teaming_LLMs.ipynb) | [notebooks/L2_Red_teaming_LLMs.py](notebooks/L2_Red_teaming_LLMs.py) | Python |
| [notebooks/L3_Red_teaming_at_scale.ipynb](notebooks/L3_Red_teaming_at_scale.ipynb) | [notebooks/L3_Red_teaming_at_scale.py](notebooks/L3_Red_teaming_at_scale.py) | Python |
| [notebooks/L4_Red_teaming_LLMs_with_LLMs.ipynb](notebooks/L4_Red_teaming_LLMs_with_LLMs.ipynb) | [notebooks/L4_Red_teaming_LLMs_with_LLMs.py](notebooks/L4_Red_teaming_LLMs_with_LLMs.py) | Python |
| [notebooks/L5_A_full_red_teaming_assessment.ipynb](notebooks/L5_A_full_red_teaming_assessment.ipynb) | [notebooks/L5_A_full_red_teaming_assessment.py](notebooks/L5_A_full_red_teaming_assessment.py) | Python |
