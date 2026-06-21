# Confidential – TryHackMe Writeup

This repository contains my writeup for the TryHackMe room **Confidential**.

The room focused on inspecting a PDF case file that contained a hidden invite code. The QR code was not removed from the document; it had been covered by a separate image layer. After creating a working copy of the PDF, moving the image aside, and decoding the uncovered QR code, the flag was recovered.

## Topics Covered

* Basic PDF file inspection
* Creating and preserving a working copy of evidence
* Reviewing PDF content in LibreOffice Draw
* Identifying separate image layers within a PDF
* Extracting embedded images with pdfimages
* QR-code recovery and decoding

## Tools Used

* file
* LibreOffice Draw
* pdfimages
* ZXing Decoder Online

## Writeup

[View the full writeup](./Confidential-tryhackme-writeup.pdf)

## Disclaimer

This writeup was created for educational and portfolio purposes only. All testing was performed in the relevant lab environment.

© 2026 Osman Dhaqane. All rights reserved.
