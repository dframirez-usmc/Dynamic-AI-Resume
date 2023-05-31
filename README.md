# Dynamic-AI-Resume
Given personal written experiences and a job description, OpenAI summarizes experiences into bullets, and LaTeX is compiled with CI/CD.

Writen in **Python + JSON + LaTeX**

Inputs:
- Job requirements description

Personal Info:
- Target job titles
- Personal work experiences

Steps:
- User must fill personal work experiences JSON file
- User must fill job requirements description JSON file with new opportunity
- `python run_resume_generator.py path_to_a_job_req.json`
- Summarize each work experience
    - Get a personal work experience from JSON file
    - Call OpenAI API with prompt to summarize with reguards to the job requirements description
    - Add to LaTeX resume
- Export LaTeX to PDF
- ???
- Profit!
