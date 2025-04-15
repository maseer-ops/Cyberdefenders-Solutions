# CyberDefenders Solutions

This repository contains the solutions to the challenges I solved on CyberDefenders.org. The repository is organized by challenge and includes relevant scripts and solutions.

## Challenge: Web Shell Identification and Mitigation

In this challenge, the task was to analyze the attack, identify the geographical origin, and determine the details of the attacker's activities, such as the malicious web shell uploaded and the vulnerabilities exploited.

### Questions and Answers

1. **Q1: Identifying the geographical origin of the attack helps in implementing geo-blocking measures and analyzing threat intelligence. From which city did the attack originate?**
   - **A1:** Tianjin

2. **Q2: Knowing the attacker's User-Agent assists in creating robust filtering rules. What's the attacker's User-Agent?**
   - **A2:** Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/115.0

3. **Q3: We need to determine if any vulnerabilities were exploited. What is the name of the malicious web shell that was successfully uploaded?**
   - **A3:** image.jpg.php

4. **Q4: Identifying the directory where uploaded files are stored is crucial for locating the vulnerable page and removing any malicious files. Which directory is used by the website to store the uploaded files?**
   - **A4:** /reviews/uploads/

5. **Q5: Which port, opened on the attacker's machine, was targeted by the malicious web shell for establishing unauthorized outbound communication?**
   - **A5:** 8080

6. **Q6: Recognizing the significance of compromised data helps prioritize incident response actions. Which file was the attacker attempting to exfiltrate?**
   - **A6:** passwd

---

## Instructions

### Clone the Repository

To begin analyzing or reviewing the solutions, you can clone the repository to your local machine:

```bash
git clone https://github.com/maseer-ops/CyberDefenders-Solutions.git
# CyberDefenders Solutions

This repository contains the solutions to the challenges I solved on CyberDefenders.org. The repository is organized by challenge and includes relevant scripts and solutions.

## Challenges Solved

- **Challenge 1**: [Name of the challenge]
- **Challenge 2**: [Name of the challenge]
- ...

## Solution Files

- **webshell-exercise/answers.txt**: This file contains the answers to the questions in the webshell challenge.
- **other files**: Description of other relevant files you may have (scripts, logs, etc.)

## Contributions

Contributions are welcome! If you'd like to contribute to this repository:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes and commit them
4. Push to your forked repository
5. Create a pull request

Please make sure your changes are well-documented and tested.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
