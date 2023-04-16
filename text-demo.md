test
1. khi có 1 dự án của team sẵn
    - b1: tạo 1 github repository(folder) - nơi chứa code
    - b2: clone project này về mày (clone file về máy)
        git clone link-hithub
    - b3: viết code
    - b4: đẩy code
        + kiểm tra trạng thái file
            git status
        + thêm file
            git add .
        + Tạo nội dung commit
            git commit -m "your-message"
        + đấy code lên github
            git push origin main
2. Dự án của chính mình
    - b1: Tạo 1 github repository(folder) - nơi chứa code
    - b2: đẩy code lên
        + khởi tạo
            git init
        + kiểm tra trạng thái
            git status
        + thêm file
            git add .
        + kiểm tra file đã ad chưa
            git status
        + Tạo nội dụng commit
            git commit -m "đẩy code nè"
        + Đẩy code lên github
            git remote add origin `link`
            git push origin master
