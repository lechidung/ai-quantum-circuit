# ai-quantum-circuit

## Plan
| Tuần       | Mục tiêu                             | Nội dung học                                                                                                        | Tài nguyên                                                                            | 
| ---------- | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Tuần 1** | Nắm khái niệm cơ học lượng tử cơ bản | - Qubit là gì? Superposition, Entanglement<br>- Đo lường & xác suất<br>- Trạng thái quantum (ket notation,          | ψ⟩) <br>- [Quantum Country](https://quantum.country/qcvc)<br>- YouTube: "Quantum Computing for Beginners" – Qiskit |
| **Tuần 2** | Hiểu & viết Quantum Circuit          | - Cổng lượng tử cơ bản: Hadamard, X, Z, CNOT<br>- Quantum Circuit, trạng thái sau mỗi cổng<br>- IBM Qiskit Basics   | - [Qiskit Textbook: Chapter 1–2](https://qiskit.org/learn)<br>- Google Colab + Qiskit |
| **Tuần 3** | Làm quen với thuật toán lượng tử     | - Thuật toán Grover (tìm kiếm)<br>- Thuật toán Deutsch-Jozsa (phân biệt hàm)<br>- Thuật toán teleportation lượng tử | - Qiskit Textbook: Algorithms<br>- IBM Q Lab                                          |
| **Tuần 4** | Dự án thực hành nhỏ                  | - Xây dựng 1 Quantum circuit mô phỏng<br>- Giao diện dùng AI điều khiển quantum circuit                             | - PennyLane Tutorial (optional)<br>- Jupyter notebook thực hành                       |


## Learn
| Chủ đề            | Cần nắm rõ gì?                                     | Ví dụ                                         |
| ----------------- | -------------------------------------------------- | --------------------------------------------- |
| **Qubit**         | Có thể ở trạng thái 0, 1 hoặc chồng chập           | \|ψ⟩ = α\|0⟩ + β\|1⟩                          |
| **Superposition** | Qubit có thể là tổ hợp nhiều trạng thái            | Sau cổng Hadamard: \|0⟩ → (1/√2)(\|0⟩ + \|1⟩) |
| **Entanglement**  | Hai qubit liên kết nhau, trạng thái phụ thuộc nhau | Bell State: (1/√2)(\|00⟩ + \|11⟩)             |
| **Gates**         | Cổng lượng tử thay đổi trạng thái                  | Hadamard, Pauli-X, CNOT                       |
| **Circuit**       | Chuỗi các gate thực hiện phép tính lượng tử        | `qc.h(0); qc.cx(0,1)` trong Qiskit            |

## Project
- Xây dựng 1 Quantum circuit mô phỏng
- Giao diện dùng AI điều khiển quantum circuit
