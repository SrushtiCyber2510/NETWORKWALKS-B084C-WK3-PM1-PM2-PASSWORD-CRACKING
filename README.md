# NETWORKWALKS – WEEK 3
## Password Cracking with JTR and Networkwalks Tools

### Internship: Cybersecurity & Ethical Hacking

This repository contains my Week 3 work completed as part of the Networkwalks Cybersecurity Internship.

The Week 3 essential modules covered password cracking using **John the Ripper (JTR)** and **Networkwalks password-cracking tools**.

---

## 📌 Objectives

- Understand the basic process of password cracking.
- Extract password hashes from a protected PDF.
- Perform password cracking using John the Ripper and Johnny.
- Use Networkwalks Hash Calculator and Password Cracker.
- Understand dictionary-based password attacks.
- Document the results and maintain evidence of the practical work.

---

# 🔐 PM1 – Password Cracking with JTR

## Tools Used

- John the Ripper (JTR)
- Johnny GUI
- Windows
- Protected PDF file

## Procedure

1. Obtained the hash of the password-protected PDF.
2. Saved the extracted hash in `hash1.txt`.
3. Installed and configured Johnny with John the Ripper.
4. Loaded the hash file into Johnny.
5. Started the password-cracking attack.
6. The attack completed successfully.
7. The password was recovered as:

```text
good-luck
```

8. Used the recovered password to open the protected PDF successfully.

## Result

The password was successfully cracked using **John the Ripper/Johnny**, and the protected PDF was opened successfully.

## Evidence

PM1 evidence is available in:

```text
PM1-JTR/screenshots/
PM1-JTR/outputs/
```

---

# 🌐 PM2 – Password Cracking with Networkwalks Tools

## Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Protected PDF file

## Procedure

1. Uploaded the protected PDF to the Networkwalks Hash Calculator.
2. Generated the PDF password hash.
3. Saved the generated hash in `pdf-hash.txt`.
4. Opened the Networkwalks Password Cracker.
5. Pasted the complete PDF hash.
6. Tested the built-in password dictionary.
7. The built-in dictionary attack was exhausted without finding a match.
8. The result displayed **Access Denied / Not cracked with this wordlist**.
9. A larger RockYou wordlist was also attempted, but the web page became unresponsive during the attack.
10. The password recovered during PM1 was used to verify that the protected PDF could be opened successfully.

## Result

The **hash extraction using the Networkwalks Hash Calculator was successful**.

The Networkwalks Password Cracker was tested with its built-in dictionary, but it did not crack the password during this run. The result and verification evidence have been documented.

## Evidence

PM2 evidence is available in:

```text
PM2-NW-TOOLS/screenshots/
PM2-NW-TOOLS/outputs/
```
---

# 📚 Learning Outcomes

Through this week's practical work, I gained hands-on experience with:

- Password hash extraction.
- John the Ripper and Johnny.
- Dictionary-based password attacks.
- Password cracking workflows.
- Networkwalks Hash Calculator.
- Networkwalks Password Cracker.
- Working with password-protected PDF files.
- Maintaining structured cybersecurity evidence.

---

# ✅ Conclusion

Week 3 provided practical exposure to password-cracking techniques using both **John the Ripper** and **Networkwalks cybersecurity tools**.

PM1 was successfully completed using JTR/Johnny, while PM2 demonstrated the hash-generation and password-cracking workflow and documented the result of the dictionary attack.
