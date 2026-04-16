# GitHub Contribution Graph Pattern Committer

A small Python utility that generates backdated Git commits to draw a pattern on your GitHub contribution graph.

## ⚠️ Disclaimer
This project is only for learning purposes. It demonstrates how Git commit dates can be manipulated locally and should not be used to misrepresent activity or violate GitHub policies.

## Features
- Reads a pattern from `pattern.json`
- Creates backdated commits across a full year
- Writes commit messages to `info.txt`
- Supports custom target years via user input

## Usage
1. Make sure this repository is a local Git repository.
2. Run the script:
   ```bash
   python script.py
   ```
3. Enter the year you want to draw the pattern for (for example, `2022`).
4. The script will generate backdated commits and attempt to push to `origin/main`.

## Files
- `script.py` - main script that generates commits
- `pattern.json` - pattern definition for contribution graph pixels
- `info.txt` - target file updated for each commit

## Notes
- The script uses `GIT_AUTHOR_DATE` and `GIT_COMMITTER_DATE` to set commit timestamps.
- Pushing to GitHub requires a properly configured `origin` remote and authentication.
- Use responsibly and only for learning.

## Quick Links
- GitHub: https://github.com/aonontojahan
- GitHUb Repo: https://github.com/aonontojahan/aonontojahan.github
- Pattern Genarator: https://github-pattern-generator.web.app/

## Author
Created by Aononto Jahan
web: aonontojahan.vercel.app