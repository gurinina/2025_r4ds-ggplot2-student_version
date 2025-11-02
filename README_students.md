# Student Guide: Working with RStudio and Git

This guide shows how to **work safely in RStudio without using Terminal**. You'll keep your copy up to date and your own work separate so updates never conflict.

---

## What "Rproject main directory" means

Your **Rproject main directory** is the folder that contains the course `.Rproj` file. Open the project by double-clicking that `.Rproj` file.

We'll keep all personal work inside a folder named **`student_notes/`** in the Rproject main directory.

---

## One-time setup (RStudio UI only)

**Create your personal codebook from the template:**

1. In the **Files** pane, navigate to `student_notes/`
2. You'll see these files:
   - `01_ggplot2_layers_STUDENT.Rmd`
   - `02_ggplot2_communication_STUDENT.Rmd`
   
3. **Rename each file** to include your last name:
   - Right-click → Rename
   - Example: `garcia_01_ggplot2_layers.Rmd`
   - Do the same for the communication file
   
4. **Open your renamed files** - these are now YOUR working copies for exercises and homework

> **Important:** From now on, work ONLY inside `student_notes/`. Anything you create or edit there is yours and won't interfere with course updates.

---

## Getting instructor updates (no Terminal)

- Use the **Git** pane → click **Pull** to fetch the latest course changes
- If you see files in the Git pane that you didn't mean to change:
  - Click the file → **Revert** (Discard) 
  - Then **Pull** again

> Your `student_notes/` folder is set up to be ignored by Git. If it ever appears in the Git pane, **do not stage it** - just keep working in that folder.

---

## Everyday workflow

1. Open the project (`.Rproj` file) in the Rproject main directory
2. **Git pane → Pull** (get latest updates)
3. Work in files inside `student_notes/` only
4. If something shows in the Git pane that you didn't intend to change → **Revert** it

---

## FAQ

**Q: Where do I put my notes and answers?**  
A: In `student_notes/` in the Rproject main directory.

**Q: Will updates overwrite my notes?**  
A: No. Your notes live in `student_notes/`, which is separate from course files.

**Q: I accidentally edited a course file outside `student_notes/`.**  
A: Use the **Git** pane → select the file → **Revert**. Then **Pull** to sync.

**Q: Do I need to push my changes?**  
A: No. Students don't push. Just **Pull** to get updates from the instructor.

**Q: What if I need help?**  
A: Ask in class, office hours, or post on the course discussion board!