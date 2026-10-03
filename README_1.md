# Student Attendance (GitHub Pages)

A simple attendance page. Teachers mark Present/Absent per course; students check only their own record.

## Put it online
1. Create a GitHub repo and upload `index.html` (and this README).
2. Create a folder named `data` (upload any file into it, e.g. a `.gitkeep`).
3. Go to **Settings → Pages**, choose branch `main`, folder `/ (root)`, Save.
4. Your site will be at `https://<your-username>.github.io/<repo-name>/`.

## Teacher
1. Open the site → **I'm a Teacher** → set a PIN (first time only).
2. Add a course: name, code (e.g. `math101`) and a student passcode.
3. Add students: one per line as `roll, name`.
4. Pick a date, tap **P** or **A** for each student (or "All present"), then **Save**.
5. Tap **Publish this course** → a file like `math101.json` downloads.
   Upload it into the repo's `data` folder (GitHub → Add file → Upload files). Re-publish after each update.

Your attendance data lives in the browser you used. Use **Download backup** now and then, and **Restore backup** to move to another device.

## Student
Open the site → enter course code, roll number and the course passcode → see your attendance.

## Privacy
Each student's record is encrypted with the course passcode + their roll number, and stored per course. Students of another course don't have that passcode, so they cannot read it, and a student can only decrypt their own record. The teacher PIN is just a convenience lock on the teacher screen, not real security.
