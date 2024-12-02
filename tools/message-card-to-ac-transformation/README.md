## Tóm tắt

Mẫu này hướng dẫn cách sử dụng `actemplate.json` để chuyển đổi hợp lý các Thẻ Tin nhắn Cũ (Legacy Message Cards) thành Thẻ Thích ứng (Adaptive Cards).  
> ### **Lưu ý**  
Công cụ này chưa sẵn sàng cho sản xuất và thực hiện chuyển đổi một cách cố gắng tối đa. Hãy sử dụng nó cẩn thận và kiểm tra kỹ lưỡng việc hiển thị thẻ trước khi triển khai vào Bots hoặc Quy trình công việc (Workflows). Ngoài ra, cần lưu ý rằng các Hành động HTTP POST không được hỗ trợ.  
Hãy thực hiện các bước thận trọng và xem xét các hạn chế đã được đề cập ở trên khi sử dụng công cụ này.

## Hướng dẫn cài đặt

 - Mẫu này nhắm đến Runtime .NET 8.0.
 - Vui lòng cài đặt SDK từ liên kết chính thức: https://dotnet.microsoft.com/en-us/download/dotnet/8.0
 - Mở tệp `msgcard-actest.csproj` bằng Visual Studio hoặc Visual Studio Code.
 - Chỉnh sửa tệp msgcard.json và cập nhật nó với dữ liệu tải (payload) tuân theo định dạng Thẻ Tin nhắn.
 - Chạy lệnh `dotnet run` và bạn sẽ thấy Thẻ Thích ứng (AC) đã được chuyển đổi từ `msgcard.json` trong bảng điều khiển.
 - Sao chép kết quả và xem trước trong trình thiết kế Thẻ Thích ứng tại https://adaptivecards.io/designer/ hoặc sử dụng tiện ích mở rộng Adaptive Card Previewer trong VS Code.

## Mẫu chạy thử
![image](assets/run-command.png)

![image](assets/adaptive-card.png)

<img src="https://pnptelemetry.azurewebsites.net/microsoft-teams-samples/tools/message-card-to-ac-transformation" />
