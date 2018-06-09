# Clone (Download code xuống máy tính)
Dùng lệnh `git clone [repository url]`

# Status (Trạng thái của các files)
1. ' ' = unmodified
2. M   = modified
3. A   = added
4. D   = deleted
5. R   = renamed
6. C   = copied
7. U   = updated but unmerged


# Push (Upload code lên server)
Bước 1: Chọn những file cần upload => `git add [file 1] [file 2] ...`
Bước 2: Commit những file đã được chọn => `git commit -m "Message"`
Bước 3: Pull code trên server về => `git pull origin`
Bước 4: Xử lí xung đột nếu có
Bước 5: Upload code lên server => `git push origin`

# Pull (Update code xuống máy tính)
Bước 1: Chọn những file cần upload nếu có => `git add [file 1] [file 2] ...`
Bước 2: Commit những file đã được chọn nếu có => `git commit -m "Message"`
Bước 3: Pull code trên server về => `git pull origin`
Bước 4: Xử lí xung đột nếu có


# Resolve Conflict (Xử lí xung đột nết có)
- Current Change
- Icomming Change