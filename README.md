# THUẬT TOÁN DI TRUYỀN (Genetic Algorithm)

## 1. Giới thiệu
  
Vào năm 1859, Darwin làm rúng động không chỉ nền y học mà là toàn thế giới khi công bố _thuyết tiến hóa_ thông qua quyển sách để đời của ông -*"On the Origin of Species"*. Thuyết tiến hóa của Darwin vừa gây tranh cãi, vừa truyền cảm hứng cho nhiều nhà khoa học trên các lĩnh vực khác nhau. Vào những năm 60 của thế kỉ 20, một nhà khoa học tên **Rechenberg** đưa ra ý tưởng đầu tiên về [evolutionary computating](https://en.wikipedia.org/wiki/Evolutionary_computation). Vào năm 1975, **John Holland** tiếp nối ý tưởng của **Rechenberg** và giới thiệu [_Thuật toán di truyền_](https://en.wikipedia.org/wiki/Genetic_algorithm) qua quyển sách _'Adaption in Natural and Artificial System'_.
  
Về bản chất, _Thuật toán di truyền_ (từ bây giờ mình sẽ gọi tắt là GA) là một thuật toán tối ưu, bạn có thế liên tưởng nó có chức năng tương tự như _Gradient Descent_. Ý tưởng của GA rất độc đáo nhưng gần gũi và dễ nắm bắt. GA dựa trên cấu tạo sinh học của các sinh vật trên trái đất. Bây giờ chúng ta hãy hình dung tất cả mọi sinh vật trên trái đất như những thực thể đơn bào, trong nhân mỗi tế bào sẽ chứa một **nhiễm sắc thể** (chromosome). **Nhiễm sắc thể** này sẽ mang các **gen** (gene), các gene này không gì các chính là các _thông số cần tối ưu hóa_ của chúng ta.
