# [Email Analysis] Look at that headers!

## The Boogeyman is here!
Julianne, a finance employee working for Quick Logistics LLC, received a follow-up email regarding an unpaid invoice from their business partner, B Packaging Inc. Unbeknownst to her, the attached document was malicious and compromised her workstation.

<div>
<img src="https://github.com/Modern-Wizard/-Email-Analysis-Look-at-that-headers-/blob/main/ss2.png" />
</div>

The security team was able to flag the suspicious execution of the attachment, in addition to the phishing reports received from the other finance department employees, making it seem to be a targeted attack on the finance team. Upon checking the latest trends, the initial TTP used for the malicious attachment is attributed to the new threat group named Boogeyman, known for targeting the logistics sector.

You are tasked to analyse and assess the impact of the compromise.

## Investigation Guide
Given the initial information, we know that the compromise started with a phishing email. Let's start with analysing the dump.eml file located in the artefacts directory. There are two ways to analyse the headers and rebuild the attachment:

    The manual way uses command-line tools such as cat, grep, base64, and sed. Analyse the contents manually and build the attachment by decoding the string located at the bottom of the file.

<div>
<img src="" />
</div>
