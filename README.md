# Java
coursera java trainning

huyn

Các Hello World dự án là một truyền thống lâu đời trong việc lập trình máy tính. Đây là một bài tập đơn giản giúp bạn bắt đầu khi học một cái gì đó mới. Hãy bắt đầu với GitHub!

Bạn sẽ học cách:

Tạo và sử dụng một kho lưu trữ
Bắt đầu và quản lý một chi nhánh mới
Thay đổi tệp và đẩy chúng vào GitHub như cam kết
Mở và hợp nhất một yêu cầu kéo

GitHub là gì?
GitHub là một nền tảng lưu trữ mã để kiểm soát phiên bản và cộng tác. Nó cho phép bạn và những người khác làm việc cùng nhau trên các dự án từ bất cứ đâu.

Hướng dẫn này dạy cho bạn các yếu tố cần thiết của GitHub như kho lưu trữ , chi nhánh , cam kết và Yêu cầu kéo . Bạn sẽ tạo kho lưu trữ Hello World của riêng bạn và tìm hiểu quy trình công việc Pull Request của GitHub, một cách phổ biến để tạo và xem lại mã.

Không cần mã hóa
Để hoàn thành hướng dẫn này, bạn cần có tài khoản GitHub.com và truy cập Internet. Bạn không cần biết cách viết mã, sử dụng dòng lệnh hoặc cài đặt Git (phần mềm kiểm soát phiên bản GitHub được xây dựng trên).

Mẹo: Mở hướng dẫn này trong một cửa sổ trình duyệt (hoặc tab) riêng biệt để bạn có thể nhìn thấy nó trong khi bạn hoàn thành các bước trong hướng dẫn.


Bước 1. Tạo một kho lưu trữ
Một kho lưu trữ thường được sử dụng để tổ chức một dự án duy nhất. Các kho lưu trữ có thể chứa các thư mục và tệp, hình ảnh, video, bảng tính và bộ dữ liệu - bất cứ thứ gì mà dự án của bạn cần. Chúng tôi khuyên bạn nên bao gồm README hoặc tệp có thông tin về dự án của bạn. GitHub giúp bạn dễ dàng thêm một cái cùng lúc bạn tạo kho lưu trữ mới của mình. Nó cũng cung cấp các tùy chọn phổ biến khác như tệp giấy phép.

hello-worldKho lưu trữ của bạn có thể là nơi bạn lưu trữ ý tưởng, tài nguyên hoặc thậm chí chia sẻ và thảo luận mọi thứ với người khác.

Để tạo một kho lưu trữ mới
Ở góc trên bên phải, bên cạnh hình đại diện hoặc nhận dạng của bạn, nhấp vào và sau đó chọn Kho lưu trữ mới .
Đặt tên cho kho lưu trữ của bạn hello-world.
Viết một mô tả ngắn.
Chọn Khởi tạo kho lưu trữ này với README .
hình thức mới

Nhấp vào Tạo kho lưu trữ .


Bước 2. Tạo một chi nhánh
Phân nhánh là cách để làm việc trên các phiên bản khác nhau của một kho lưu trữ cùng một lúc.

Theo mặc định, kho lưu trữ của bạn có một nhánh được đặt tên masterlà nhánh chính xác. Chúng tôi sử dụng các nhánh để thử nghiệm và thực hiện các chỉnh sửa trước khi cam kết chúng master.

Khi bạn tạo một nhánh ra khỏi masternhánh, bạn đang tạo một bản sao hoặc ảnh chụp nhanh masternhư thời điểm đó. Nếu người khác thực hiện thay đổi cho masterchi nhánh trong khi bạn đang làm việc trên chi nhánh của mình, bạn có thể cập nhật những cập nhật đó.

Sơ đồ này cho thấy:

các masterchi nhánh
Một nhánh mới được gọi feature(vì chúng tôi đang thực hiện 'tính năng công việc' trên nhánh này)
Hành trình đi featuretrước khi nó hòa vàomaster
một chi nhánh

Bạn đã bao giờ lưu các phiên bản khác nhau của một tập tin? Cái gì đó như:

story.txt
story-joe-edit.txt
story-joe-edit-reviewed.txt
Các chi nhánh hoàn thành các mục tiêu tương tự trong kho GitHub.

Tại GitHub, các nhà phát triển, nhà văn và nhà thiết kế của chúng tôi sử dụng các nhánh để giữ các sửa lỗi và tính năng hoạt động tách biệt với masternhánh (sản xuất) của chúng tôi . Khi một sự thay đổi đã sẵn sàng, họ hợp nhất chi nhánh của họ vào master.

Để tạo một chi nhánh mới
Chuyển đến kho lưu trữ mới của bạn hello-world.
Nhấp vào thả xuống ở đầu danh sách tập tin có nhánh: master .
Nhập tên chi nhánh readme-edits, vào hộp văn bản chi nhánh mới.
Chọn hộp Tạo nhánh màu xanh hoặc nhấn vào Enter Enter trên bàn phím của bạn.
chi nhánh gif

Bây giờ bạn có hai chi nhánh, mastervà readme-edits. Chúng trông giống hệt nhau, nhưng không lâu đâu! Tiếp theo chúng tôi sẽ thêm các thay đổi của chúng tôi vào chi nhánh mới.


Bước 3. Thực hiện và cam kết thay đổi
Bravo! Bây giờ, bạn đang ở chế độ xem mã cho readme-editschi nhánh của mình , đây là bản sao của master. Hãy thực hiện một số chỉnh sửa.

