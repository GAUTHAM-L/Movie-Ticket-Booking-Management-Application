### Conclusion 🎬

The project concludes with the automated resolution of the Movie Ticket Request lifecycle, ending in the dispatch of a confirmation notification (US-008). On case resolution, a Correspondence rule maps the case's dynamic properties — Case ID, Movie Name, Show Date & Time, Number of Tickets, Seat Numbers, and Total Cost — into a structured confirmation email. This removes the need for manual tracking and gives the customer immediate visibility into their booking status.

https://github.com/user-attachments/assets/35051e8d-746d-4fe3-8933-c8313458114f

[NIP_Project_Submission_Filled.pdf](https://github.com/user-attachments/files/31619769/NIP_Project_Submission_Filled.pdf)

**📩 Sample Output — Confirmation Email**

- **Subject:** Movie Ticket Booking Confirmed – `[Case ID]`
- **Salutation:** Dear `[Customer Name]`,
- **Message:** Your movie ticket booking has been successfully confirmed.
- **Booking Details:**
  - Case ID: `[Case ID]`
  - Movie Name: `[Movie Name]`
  - Show Date & Time: `[Show Date & Time]`
  - Number of Tickets: `[Number of Tickets]`
  - Seat Numbers: `[Seat Numbers]`
  - Total Cost: `[Total Cost]`
- **Instructions:** Please arrive before show time and present your booking details at entry.
- **Sign-off:** Thank you for choosing our services. Enjoy your movie! — CineWave Entertainment Booking Support Team
