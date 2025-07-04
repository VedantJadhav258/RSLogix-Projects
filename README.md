
# RSLogix‑Projects

A curated collection of automation projects developed with Allen‑Bradley RSLogix and Studio 5000, using Ladder Logic and structured XML exports for version control and collaboration during a workshop.

## 📁 Repository Structure

```
/
├── ProjectName1/
│   ├── ProjectName1.acd      # RSLogix/Studio 5000 program file
│   ├── ProjectName1.L5X      # XML-exported version, ideal for diffing in Git
│   └── report.pdf            # Documentation, logic diagrams, test plans
├── ProjectName2/
│   └── ...
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Viewing a project

1. Clone the repo:

   ```sh
   git clone https://github.com/VedantJadhav258/RSLogix-Projects.git
   cd RSLogix-Projects
   ```
2. Open the `.acd` file in RSLogix or Studio 5000.
3. Alternatively, inspect the XML `.L5X` in a text editor.

### Why both `.acd` and `.L5X`?

* **`.acd`** is the native binary project file used for editing and deployment.
* **`.L5X`** is the XML export from RSLogix, enabling clear diffs and merges in version control systems ([github.com][1], [reddit.com][2], [plctalk.net][3]).

### Recommended Workflow

1. **Export** your `.acd` file to `.L5X` via RSLogix (`File → Save as L5X`) before committing.
2. Commit both formats.
3. Use Git to track changes on `.L5X`—great for version history, diffs, and code reviews.

## 🛠 Included Examples

* **Digital Traffic light Controller **: Basic ladder logic for traffic management.
* **Timer and Counter**: Basic control elements demonstration.
* **Latching**: Typical latching operations, sequencing, and interlocks.



## 🧩 Version Control Hints

Want smooth Git-based handling of binary/rich RSLogix files in a team or automation setting?
Check discussions like:

* “Using RSLogix Compare tool with Git” workflows ([github.com][4], [plctalk.net][3])
* Other solutions: exporting `.L5X` for diffing .

## 📝 How to Contribute

* Fork this repo and push your projects (Ladder, `.acd`, `.L5X`, documentation).
* Include a short README in your project folder explaining the logic and purpose.
* Open a pull request—happy to review and merge!



