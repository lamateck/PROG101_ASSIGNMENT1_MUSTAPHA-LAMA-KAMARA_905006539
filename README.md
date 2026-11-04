# PROG101_ASSIGNMENT1_MUSTAPHA-LAMA-KAMARA_905006539
A logical system design for reporting and monitoring poor waste management and blocked drainage problems in Sierra Leone  Resources
# Community Waste Management and Drainage Reporting System (CWDRS)

## 1. Project Overview

The Community Waste Management and Drainage Reporting System (CWDRS) is a proposed system designed to address poor waste management and blocked drainage problems in Sierra Leone.

The system provides a logical approach for residents to report waste-related problems and allows administrators to monitor submitted complaints and update their progress.

This project is developed as part of the PROG101: Principles of Programming Logic and Design assignment at Limkokwing University of Creative Technology, Sierra Leone.

## 2. Problem Statement

Poor waste management and blocked drainage systems are major environmental challenges in many communities in Sierra Leone. These problems contribute to flooding, environmental pollution, unpleasant surroundings and health risks.

The proposed system aims to improve how these problems are reported, recorded and monitored.

## 3. Project Objectives

The main objectives are to:

* Provide a simple way for residents to report waste management and drainage problems.
* Validate information submitted by residents.
* Generate a unique identification number for every report.
* Categorise complaints according to the type of problem.
* Allow administrators to monitor reports and update their statuses.
* Improve the organisation and tracking of community complaints.

## 4. Main System Features

* Resident complaint submission.
* Report information validation.
* Complaint categorisation.
* Unique Report ID generation.
* Report status tracking.
* Administrator report management.
* Report summary generation.

## 5. Complaint Categories

The system will recognise the following complaint categories:

1. Uncollected household waste.
2. Overflowing rubbish containers.
3. Blocked drainage channels.
4. Illegal waste dumping.

## 6. Report Status

Each complaint will have one of the following statuses:

* Pending: The report has been received.
* In Progress: Action is being taken.
* Resolved: The reported problem has been addressed.

## 7. Computational Thinking Concepts

The project applies the following computational thinking concepts:

* Decomposition
* Pattern Recognition
* Abstraction
* Algorithm Design

## 8. Technologies and Tools

The project uses the following tools for its logical design and documentation:

* GitHub – Project storage and version control.
* Microsoft Word – Assignment documentation.
* Flowcharts – Visual representation of system processes.
* Pseudocode – Description of the system’s logical steps.

## 9. Repository Structure

The repository contains the following project materials:

* Documentation – Project report and explanations.
* Algorithms – Algorithm designs.
* Pseudocode – Logical instructions for the system.
* Flowcharts – Visual diagrams of the system processes.
* Screenshots – Evidence of project development and GitHub activities.

## 10. Expected Outputs

The expected system outputs include:

* Report submission confirmation.
* Unique Report Identification Number.
* Error and validation messages.
* Report status display.
* Updated report information.
* Report summary.

## 11. Project Limitations

The project focuses on logical system design and documentation. It does not represent a fully developed application. It does not physically collect waste or clear blocked drainage channels.

## 12. Sustainable Development Goals

The project supports:

* SDG 11: Sustainable Cities and Communities.
* SDG 3: Good Health and Well-being.

## 13. Conclusion

The Community Waste Management and Drainage Reporting System is proposed as a logical solution to improve the reporting and monitoring of waste management and drainage problems in Sierra Leone. It demonstrates how programming logic and computational thinking can be applied to address real-life community challenges.

⸻

## SCREENSHOT

<img width="1440" height="900" alt="Screenshot 2026-11-04 at 2 47 30 PM" src="https://github.com/user-attachments/assets/117b1955-ffda-49ee-a6f4-0465d0c96018" />

## ALGORITHM DESIGN

## Algorithm 1: Resident Report Submission

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

## Algorithm 2: Administrator Report Management

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

## PSEUDOCODE

Resident Report Submission

BEGIN

    INPUT residentName
    INPUT contactNumber
    INPUT location
    INPUT complaintCategory
    INPUT complaintDescription

    WHILE residentName IS EMPTY OR
          contactNumber IS EMPTY OR
          location IS EMPTY OR
          complaintDescription IS EMPTY

        DISPLAY "Please complete all required fields"

        INPUT residentName
        INPUT contactNumber
        INPUT location
        INPUT complaintDescription

    END WHILE

    IF complaintCategory IS VALID THEN

        GENERATE uniqueReportID

        SAVE reportDetails

        SET reportStatus = "Pending"

        DISPLAY "Report submitted successfully"
        DISPLAY uniqueReportID

    ELSE

        DISPLAY "Invalid complaint category"

    END IF

END

Administrator Report Management

BEGIN

    INPUT reportID

    SEARCH for reportID

    IF reportID EXISTS THEN

        DISPLAY reportDetails

        DISPLAY "Select an action"
        DISPLAY "1. Start Work"
        DISPLAY "2. Complete Work"
        DISPLAY "3. Keep Pending"

        INPUT choice

        IF choice = 1 THEN
            SET reportStatus = "In Progress"

        ELSE IF choice = 2 THEN
            SET reportStatus = "Resolved"

        ELSE IF choice = 3 THEN
            SET reportStatus = "Pending"

        ELSE
            DISPLAY "Invalid selection"

        END IF

        SAVE updatedReport

        DISPLAY reportStatus

    ELSE

        DISPLAY "Report not found"

    END IF

END

## FLOWCHARTS

<img width="2270" height="6085" alt="Complaint Report Validation Pipeline-2026-11-03-171247" src="https://github.com/user-attachments/assets/a9601f04-7eb0-46f5-8446-985a387b1150" />
<img width="3352" height="6820" alt="Administrator Report Status Decision Tree-2026-11-03-171936" src="https://github.com/user-attachments/assets/0beff9df-454c-4200-bb74-b9ae6a3bef31" />

## Author 
-MUSTAPHA LAMA KAMARA-905006539
