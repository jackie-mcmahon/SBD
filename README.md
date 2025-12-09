# SBD
Scripts by Design Sabre Scripts

## Sharing Executable Files

This repository is configured to track and share .exe files publicly. You can add executable files directly to the repository.

### How to Add .exe Files

1. Place your .exe file in the repository directory
2. Add it to git: `git add yourfile.exe`
3. Commit the file: `git commit -m "Add yourfile.exe"`
4. Push to GitHub: `git push`

The .exe files will be publicly accessible through GitHub once pushed.

### Notes

- .exe files are binary files and can increase repository size
- Consider file size limits (GitHub has a 100MB file size limit per file)
- For very large files (>50MB), consider using Git LFS (Large File Storage)
