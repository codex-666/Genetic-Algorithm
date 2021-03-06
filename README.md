# THUẬT TOÁN DI TRUYỀN (Genetic Algorithm)

## 1. Introduction - Thuật toán di truyền là gì ?
  
Vào năm 1859, **Darwin** làm rúng động không chỉ nền y học mà là toàn thế giới khi công bố _thuyết tiến hóa_ thông qua quyển sách để đời của ông -*"On the Origin of Species"*. Thuyết tiến hóa của **Darwin** vừa gây tranh cãi, vừa truyền cảm hứng cho nhiều nhà khoa học trên các lĩnh vực khác nhau. Vào những năm 60 của thế kỉ 20, một nhà khoa học tên **Rechenberg** đưa ra ý tưởng đầu tiên về [evolutionary computating](https://en.wikipedia.org/wiki/Evolutionary_computation). Vào năm 1975, **John Holland** tiếp nối ý tưởng của **Rechenberg** và giới thiệu [_Thuật toán di truyền_](https://en.wikipedia.org/wiki/Genetic_algorithm) qua quyển sách _'Adaption in Natural and Artificial System'_.

![To change or TO DIE](https://tulip4attoo.github.io/assets/img/chrome-trex/es_bear.jpeg)
  
Về bản chất, _Thuật toán di truyền_ (từ bây giờ mình sẽ gọi tắt là GA) là một thuật toán tối ưu xấp xỉ (bạn có thế liên tưởng nó có chức năng tương tự như _Gradient Descent_) nhằm tìm ra cực trị của _hàm mục tiêu_ thông qua xấp xỉ và thử sai. Ý tưởng của GA rất độc đáo nhưng gần gũi và dễ nắm bắt. GA dựa trên cấu tạo sinh học của các sinh vật trên trái đất. Bây giờ chúng ta hãy hình dung tất cả mọi sinh vật trên trái đất như những thực thể đơn bào, trong nhân mỗi tế bào sẽ chứa một **nhiễm sắc thể** **(chromosome)**. **Nhiễm sắc thể** này sẽ mang các **gen (gene)**, các gene này không gì các chính là các _thông số cần tối ưu hóa_ của chúng ta.

Đầu tiên, chúng ta sẽ tạo ra một quần thể gồm n nhiễm sắc thể với n là một số tự chọn, n càng cao thì thời gian tính toán sẽ càng lâu nhưng nếu n quá ít thì thuật toán sẽ khó hội tụ. Mỗi nhiễm sắc thể sẽ mang theo m gen, m chính là số biến trong hàm mục tiêu của chúng ta. Thông thường, giá trị của những gen trong thế hệ đầu thường sẽ mang giá trị ngẫu nhiên. Sau khi tạo ra quần thể ban đầu, chúng ta sẽ đánh giá __khả năng thích nghi (fitness)__ của từng cá thể (chromosome). Sau khi đánh giá fitness của các chromosome, chúng ta sẽ tiến hành lựa chọn các __cha mẹ (parents)__ để __lai tạo (crossover)__, thông thường những chromosome có fitness cao sẽ có khả năng (probality) được lai tạo với nhau nhiều hơn. Trong quá trình crossover thì genes của parent sẽ qua một ánh xạ nào đó để trở thành genes của đời con (child). Ngoài crossover, từ lứa đầu ta có thể tạo ra lứa chromosome sau bằng cách gây __đột biến (mutation)__ tức là thay đổi genes của một chromosome nào đó 1 cách ngẫu nhiên, thông thường những chromosomes có fitness thấp sẽ có khả năng bị đột biến nhiều hơn. 

## 2. Workflow - Vậy thì lập trình như thế nào ?
## 3. Application - Dùng GA để tìm các hệ số cho bộ điều khiển PID 
## 4. Recommendation - Một số bài viết hay về GA
