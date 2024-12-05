# Challenge
## indirect-jump

![image](https://github.com/user-attachments/assets/6fc5374c-93a3-4a4f-a4b3-4a5dff270bfb)

Ở bài này, mình so sánh rdi với 3 và xét 2 điều kiện là **rax = 4 (rdi > 3)** và **rax = rdi (rdi <= 3)**. Sau đó, **jump** tới địa chỉ trong bảng **[rsi + rax * 0x8]**. 

![image](https://github.com/user-attachments/assets/e2bd0b9e-0e60-4d7c-a64c-43014ba03b0d)

Flag: `pwn.college{UOf4a1CrnI_7IFHSaQywrXMMKYf.0lMxIDLwEzN1gzW}`