Trên GitHub, thay đổi lưu được gọi là cam kết . Mỗi cam kết có một thông điệp cam kết liên quan , đó là một mô tả giải thích tại sao một thay đổi cụ thể được thực hiện. Thông điệp cam kết nắm bắt lịch sử thay đổi của bạn, để những người đóng góp khác có thể hiểu những gì bạn đã làm và tại sao.

Thực hiện và cam kết thay đổi
Nhấp vào README.mdtập tin.
Nhấn vào  biểu tượng bút chì ở góc trên bên phải của chế độ xem tệp để chỉnh sửa.
Trong trình chỉnh sửa, viết một chút về bản thân bạn.
Viết một thông điệp cam kết mô tả những thay đổi của bạn.
Nhấp vào nút Cam kết thay đổi .
cam kết

Những thay đổi này sẽ được thực hiện đối với tệp README trên readme-editsnhánh của bạn , vì vậy bây giờ nhánh này chứa nội dung khác với master.


Bước 4. Mở Yêu cầu kéo
Chỉnh sửa tốt đẹp! Bây giờ bạn có các thay đổi trong một nhánh master, bạn có thể mở một yêu cầu kéo .

Pull Requests là trái tim của sự hợp tác trên GitHub. Khi bạn mở một yêu cầu kéo , bạn đang đề xuất các thay đổi của mình và yêu cầu ai đó xem xét và lấy đóng góp của bạn và hợp nhất chúng vào chi nhánh của họ. Yêu cầu kéo hiển thị khác biệt hoặc khác biệt của nội dung từ cả hai nhánh. Các thay đổi, bổ sung và phép trừ được hiển thị bằng màu xanh lá cây và đỏ.

Ngay khi bạn thực hiện một cam kết, bạn có thể mở một yêu cầu kéo và bắt đầu một cuộc thảo luận, ngay cả trước khi mã được kết thúc.

Bằng cách sử dụng hệ thống @mention của GitHub trong thông báo yêu cầu kéo của bạn, bạn có thể yêu cầu phản hồi từ những người hoặc nhóm cụ thể, cho dù họ đang ở dưới sảnh hay cách 10 múi giờ.

Bạn thậm chí có thể mở các yêu cầu kéo trong kho lưu trữ của riêng bạn và tự hợp nhất chúng. Đó là một cách tuyệt vời để tìm hiểu luồng GitHub trước khi thực hiện các dự án lớn hơn.

Mở Yêu cầu Kéo để thay đổi đối với README
Bấm vào hình ảnh cho một phiên bản lớn hơn

Bươc	Ảnh chụp màn hình
Nhấn vào  Tab Yêu cầu kéo , sau đó từ trang Yêu cầu kéo, nhấp vào nút Yêu cầu kéo mới màu xanh lục .	tab pr
Trong hộp So sánh ví dụ , chọn nhánh bạn đã tạo readme-edits, để so sánh với master(bản gốc).	chi nhánh
Xem xét các thay đổi của bạn về các khác biệt trên trang So sánh, đảm bảo chúng là những gì bạn muốn gửi.	khác
Khi bạn hài lòng rằng đây là những thay đổi bạn muốn gửi, hãy nhấp vào nút Tạo yêu cầu kéo màu xanh lá cây lớn .	tạo-kéo
Đưa ra yêu cầu kéo của bạn một tiêu đề và viết một mô tả ngắn gọn về những thay đổi của bạn.	mẫu đơn
Khi bạn hoàn thành với tin nhắn của mình, nhấp vào Tạo yêu cầu kéo !

Mẹo : Bạn có thể sử dụng biểu tượng cảm xúc và kéo và thả hình ảnh và gifs vào bình luận và Yêu cầu kéo.


Bước 5. Hợp nhất yêu cầu kéo của bạn
Trong bước cuối cùng này, đã đến lúc kết hợp các thay đổi của bạn lại với nhau - hợp nhất readme-editschi nhánh của bạn vào masterchi nhánh.

Nhấp vào nút yêu cầu kéo Hợp nhất màu xanh lá cây để hợp nhất các thay đổi thành master.
Nhấp vào Xác nhận hợp nhất .
Hãy tiếp tục và xóa chi nhánh, vì các thay đổi của nó đã được kết hợp, với nút Xóa chi nhánh trong hộp màu tím.
Hợp nhất xóa bỏ

Ăn mừng!
Bằng cách hoàn thành hướng dẫn này, bạn đã học cách tạo một dự án và thực hiện yêu cầu kéo trên GitHub!

Đây là những gì bạn đã hoàn thành trong hướng dẫn này:

Tạo một kho lưu trữ nguồn mở
Bắt đầu và quản lý một chi nhánh mới
Đã thay đổi một tệp và cam kết những thay đổi đó với GitHub
Đã mở và hợp nhất một Yêu cầu kéo
Hãy xem hồ sơ GitHub của bạn và bạn sẽ thấy các hình vuông đóng góp mới của mình !

Để tìm hiểu thêm về sức mạnh của Yêu cầu kéo, chúng tôi khuyên bạn nên đọc Hướng dẫn luồng GitHub . Bạn cũng có thể truy cập GitHub Explore và tham gia vào một dự án nguồn mở.

Mẹo : Xem các Hướng dẫn khác , Kênh YouTube và Đào tạo theo yêu cầu của chúng tôi để biết thêm về cách bắt đầu với GitHub.

Cập nhật lần cuối ngày 7 tháng 4 năm 2016
