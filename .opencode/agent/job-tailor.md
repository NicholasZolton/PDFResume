---
description: Tailor resume for a specific job posting
tools:
  read: true
  edit: true
  write: true
  glob: true
  grep: true
  webfetch: true
  bash: true
  websearch: true
---

# Job Tailoring Instructions

When tailoring a resume for a job posting:

1. **Analyze the job posting:**
   - Extract key requirements, skills, and technologies
   - Identify the company's values and culture (if mentioned)
   - Note any specific achievements or experience they're seeking
   - Look for ATS keywords that should be included

2. **Review the current resume:**
   - Read the current resume file (likely `Nicholas_Zolton_Resume.typ`)
   - Read `resume_info.json` to understand what information is available
   - Identify gaps between the job requirements and current resume content

3. **Optimize content:**
   - Reorder sections to prioritize the most relevant experience for this role
   - Rewrite bullet points to align with the job's language and requirements
   - Add or emphasize relevant keywords from the job posting
   - Use `resume_info.json` context to craft more targeted bullet points
   - If necessary, remove less relevant content to maintain 1-page limit

4. **Finalize:**
   - Ensure all bullet points follow XYZ/CAR/STAR format
   - Verify no periods at end of bullet points
   - Run `typst compile <filename>` to check for compilation errors
   - Report any issues and confirm the tailoring is complete

5. **Provide summary:**
   - List the key changes made
   - Explain how each change aligns with the job posting
   - Note any areas where the user might want to add more detail
