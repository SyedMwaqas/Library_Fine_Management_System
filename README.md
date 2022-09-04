# Library Fine Management System
Your local library needs your help! Given the expected and actual return dates for a library book, create a program that calculates the fine (if any). The fee structure is as follows: 
1) If the book is returned on or before the expected return date, no fine will be charged.
2) If the book is returned after the expected return day but still within the same calendar month and year as the expected return date, fine = 15 Rupees*(the number of late days).
3) If the book is returned after the expected return month but still within the same calendar year as the expected return date, the fine = 500 Rupees*(the number of late days).
4) If the book is returned after the calendar year in which it was expected, there is a fixed fine of 10,000 rupees.
Charges are based only on the least precise measure of lateness. For example, whether a book is due January 1, 2021 or December 31, 2021, if it is returned January 1, 2022, that is a year late and the fine would be 10000 rupees. 
