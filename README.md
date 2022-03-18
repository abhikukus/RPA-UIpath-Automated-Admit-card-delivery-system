# Automated Admit Card delivery system

Automated Admit Card delivery system is a RPA (Robotic Process Automation) bot which has its use case in Examination cell department. Our bot will help the department to send a mail having original admit card as attachment to all student’s personal email id with lots of other features mentions below.

## Running the bot

- Install UIpath and all mention [dependencies](#dependencies) and open main.xaml file in UIpath. Hit run button.
- Demo video [here](https://youtu.be/Ou5LJWAjDvM)

## Technologies Used

- RPA - Robotic Process Automation
- UIpath community edition.

## Features

- Live Status GUI which displays current activity information and Overall progress of process.
- Summary Message Box with success and errors and show after execution has finished.
- Error Summary Report automatically produced in Excel format in .\debug directory which contains status-SUCCESS/FAIL and Error Type if FAIL for each row entry.
- Error Handling:
  - Invalid Email - Validity check of Email using Regular Expressions.
  - Bad Network - Mails failed to send due to Network timeout is accounted for in summary report Excel file.
  - Roll no. Doesn’t Exits.

## Dependencies

- UiPath.Excel.Activities : 2.11.4
- UiPath.Mail.Activities : 1.12.3
- UiPath.PDF.Activities : 3.5.0-preview
- UiPath.System.Activities : 21.10.4
- UiPath.UIAutomation.Activities : 21.10.5
- UiPathTeam.StatusProgress.Activities : 1.0.2
