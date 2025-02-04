# ![Paw](https://github.com/Linhchi162/ImageForPacCat/blob/main/1683577958744.png?raw=true) PacCat_SDL2_Game
- Trần Linh Chi
- MSV: 22026564

### Giới thiệu 
- Nội dung Game: Một con mèo tên là Pac ![Pac](https://github.com/Linhchi162/ImageForPacCat/blob/main/Asset%201.png?raw=true) đột nhiên lạc vào mê cung và không thể tìm được lối ra. Mê cung bao gồm rất nhiều hộp đựng đồ vật đang chen lấn trên đường đi của Pac. Hãy giúp Pac đẩy các hộp đúng vị trí để tìm được lối thoát khỏi mê cung.
- PacCat là một trò chơi giải đố được phát triển bằng ngôn ngữ C++ và thư viện SDL2, lấy cảm hứng từ trò chơi Sokoban. Trong trò chơi, người chơi sẽ nhập vai vào một chú mèo tên Pac và điều khiển nó đẩy các hộp vào các ô đích để hoàn thành màn chơi. Trò chơi có độ khó tăng dần khi tiến đến các màn chơi mới và người chơi cần suy nghĩ để đưa ra các chiến lược để hoàn thành các màn chơi.

### Lý do chọn game
-Mình chọn Sokoban vì nó là trò chơi vừa đủ khó để mình phải vắt óc suy nghĩ, nhưng không quá khó để mình phải bỏ cuộc, đơn giản nhưng hấp dẫn. Nó giúp cho mình học cách sử dụng C++ và SDL2 để xử lý các khía cạnh cơ bản của một trò chơi như vòng lặp chính, xử lý sự kiện, hiển thị đồ họa và di chuyển các đối tượng.

### Cách chạy chương trình
- Tải file zip về và giải nén
- mở PacCat!.exe

### Hướng dẫn chơi 
1. Sử dụng các phím mũi tên lên, xuống, trái, phải để di chuyển chú mèo.
2. Đẩy các hộp vào ô đích  để hoàn thành màn chơi và tiến đến màn tiếp theo.
3. Tránh đẩy hai hộp dính liền với nhau hoặc đẩy hộp vào một góc.
4. Game có tổng cộng 10 màn chơi, mỗi màn chơi kéo dài 5 phút, nếu chưa hoàn thành màn chơi trong vòng 5 phút thì người chơi sẽ thua và phải chơi lại từ đầu.
5. Kết thúc cả 10 màn chơi thì Pac sẽ được giải thoát khỏi mê cung.
### Preview

![](https://github.com/Linhchi162/ImageForPacCat/blob/main/Preview2.gif?raw=true)

### Các chức năng 
-Trong màn hình menu bao gồm :
+ Button để bắt đầu trò chơi.
+ Button để bật tắt âm thanh.
+ Button để vào màn hình chọn level.
+ Button để xem hướng dẫn chơi game.

-Trong màn hình game bao gồm :
+ Một bộ đếm thời gian
+ Button để đặt lại vị trí các hộp và vị trí người chơi.
+ Button để tạm dừng level, hiện màn hình menu.
+ Button để làm cho các hộp biến mất, để có thể dễ dàng quan sát màn chơi hơn.


### Các hướng phát triển về sau 
1. Cải thiện đồ họa của trò chơi.
2. Thêm nhiều màn chơi và thử thách hơn.
3. Tạo thêm chế độ 2 người chơi.
4. Thêm tính năng lưu lại tiến trình của người chơi mỗi khi tắt game.

### Tài liệu tham khảo
- Lazyfoo.
- youtuber LepleyDev.

### Source
- Âm thanh được lấy từ mixkit.
- Hình ảnh tự design, riêng hình ảnh khi hoàn thành hết tất cả các level được lấy từ [Pinterest](https://www.pinterest.com/pin/19351473391917464/)
- Font được lấy từ Dafont.
- Các level được tạo ra dựa trên Sokoban Online
