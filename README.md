PDF Cracker — Educational / Testing Tool

Important — Read before using:
This repository is intended only for lawful, ethical, and educational use (e.g., recovery of passwords for your own documents, defensive research, classroom demonstrations). Do not use this tool on files you do not own or do not have explicit written permission to test. Unauthorized password-cracking is illegal and unethical.

Project Overview

PDF Cracker is a proof-of-concept utility created for academic and defensive purposes to demonstrate how weak or short passwords on PDF files can be brute-forced and why strong encryption and password policies matter. The project is suitable for lab demonstrations, coursework, and study of defensive countermeasures.

The implementation intentionally focuses on demonstrating methodology, performance trade-offs, and defenses rather than providing tools for misuse.

Features

Brute-force / wordlist-based attempts against password-protected PDFs (intended for use on files you own).

Support for password generation modes (for controlled lab testing).

Configurable concurrency to demonstrate time vs. resource trade-offs.

Progress reporting and simple logging of attempts.

Safe sample data and examples included in samples/.

Ethical & Legal Notice

Only run this tool on PDFs you own or for which you have explicit written authorization.

If you perform security testing as part of a program (bug-bounty, company audit, coursework), follow the program’s rules and responsible disclosure policy.

Misuse can lead to legal penalties. The author is not responsible for misuse of this code.

Requirements

Python 3.8+

Dependencies (example): pikepdf, tqdm, concurrent.futures (or standard library), argparse
