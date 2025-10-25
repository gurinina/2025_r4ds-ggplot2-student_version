# Student Guide (RStudio only): Notes, Codebook, and Updates

This guide shows how to **work safely in RStudio without using Terminal**. You’ll keep your copy up to date and your own notes separate so updates never conflict.

---

## What “Rproject main directory” means
Your **Rproject main directory** is the folder that contains the course `.Rproj` file. Open the project by double‑clicking that `.Rproj` file.

We’ll keep all personal work inside a folder named **`students_notes/`** at the *Rproject main directory*.

---

## One‑time setup (RStudio UI only)
**Make your personal codebook from the template**

   - In the **Files** pane, navigate to `lessons/` and locate:  
     **`01_ggplot2_layers.Rmd`**
     In this chapter, you’ll expand on your ggplot2 foundation. We’ll start with a deeper dive into aesthetic mappings, 
     geometric objects, and facets.
     
   - Check the box next to that file → click **More** → **Copy To…**
   
   - In the dialog, choose the **`students_notes/`** folder and set the new name to: 
   
     **`<lastname>01_ggplot2_layers_codebook.Rmd`** (for example, `garcia_01_ggplot2_layers_codebook.Rmd`) → **OK**.
     
   - Do the same thing for the file **'02_ggplot2_communication.Rmd'**
     This chapter will focus on making effective figures for publication purposes.
   
   - Set the new name to **`<lastname>01_ggplot2_communication_codebook.Rmd**
   
   - Click the new files in `students_notes/` to open them. These are now **your** working copies for the homework.

> From now on, **work only inside `students_notes/`**. Anything you create or edit there is yours and won’t interfere with course updates.

---

## Getting instructor updates (no Terminal)

- Use the **Git** pane → click **Pull** to fetch the latest course changes.
- If you ever see files listed in the Git pane that you didn’t mean to change, click the file → **Revert** (Discard) to return to the instructor version, then **Pull** again.

> Your `students_notes/` folder is set up by the instructor to be ignored by Git. If it ever appears in the Git pane, **do not stage it**—just keep working in that folder.

---

## Everyday workflow

1. Open the project (`.Rproj` file) in the **Rproject main directory**.
2. **Git pane → Pull.**
3. Work in files **inside `students_notes/`** only (e.g., your codebook).
4. If something shows in the Git pane that you didn’t intend to change → **Revert** it.

---

---

## FAQ

**Q: Where do I put my notes and answers?**  
A: In `students_notes/` at the **Rproject main directory**.

**Q: Will updates overwrite my notes?**  
A: No. Your notes live in `students_notes/`, separate from course files.

**Q: I accidentally edited a course file outside `students_notes/`.**  
A: Use the **Git** pane → select the file → **Revert**. Then **Pull** to sync.

**Q: Do I need to push?**  
A: No. Students don’t push. Just **Pull** to get updates.
