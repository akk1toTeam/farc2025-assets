1. PartyRock - BMI Buddy_How to create an AI app.txt
BMI Buddy APP
https://partyrock.aws/u/hoangnt/J6mT9Q1gx/BMI-Buddy
https://partyrock.aws/u/hoangnt/J6mT9Q1gx/BMI-Buddy/snapshot/ke5JpNyLH
https://emojipedia.org/

1. STATIC TEXT: APP INTRODUCTION - GIỚI THIỆU CHUNG VỀ APP 
# Trà sữa mlem mlem và chỉ số BMI! 🧋 
### Hãy nhập chiều cao và cân nặng của bạn để biết chỉ số BMI và nhận những lời khuyên về sức khỏe. Ứng dụng sẽ phân tích và đưa ra lời khuyên phù hợp cho bạn.

2. INPUT: CÁC THAM SỐ, THÔNG SỐ, BIẾN DÙNG CHO TÍNH TOÁN

3. PROMPT GEN TEXT: XỬ LÝ VÀ TÍNH TOÁN TRÊN THAM SỐ, LOGIC, MẠCH CHẠY CỦA APP
Hãy tính chỉ số BMI dựa trên chiều cao [Chiều cao] cm và cân nặng [Cân nặng] kg. Sau đó phân tích và đưa ra nhận xét chi tiết bằng tiếng Việt về chỉ số BMI này, bao gồm: 1) Công thức tính 2) Kết quả BMI 3) Phân loại (gầy, bình thường, thừa cân, béo phì) 4) Nguy cơ sức khỏe liên quan

4. PROMPT GEN ẢNH: XỬ LÝ VÀ TÍNH TOÁN TRÊN THAM SỐ, LOGIC, MẠCH CHẠY CỦA APP, KẾT NỐI VỚI CÁC PROMPT KHÁC
Tạo một hình ảnh vui nhộn, phong cách hoạt hình về một người có chỉ số BMI tương ứng với kết quả [Kết quả BMI 🥛]. Nếu BMI cao thì vẽ người mập, nếu thấp thì vẽ người gầy, nếu bình thường thì vẽ người cân đối

5. PROMPT GEN TEXT: XỬ LÝ VÀ TÍNH TOÁN TRÊN THAM SỐ, LOGIC, MẠCH CHẠY CỦA APP, KẾT NỐI VỚI CÁC PROMPT KHÁC
Dựa vào chỉ số BMI từ [Kết quả BMI 🥛], hãy đưa ra lời khuyên chi tiết bằng tiếng Việt về: 1) Chế độ ăn uống phù hợp 2) Các loại thực phẩm nên ăn và nên tránh 3) Thời gian ăn uống hợp lý 4) Lượng calories phù hợp mỗi ngày


6. PROMPT CHAT: XỬ LÝ VÀ TÍNH TOÁN TRÊN THAM SỐ, LOGIC, MẠCH CHẠY CỦA APP, KẾT NỐI VỚI CÁC PROMPT KHÁC
* Prompt: Đây là thông tin BMI của tôi: [Kết quả BMI 🥛]. Hãy tư vấn cho tôi về dinh dưỡng và sức khỏe.
* Place Holder: Hãy hỏi bất kỳ câu hỏi về dinh dưỡng và sức khỏe
* Initial Message: Xin chào! Tôi là trợ lý dinh dưỡng. Dựa trên chỉ số BMI của bạn, tôi sẽ giúp bạn có được lời khuyên phù hợp nhất về chế độ ăn uống và lối sống lành mạnh. Bạn có thể hỏi tôi bất kỳ câu hỏi nào về dinh dưỡng!
