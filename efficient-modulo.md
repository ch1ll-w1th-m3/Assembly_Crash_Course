# Challenge
## efficient-modulo

![image](https://github.com/user-attachments/assets/9aa5426b-91e9-4249-8e28-5fce51a0959f)

Ở bài này, thay vì div như thông thường để lấy mod, thì sẽ lâu hơn. Thay vào đó, vì đề bài cho mod 2^n nên ta có thể dùng các bit thấp để lưu thay cho phép mod. 

Ví dụ, để tính rdi % 256 thì ta chỉ cần lấy 2 bits cuối của rdi, tương tự với rsi ta lấy 4 bits cuối. 

![image](https://github.com/user-attachments/assets/d103b6d5-7b77-4367-9ea0-e795afa5e5d0)

Flag: `pwn.college{k3No9M7_m4bIejLDx0AZzRXsHEM.0VO5EDLwEzN1gzW}`
