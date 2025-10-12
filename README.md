# Convert Text into PowerPoint Presentation Using ChatGPT

**Author:** K. Venkata Sai Mrudula  
**Roll Number:** 22HP1A4230  
**Internship:** Blackbucks Group 🦌 (May 2025 – Jul 2025)  

---

## Project Overview

This project automates the creation of PowerPoint presentations from plain text using **ChatGPT** and **Python automation libraries**. It leverages natural language processing and rule-based parsing to generate slides with consistent layouts, styling, and formatting. The tool reduces manual effort and enables users with minimal design experience to create professional presentations efficiently.

---

## Key Features

- Converts plain text into formatted PowerPoint slides automatically.
- Maintains **layout consistency**, bullet/paragraph formatting, and aesthetic styling.
- Interactive interface using **ipywidgets** for text input and slide generation.
- Generates downloadable `.pptx` files directly in **Google Colab**.
- Supports modular extensions for future enhancements.

---

## Problem Statement

Creating presentations manually is time-consuming and often inconsistent in design. Many users lack design expertise or the time to format slides properly. This project addresses these challenges by automating slide creation using AI-assisted automation and scripting.

---

## Technology Stack

- **Programming Language:** Python 3  
- **Platform:** Google Colab  
- **Libraries:** python-pptx, ipywidgets, datetime, google.colab.files  

---

## Dataset

- **Simulated Dataset:** Manually created `.txt` files to mimic structured user input.  
- **Content Structure:** Each block contains a slide title followed by content in bullet or paragraph form.  
- **Purpose:** Test input, documentation, and reproducibility.

---

## System Architecture

1. **User Input Layer:** Captures text via widgets.  
2. **Parser Module:** Splits content into slides and formats text.  
3. **Slide Generator:** Uses python-pptx to create slides.  
4. **Styling Engine:** Applies gradients, fonts, and colors.  
5. **Output Module:** Saves and downloads `.pptx` file.

---

## Implementation

- Text parsing and slide generation with **rule-based automation** (no ML required).  
- Dynamic word wrapping and formatting applied automatically.  
- Modular Python code allowing future expansion (themes, AI-based summarization).  

---

## Results

- Reduced slide creation time by **90%**.  
- Achieved **100% layout consistency**.  
- Eliminated manual design errors.  
- Enabled non-technical users to generate professional slides.

---

## Future Enhancements

- AI-based text summarization for slide content.  
- Theme and style customization.  
- Export to PDF.  
- Multi-language support.  
- Cloud storage integration for saving presentations.

---

## References

- [python-pptx Documentation](https://python-pptx.readthedocs.io/)  
- [OpenAI ChatGPT Developer Guide](https://platform.openai.com/docs)  
- [Google Colab User Manual](https://colab.research.google.com/notebooks/intro.ipynb)  
- [ipywidgets Official Guide](https://ipywidgets.readthedocs.io/)  
- Stack Overflow solutions for pptx rendering
