# Khái niệm cơ học lượng tử cơ bản

## Kiến trúc
```
+-----------------------------+
|     Classical Control Unit  |
+-------------+--------------+
              |
              v
+-------------+--------------+
|      Quantum Processing Unit (QPU)     |
|  - Qubit Register (Physical Qubits)    |
|  - Quantum Gates (Hadamard, CNOT...)  |
|  - Quantum Circuit Layer              |
+----------------+----------------------+
              |
              v
+-------------+--------------+
|    Quantum Measurement Unit         |
+------------------------------------+
              |
              v
+------------------------------------+
|   Classical Post-Processing (CPU)  |
+------------------------------------+
```

### So sánh Classical Computer vs Quantum

| Thành phần           | PC truyền thống       | Máy tính lượng tử                                                   |
| -------------------- | --------------------- | ------------------------------------------------------------------- |
| **Bộ xử lý**         | CPU, GPU              | QPU (Quantum Processing Unit)                                       |
| **Đơn vị dữ liệu**   | Bit (0 hoặc 1)        | Qubit (chồng chập 0 và 1)                                           |
| **Bộ nhớ**           | RAM/Cache             | Trạng thái lượng tử được giữ trong qubit (rất nhạy, dễ decoherence) |
| **Tác vụ logic**     | Cổng logic AND/OR/NOT | Cổng lượng tử: Hadamard, Pauli-X, CNOT,...                          |
| **Đo lường**         | Xem trực tiếp dữ liệu | Phép đo sẽ “làm sập” trạng thái lượng tử thành kết quả cụ thể       |
| **Kiểm soát**        | Tín hiệu điện         | Điều khiển bằng xung vi sóng, laser, hoặc điện từ                   |
| **Hệ thống làm mát** | Quạt tản nhiệt, nước  | Làm lạnh siêu dẫn (≈ 15 millikelvin)                                |


### 🔩 Thành phần chính trong QPU
| Thành phần              | Vai trò                                    |
| ----------------------- | ------------------------------------------ |
| **Physical Qubits**     | Lưu trạng thái lượng tử                    |
| **Quantum Gate Array**  | Áp dụng cổng lượng tử để xử lý dữ liệu     |
| **Measurement Circuit** | Đo trạng thái qubit sau tính toán          |
| **Control Electronics** | Gửi xung điều khiển chính xác đến qubit    |
| **Cryostat**            | Giữ nhiệt độ siêu thấp để ngăn decoherence |


### 📝 Ghi chú
- Máy tính lượng tử không thể thay thế máy tính cổ điển trong mọi tác vụ
- Chỉ phù hợp với các bài toán như: tối ưu hóa tổ hợp, mô phỏng lượng tử, giải mã hóa học lượng tử, machine learning,...
- Phần lớn máy tính lượng tử ngày nay vẫn yêu cầu máy tính cổ điển đi kèm để kiểm soát và xử lý hậu đo lường.

## Danh mục nội dung Quantum Computing

Từ tài liệu *Quantum Computing for the Very Curious* của Michael Nielsen và Andy Matuschak, một khóa học tương tác nổi bật về máy tính lượng tử, đặc biệt phù hợp với người đã có nền tảng AI/ML.

### **Phần I: Trạng thái của Qubit**

* Khái niệm cơ bản về bit và qubit
* Biểu diễn trạng thái qubit bằng vector trong không gian Hilbert
* Chồng chập (superposition) và rối lượng tử (entanglement)
* Biên độ xác suất và điều kiện chuẩn hóa
* Hình cầu Bloch và trực quan hóa trạng thái qubit

### **Phần II: Giới thiệu về cổng logic lượng tử**

* Cổng lượng tử cơ bản: Hadamard (H), Pauli-X, Pauli-Z, CNOT
* Tác động của các cổng lên trạng thái qubit
* Mạch lượng tử và cách xây dựng([quantum.country][1], [researchgate.net][2])

### **Phần III: Đo lường trong máy tính lượng tử**

* Quá trình đo lường và sự sụp đổ của trạng thái lượng tử
* Xác suất kết quả đo và ảnh hưởng đến trạng thái qubit
* Đo lường trong cơ sở tính toán (computational basis)([quantum.country][1])

### **Phần IV: Thuật toán lượng tử cơ bản**

* Thuật toán Grover: tìm kiếm trong danh sách không có thứ tự
* Thuật toán Deutsch-Jozsa: phân biệt hàm hằng và hàm cân bằng
* Dịch chuyển lượng tử (quantum teleportation)

### **Phần V: Ứng dụng và triển vọng**

* Ứng dụng của máy tính lượng tử trong mô phỏng hóa học, tối ưu hóa, và học máy
* Thách thức kỹ thuật và triển vọng phát triển

[1]: https://quantum.country/qcvc?utm_source=chatgpt.com "Quantum computing for the very curious"
[2]: https://www.researchgate.net/publication/350301441_Quantum_Computing_for_the_Quantum_Curious?utm_source=chatgpt.com "(PDF) Quantum Computing for the Quantum Curious - ResearchGate"

