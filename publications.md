**1. Overview**  
This specification outlines the goals and intended audience—authors, editors, and collaborators—providing clear guidance and best practices for preparing MoKa Reads publications.  
Defines standards for authoring, formatting, and publications under the MoKa Reads Foundation.

**2. Purpose**
- Consistency and accessibility across all MoKa Reads publications.
- Facilitate collaboration and version control.
- Uphold open-education and open-source principles.

**3. Scope**  
Applies to the manuscript of the publication to be under the MoKa Reads Foundation. We hold a cap of a book to only contain 6 chapters. 

**4. Document Structure**  
1. Title Page
2. License, Copyrights, Publish Dates, ISBN  
3. Acknowledgements 
4. Preface
5. Table of Contents
6. Chapters
	- Use level 1 heading under centered alignment for chapters 
	- Use level 2 heading for sections, and so on
	- Contain a summary of the chapter 
	- After the summary have a mini table of content (`machiatto.minitoc`)
7. References

**5. File Formats & Naming Conventions**
- Primary source: Typst (.typ)
- Output: PDF (.pdf)
- Figures: SVG (.svg) or high-res PNG (.png)
- Code listings: standalone code files 

**Naming Convention:**  
`<project>_v<major>.<minor>.typ`

**6. Metadata Requirements**
- Title
- Authors (Name, Affiliation)
- Date
- Version
- License (e.g., CC BY 4.0)

**7. Typography & Layout**
- Body text font: Libertinus Serif
- Code font: New Computer Modern
- Math font: New Computer Modern Math
- Line spacing: 1
- Margins: 1" all around

**8. Citation & Reference Style**
- Citation Style: Springer-Basic-author-date
- Bibtex to organize references

**9. Figures, Tables & Equations**
- Numbered sequentially
- Captions placed below figures, above tables
- Equations centered with numbering on right

**10. Supplementary Material**
- Data files: CSV, JSON
- Code: GitHub repository link with commit hash
- Additional figures: clearly labeled

**11. Version Control & Collaboration**
- Use Git for source control
- Pull request template and review checklist

**12. Review & Approval Workflow**
- Draft submission
- Peer review (2+ reviewers)
- Revision cycle
- Final manuscript


**Recommended Tools**
- [Machiatto](https://github.com/Moka-Reads/machiatto)
	- The Machiatto typst package is aimed to follow the MoKa Reads specification for publications whilst allowing authors to develop visually stunning publications. 