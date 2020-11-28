Lệnh git:

git init					// Thêm folder vào repo
git status					// check thay đổi
git add						// thêm file lên stage
git commit -m "decs"		//commit
git log						// check thông tin commit
git show 'mã gói hàng'		// xem commit
git diff					// xem file modified chưa lên stage
git checkout -- 'filename' 	// xóa modified
git reset 'filename'		// back từ stage xuống modified
git branch					// check nhánh
git branch 'name'			// tạo nhánh
git checkout 'branchname'	//	chuyển nhánh
git merge B 				// thêm nhánh B vào nhánh A. Lưu ý phải đứng từ nhánh nào thì thêm vào nhánh đó
git branch -D 'branchname'	// xóa branch

git reset --soft 'commit-id  trước'	// back về stage
git reset --mixed 'commit-id trước'	// back về modified
git reset --hard 'commit-id trước'	// xóa luôn

git remote add origin 'link-repo'	// Kết nối folder với repo
git remote -v 						// danh sách remote