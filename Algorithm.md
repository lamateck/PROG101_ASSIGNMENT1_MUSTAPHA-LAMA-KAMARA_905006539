 Algorithm 1: Resident Report Submission

Purpose: To allow residents to submit complaints about poor waste management and blocked drainage.

Steps:

1. Start.
2. Request the resident’s details and complaint information.
3. Receive the resident’s name, contact information, location and complaint category.
4. Check whether all required fields have been completed.
5. If any required information is missing, display an error message and request the resident to enter the missing information.
6. Check whether the selected complaint category is valid.
7. If the category is invalid, display an error message and request a valid category.
8. Generate a unique Report ID.
9. Save the complaint details in the system.
10. Set the report status to Pending.
11. Display a confirmation message together with the Report ID.
12. End.

Algorithm 2: Administrator Report Management

Purpose: To allow administrators to view submitted complaints and update their progress.

Steps:

1. Start.
2. Administrator opens the system.
3. Request the Report ID.
4. Receive the Report ID entered by the administrator.
5. Search for the report in the system.
6. Check whether the report exists.
7. If the report does not exist, display a message stating that the report was not found.
8. If the report exists, display the report details.
9. Allow the administrator to select an action:
    * Start work on the complaint.
    * Mark the complaint as completed.
    * Keep the complaint pending.
10. Update the report status according to the selected action:
    * In Progress.
