- **Binary digits are a foundational segment of [[subnetting]]**
- Binary refers to a language that only uses 0s or 1s.
- A *bit* is a **single digit**, either 0 or 1.
- A *byte* refers to **eight bits**. They are also called "octets".

Using exponents of two, we can follow a simple chart to translate between binary and decimal.

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   |

## Case 1: Binary to decimal
If we wanted to find out what the numbers **00000010 and 00100010**  would be in decimal, we can just do these steps:

### Step 1: Replace the numbers in the lower row.
**Number = 00000010**

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 0   | 0   | 1   | 0   |
| 0   | 0   | 1   | 0   | 0   | 0   | 1   | 0   |
### Step 2: Add the multiplication of both rows.
(128 * 0) +( 64 * 0) + (32 * 0) + (16 * 0) + (8 * 0) + (4 * 0) + (2 * 1) + (1 * 0) = 2
(128 * 0) +( 64 * 0) + (32 * 1) + (16 * 0) + (8 * 0) + (4 * 0) + (2 * 1) + (1 * 0) = 34

The numbers are 2 and 34

# Case 2: Decimal to binary
The equation is equally simple to perform by following a few steps. Let's say that we want to know the binary of the number 182

## Keep dividing full numbers with the one closest in the table

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
187 - 128 = 59

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 0   | 0   | 0   | 0   | 0   | 0   | 0   |
59 - 32 = 27

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 0   | 1   | 0   | 0   | 0   | 0   | 0   |
27 - 16 = 11

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 0   | 1   | 1   | 0   | 0   | 0   | 0   |
11-8 = 3

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 0   | 1   | 1   | 1   | 0   | 0   | 0   |
3-2 = 1

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 0   | 1   | 1   | 1   | 0   | 1   | 0   |
1-1=0

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 0   | 1   | 1   | 1   | 0   | 1   | 1   |

So the final result is **10111011**

---
[[SUBNETTING]]
