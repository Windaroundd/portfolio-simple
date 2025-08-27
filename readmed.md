//git command

1. Mở folder muốn đẩy lên github
2. Mở terminal
3. git init
4. git add -A
5. git commit -m "initial commit" (cho commit đầu tiên) => message tùy theo nội dung mà mình thay đổi trong code
6. Tạo repo trên github => muốn deploy vercel thì để public
7. git remote add origin ...... (link là địa chỉ của repo github)
8. git push --set-upstream origin master (chỉ làm lần đầu khi đẩy lên github) lần sau => git push
9. Kiểm tra lại github xem có file code chưa? nếu có => thành công
10. Để deploy thì xài vercel
11. Đăng nhập bằng github => new project => import repo github vừa tạo
12. Deploy => có link deploy => xong
