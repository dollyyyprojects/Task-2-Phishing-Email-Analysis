Task 2: Phishing Email Analysis

Project Overview

This project focuses on analyzing a suspicious email to identify common phishing characteristics and understand how phishing attacks attempt to deceive users.

Objective

To examine a suspicious email sample and identify phishing indicators such as sender inconsistencies, suspicious links, urgent language, and other warning signs.

Sample Email

A simulated phishing email impersonating Microsoft 365 Support was used for this analysis.

Analysis Performed

- Sender Analysis: Examined the sender's email address, display name, and Reply-To address.
- Header Analysis: Attempted to analyze the available email header information using Google Admin Toolbox Messageheader.
- Link Analysis: Identified and examined the suspicious link included in the email.
- Urgency Analysis: Identified threatening and urgent language used to pressure the recipient.
- URL Analysis: Checked the destination URL and its relevance to the claimed organization.
- Spelling and Grammar Analysis: Reviewed the email for spelling, grammar, and generic wording.

Key Findings

- The sender's domain did not match Microsoft's official domain.
- The Reply-To address used a different domain.
- The email contained a suspicious HTTP link.
- The email used urgent language and threatened possible account suspension.
- The available header information was insufficient for complete authentication checks.
- No obvious spelling or grammar errors were found.

Tools Used

- Google Admin Toolbox – Messageheader
- Text editor
- Manual email analysis

Project Structure

- "Sample_Email/" – Contains the simulated phishing email sample.
- "Analysis_Report/" – Contains the final phishing email analysis report.

Conclusion

The email displayed multiple suspicious characteristics commonly associated with phishing attempts. This task helped develop an understanding of phishing indicators, email analysis, suspicious URLs, and social engineering techniques.

Note: The email used in this project is a simulated sample created for educational purposes. No live phishing link was opened or tested.
