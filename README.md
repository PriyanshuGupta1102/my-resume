# LaTeX Resume with Fully Automated PDF Releases

This repository contains my personal resume, written in LaTeX. It uses a GitHub Actions workflow to fully automate the release process.

Every time a change to `resume.tex` is pushed to the `main` branch, the workflow will automatically:

1.  Generate a new version tag based on the current date (e.g., `v2025.07.23`).
2.  Create a new GitHub Release with this tag.
3.  Compile the latest `resume.tex` into a PDF.
4.  Attach the `Priyanshu_Gupta_Resume.pdf` to the new release.

## Getting the Latest Resume

The most up-to-date version of my resume is always available from the **[Releases Page](https://github.com/PriyanshuGupta1102/your-repo-name/releases)**.

1.  Go to the **[Releases Page](https://github.com/PriyanshuGupta1102/your-repo-name/releases)**.
2.  The release at the top is the newest one.
3.  Under the **Assets** section of that release, download the `Priyanshu_Gupta_Resume.pdf` file.

*(Note: You will need to replace `your-repo-name` with the actual name of your GitHub repository in the links above.)*

## How to Update the Resume

The process is now extremely simple.

### Step 1: Edit the Resume

Make your desired changes to the `resume.tex` file in this repository.

### Step 2: Push to Main

Commit and push your changes to the `main` branch. The GitHub Actions workflow will handle the rest.

### Local Compilation (Optional)

If you want to preview your changes locally before pushing, you will need a LaTeX distribution installed (like [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/)).

Once installed, you can compile the `.tex` file into a PDF by running the following command in your terminal from the project's root directory:

```bash
pdflatex resume.tex```

This will generate a `resume.pdf` in your local directory for you to review.

## Contact

*   **Email:** [pg0000742@gmail.com](mailto:pg0000742@gmail.com)
*   **LinkedIn:** [linkedin.com/in/priyanshu-gupta-4ba240259](https://www.linkedin.com/in/priyanshu-gupta-4ba240259)
*   **GitHub:** [github.com/PriyanshuGupta1102](https://github.com/PriyanshuGupta1102)
