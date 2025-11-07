# Student Guide: Working with RStudio and Git

This guide shows how to **work safely in RStudio without using Terminal**. You'll keep your copy up to date and your own work separate so updates never conflict.

---

## What "Rproject main directory" means

Your **Rproject main directory** is the folder that contains the course `.Rproj` file. Open the project by double-clicking that `.Rproj` file.

We'll keep all personal work inside a folder named **`student_notes/`** in the Rproject main directory.

---

## One-time setup (RStudio UI only)

**Create your personal workbook from the templates:**

1. In the **Files** pane, navigate to the `templates/` folder
2. You'll see these files:
   - `01_ggplot2_layers_STUDENT.Rmd`
   - `02_ggplot2_communication_STUDENT.Rmd`
   
3. **Copy each file to `student_notes/`:**
   - Check the box next to the file
   - Click **More → Copy To...**
   - Navigate to `student_notes/`
   - Click **Choose**
   
4. **Navigate to `student_notes/` folder**

5. **Rename each file** to include your last name:
   - Right-click → Rename
   - Example: `garcia_01_ggplot2_layers_STUDENT.Rmd`
   - Do the same for the communication file
   
6. **Open your renamed files** - these are now YOUR working copies for exercises and homework

> **Important:** From now on, work ONLY inside `student_notes/`. Anything you create or edit there is yours and won't show up in Git, so you won't accidentally push changes.

---

## Getting instructor updates (no Terminal)

- Use the **Git** pane → click **Pull** to fetch the latest course changes
- Your work in `student_notes/` is safe and won't be affected by updates

> Your `student_notes/` folder is ignored by Git. Your work there will never appear in the Git pane - you can work freely!

---

## Everyday workflow

1. Open the project (`.Rproj` file) in the Rproject main directory
2. **Git pane → Pull** (get latest updates)
3. Work in your renamed files inside `student_notes/` only
4. Save your work frequently (Ctrl+S or Cmd+S)
5. Knit your Rmd files to check your work

---

## FAQ

**Q: Where do I put my notes and answers?**  
A: In the files you renamed inside `student_notes/` (e.g., `garcia_01_ggplot2_layers_STUDENT.Rmd`)

**Q: Will updates overwrite my notes?**  
A: No. Your notes live in `student_notes/`, which Git ignores. They're completely safe.

**Q: I don't see `student_notes/` folder!**  
A: Create it: In Files pane → **New Folder** → name it `student_notes`

**Q: Do I need to push my changes?**  
A: No. Students don't push. Just **Pull** to get updates from the instructor. Your work in `student_notes/` won't show in the Git pane anyway.

**Q: I accidentally edited a template file in `templates/`.**  
A: Use the **Git** pane → select the file → **Revert**. Then copy the template again to `student_notes/` and rename it.

**Q: What if I need help?**  
A: Ask in class, office hours, or email your instructor!