# Power BI Projects

## 1. Black Line Fraud on ATM machine
- Data: output from AI model (black line fraud detection)
- Objective: To raise alarm after same fraud appear on the 45 cheques.
- Below is the analysis of ATM12
  
![atm12](https://github.com/user-attachments/assets/88b4fb2a-fa72-4b49-b187-cc13ca2942fd)

#### Findings:
- There are 2 significant fraud black lines appear from this atm machine.
- The fraud black line located horizontally at coordinate 140 and 95.
- The thickness of black lines are varied. 3 pixel black line thickness at 140 (y-axis) and 25 pixel black line thickness at 95 (y-axis).
- 1st black line detected at only 83% from all 45 cheques.
- 2nd black line detected at all 45 cheques. (100% confidence score)
- Due to high confidence score, the system will raise the alarm to notify the staff for the ATM cleaning.
