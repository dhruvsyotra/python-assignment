# COM-501 Python Assignment

This repository contains the code for all five milestones of the COM-501 assignment. The milestones build on the same photography storage-management scenario.

## Where to find each question's code

| Assignment question | File name | What the file contains |
|---|---|---|
| **Q1 – Milestone 1** | `q1.py` | Inputs for one shoot, data types, MB/GB calculations, remaining card space, duration conversion, and session-code string slicing. |
| **Q2 – Milestone 2** | `q2.py` | Multiple shoots, shoot-type dictionary, input validation, list of sessions, unique-type set, storage categories, totals, and sorting. |
| **Q3 – Milestone 3** | `q3.py` | `MemoryCard` and `PhotoSession` classes, methods, objects, and composition. |
| **Q4 – Milestone 4** | `main.py` and `photo_utils.py` | Reusable functions, user-defined module, `math.ceil()`, `*args`, keyword/default arguments, weekly summary, and report timing. |
| **Q5 – Milestone 5** | `main.py` and `photo_utils.py` | Persistent shoot logs, directory/file creation, reading saved records, file size, input validation, and exception handling. |

## Folder structure

```text
Digital_Photo_Manager/
│
├── README.md                 # This guide: where the code for each question is
├── .gitignore                # Files Git should ignore
│
├── q1.py                     # Q1 code
├── q2.py                     # Q2 code
├── q3.py                     # Q3 code
│
├── photo_utils.py            # Reusable functions/module for Q4 and Q5
├── main.py                   # Main integrated application for Q4 and Q5
│
└── photo_logs/
    └── shoot_log.txt         # Sample saved shoot records; new records append here
```

## How to run the programs

You need Python 3. No third-party packages are required.

Open a terminal in the `Digital_Photo_Manager` folder.

Run the individual milestone programs:

```bash
python q1.py
python q2.py
python q3.py
```

Run the final integrated application for Q4 and Q5:

```bash
python main.py
```

When `main.py` asks for a shoot type, enter one of:

- `Portrait`
- `Event`
- `Landscape`
- `Product`
- `Sports`

Enter `DONE` when you have finished entering sessions. Successfully accepted sessions are appended to `photo_logs/shoot_log.txt`.

## Important notes

- The application uses **1 GB = 1024 MB** for storage calculations.
- `main.py` imports reusable functions from `photo_utils.py`. Keep both files in the same folder.
- The `photo_logs` folder and log file are created automatically if they do not exist when a session is saved. A sample log file is included in this repository.
- Q1, Q2, and Q3 are separate milestone demonstrations. Q4 and Q5 are represented by the integrated final application.
