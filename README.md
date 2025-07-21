# Embedded C Programs for 8051 Microcontroller

## Description:
This repository contains basic Embedded C programs written for the 8051 microcontroller using Keil uVision IDE.

All programs are tested in Keil with virtual output.

---

## List of Programs

### 1️⃣ UART Print ASCII A-Z

**File:** UART_Print_ASCII

**Question:**  
Write a program to transmit ASCII characters from 'A' to 'Z' using UART communication in the 8051 microcontroller. Use `printf()` by retargeting `putchar()`.

---

### 2️⃣ BCD to Binary Conversion

**File:** BCD_to_Binary_Conversion

**Question:**  
Write a program to convert BCD `0x25` into its equivalent binary value and print both the BCD and the Binary value via UART.

---

### 3️⃣ Counter with Delay

**File:** Counter_with_Delay

**Question:**  
Create a simple counter that increments continuously. Print the counter value using UART with a software delay between counts.

---

### 4️⃣ Dice Simulator using Port 1

**File:** Dice_Simulator_Port1

**Question:**  
Simulate a dice using an 8051 microcontroller. Display a pseudo-random number between 1-6 on Port 1 every second.

---

### 5️⃣ String Reverse using UART

**File:** String_Reverse_UART

**Question:**  
Write a program to reverse a string and print both the original and reversed strings using UART.

---

### 6️⃣ UART Simple Retargeting

**File:** UART_Simple_Retarget

**Question:**  
Write a simple UART retarget program where `putchar()` is used to send a character to UART.

---

### 7️⃣ UART Hello Transmission

**File:** UART_Hello_TX

**Question:**  
Send the string "HELLO" via UART once using `UART_Tx` function.

---

### 8️⃣ Password Check with P1 Simulation

**File:** Password_Check_with_P1_Simulation

**Question:**  
Simulate a 4-digit password input using Port 1 switches (P1.0 to P1.3). Compare it with a preset password and send "Access Granted" or "Access Denied" via UART.

---

### 9️⃣ Software Timer - Print Seconds

**File:** Software_Timer_Print_Seconds

**Question:**  
Write a software timer in 8051 that prints the elapsed time in seconds using UART. Use a delay loop to simulate time.

---

## Tools Used

- **Keil uVision IDE**
- **8051 Microcontroller (AT89C51)**

## Author
Elakkiya SR  
