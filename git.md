# 1> clone repository
    "git clone url-repository" -> git clone https://github.com/Trungdeptraii/tittok.git
# 2> set config (user.name, user.email)
    'git config --global user.name  "stringName" '
   ' git config --global user.email "stringEmail"'

    check git config user.name | user.email
# 3> Commit
    "git add fiename" (thêm file vào repository)
    "git status" - kiểm tra trạng thái đã ok chưa
    'git commit -m "ghi chú"'
# 4> push 
    "git push origin branch" -> git push origin mail
# 5> pull
    "git pull" - lấy dữ liệu về vscode khi thay đổi code trên github
# 6> Branching
    "git branch"  - Trả về các nhánh của repository
   " git checkout -b newbranch" - thoát khỏi branch hiện tại, và chuyển sang newBranch
    "git push -u origin branch" - giống "git push origin branch" nhưng khác ở đây là chức năng
        >> -u = --ser-upsteam sau khi thiết lập upstream các lần đẩy code sau thì chỉ cần sử dụng lệnh
        "git push" và không cần nhập "origin" và "branch"