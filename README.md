# José D. Gutiérrez - CV

This repository contains my professional curriculum vitae, managed as code using the YAML format and **RenderCV**.

## 🚀 About this project

Unlike traditional CVs edited manually in word processors, this project uses a **"CV-as-code"** approach. The information is maintained in a structured data file (`JOSE_GUTIERREZ_CV.yaml`), which allows for:

- **Versatility:** Generate multiple formats (PDF, HTML, Markdown) from a single source.
- **Version Control:** Track changes through Git.
- **Consistency:** Professional design guaranteed by predefined templates.

## 🛠️ Tools

This CV is powered by [**RenderCV**](https://rendercv.com/), an open-source tool that transforms YAML files into resumes with professional typography (utilizing LaTeX/Typst under the hood, without the need to write complex code).

You can check the [official RenderCV Documentation](https://docs.rendercv.com/) for more details on how to customize the design or fields.

## 📂 Repository Structure

- `JOSE_GUTIERREZ_CV.yaml`: The main file containing all my profile information, experience, education, and skills.
- `README.md`: This informative file.

## ⚙️ How to generate the CV locally

If you want to render the CV yourself, make sure you have Python installed and follow these steps:

1. **Install RenderCV:**

   ```bash
   pip install "rendercv[full]"
   ```

2. **Render the YAML file:**

   ```bash
   rendercv render JOSE_GUTIERREZ_CV.yaml
   ```

This will create a folder named `output` (or similar, depending on settings) with the PDF version and other formats.

---
José D. Gutiérrez
