# Text Data Type in LabVIEW

This LabVIEW project demonstrates the usage of string (text) data types and event-driven programming to handle user interactions and display different messages based on numeric inputs.

## Overview

The program contains an event structure that handles specific value changes in user controls, including numeric and stop commands. When different numeric values are entered, the program generates corresponding string outputs and displays them to the user.

## Features

1. **Event-Driven String Handling**
   - The program utilizes an event structure to respond to changes in the numeric controls (`Один`, `Два`, and `Три`) and a stop command.

2. **Event Cases and String Operations**
   - **Timeout Event:**
     - If no user interaction occurs within a specified period, the program triggers a default event with the numeric value `0`, and the output string indicator is set to `Default`.

   - **"Один" Value Change Event:**
     - When the numeric control labeled `"Один"` is updated, the string output displays `"Один"` as the corresponding value.

   - **"Два" Value Change Event:**
     - Changing the value of the numeric control labeled `"Два"` sets the output string to `"Два"`.

   - **"Три" Value Change Event:**
     - When the numeric control labeled `"Три"` changes, the program outputs the string `"Три"`.

   - **"stop" Value Change Event:**
     - When the `"stop"` button is pressed, the program generates the output string `"stop"` and terminates the operation.

## How It Works

- **Event Structure**:  
  The program uses an event structure to listen for user actions and respond by generating corresponding text outputs. Depending on which numeric control changes, the program displays the associated string value on the output indicator.

- **String Outputs**:  
  String indicators provide feedback on the current control value, allowing users to observe how the input affects the output in real time.

## Usage

- Run the VI and interact with the numeric controls (`Один`, `Два`, `Три`).
- Observe how changing each numeric control results in a different text output being displayed.
- Use the `"stop"` button to terminate the program.

## Requirements

- LabVIEW software is required to open and run the VI.

## Code
![image](https://github.com/user-attachments/assets/e99b4a49-8969-4f1a-a297-36d84e82fcba) 
![image](https://github.com/user-attachments/assets/86d70285-bb92-4db2-8509-619555a62c45) 
![image](https://github.com/user-attachments/assets/27415306-ba08-4d6c-ad7a-dc96443647b3) 
![image](https://github.com/user-attachments/assets/498985b4-9ed9-44e0-acb7-8f6d1b02011b) 
![image](https://github.com/user-attachments/assets/abbb65fa-0dcf-4a11-a464-42eb8d6b0181) 

## The appearance of the running program
![image](https://github.com/user-attachments/assets/6a25bf7d-94b7-4dbd-b4f5-53a74e664503) 
![image](https://github.com/user-attachments/assets/55c7f5b6-10af-40ec-ab92-7e5fee0e9fc2) 
![image](https://github.com/user-attachments/assets/44536996-e4ae-4c3f-bf96-7096e06dac5a)
