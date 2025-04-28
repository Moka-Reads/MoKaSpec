**1. Overview**
This specification outlines the goals and intended audience—authors, editors, and collaborators—providing clear guidance and best practices for preparing MoKa Reads research papers.
Defines standards for authoring, formatting, and publications under the MoKa Reads Foundation.

**2. Purpose**
- Consistency and accessibility across all MoKa Reads research papers.
- Facilitate collaboration and version control.
- Uphold open-education and open-source principles.

**3. Document Structure**
1. **Title Page**
   - Title of Paper
   - Author(s)
   - Institution / Affiliation
   - Date of Submission
   - (Optional) Running Title

2. **License / Copyright / Metadata**
   - Copyright Notice
   - License for Reuse (e.g., CC-BY)
   - DOI (Digital Object Identifier)
   - Submission Date / Publication Date

3. **Acknowledgements** (Optional)
   - Credit to funding bodies, collaborators, advisors, etc.

4. **Abstract**
   - Concise summary of purpose, methods, results, and conclusion (150–250 words).
   - Comes **before** Table of Contents.

5. **Table of Contents** (Optional for shorter papers)
   - Lists major sections (Introduction, Methods, Results, etc.)

6. **Body of the Paper**
   - Organized into **Major Sections** or **Chapters**.

   Structure:
   - **Level 1 Heading**: Major Sections or Chapter Titles (centered)
     - Examples: "INTRODUCTION", "METHODS", "RESULTS", "DISCUSSION"
   - **Level 2 Heading**: Sections within Major Sections (left-aligned, bold)
     - Example: "2.1 Data Collection"
   - **Level 3 Heading**: Subsections (smaller, italic or bold italic)
     - Example: "2.1.1 Sample Demographics"

7. **Summary / Conclusion**
   - Recap key findings, implications, and future directions.

8. **Appendix** (Optional)
   - Supplementary material, such as additional data, code, or detailed calculations.

9. **References**
   - Full bibliographic listing, following the required citation style
   - We prefer to use springer-basic-author-date

**4. File Formats & Naming Conventions**
- Primary source: Typst (.typ)
- Output: PDF (.pdf)
- Figures: SVG (.svg) or high-res PNG (.png)
- Code listings: standalone code files

**Naming Convention:**
`<title>.typ`

**5. Typography & Layout**
- Body text font: Libertinus Serif
- Code font: New Computer Modern
- Math font: New Computer Modern Math
- Line spacing: 1
- Margins: 1" all around

**6. Figures, Tables & Equations**
- Numbered sequentially
- Captions placed below figures, above tables
- Equations centered with numbering on right

**7. Supplementary Material**
- Data files: CSV, JSON
- Code: GitHub repository link with commit hash
- Additional figures: clearly labeled

**Recommended Tools**
- No developed tools at the moment, but we plan to develop a template called `cappuccino`
