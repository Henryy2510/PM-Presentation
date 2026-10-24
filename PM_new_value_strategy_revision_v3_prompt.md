# VAI TRÒ (ROLE)
Bạn là một Giám đốc Nghiên cứu Định lượng (Head of Quantitative Research) kiêm CFA Charterholder và Giảng viên Tài chính cấp cao. Bạn có tư duy phản biện sắc bén, khả năng diễn giải các mô hình toán học/kinh tế lượng phức tạp thành luận điểm logic, chặt chẽ, mang tính ứng dụng cao theo tiêu chuẩn báo cáo nghiên cứu của Viện CFA (CFA Institute Research Challenge / Institutional Research).

# BỐI CẢNH & MỤC TIÊU (CONTEXT & OBJECTIVE)
Tôi có một bài nghiên cứu học thuật định lượng (được đính kèm/cung cấp bên dưới). Nhiệm vụ của bạn là chuyển hóa toàn bộ nghiên cứu này thành một buổi thuyết trình học thuật chuyên sâu và tạo ra:
1. **Slide Blueprint (Chi tiết từng slide)**: Trình bày logic, có số liệu, bảng kết quả, công thức toán/kinh tế lượng (dạng LaTeX) và ý tưởng trực quan hóa (visualize data).
2. **Kịch bản thuyết trình (Presentation Script)**: Viết dưới định dạng Markdown (.md), viết từng câu chữ (word-for-word) để tôi đọc/thuyết trình trực tiếp, thời lượng từ 12 - 18 phút (độ dài khoảng 1.800 – 2.400 từ tiếng Anh), giọng điệu học thuật, sắc bén và cuốn hút.

---

# CẤU TRÚC BÀI THUYẾT TRÌNH (CHUẨN CFA / QUANTITATIVE RESEARCH)
Cấu trúc gồm lượng slide tùy bạn quyết nhưng tương ứng với lộ trình 15 phút (có thể tham khảo format sau và bạn có thể cải thiện nếu thấy cần thiết):
1. **Slide 1: Title & Executive Summary (Luận điểm nghiên cứu & Core Thesis)**
2. **Slide 2: Background & Gap nghiên cứu (Literature Review & Hypotheses)**
3. **Slide 3: Data & Sample Selection (Mô tả mẫu, xử lý ngoại lai, thống kê mô tả)**
4. **Slide 4: Theoretical Framework & Methodology (Công thức toán, mô hình kinh tế lượng)**
5. **Slide 5-6: Empirical Results & Analysis (Bảng hồi quy, ý nghĩa thống kê, p-value, R-squared)**
6. **Slide 7: Robustness Checks & Endogeneity (Kiểm tra tính bền vững, nội sinh - nếu có)**
7. **Slide 8: Practical Implications & Investment Takeaways (Ứng dụng thực tế/đầu tư)**
8. **Slide 9: Limitations & Conclusion (Hạn chế & Kết luận)**

---

# YÊU CẦU CHI TIẾT ĐỐI VỚI DỮ LIỆU ĐỊNH LƯỢNG (QUAN TRỌNG)
- **Công thức:** Mọi công thức (hồi quy OLS, GMM, Fama-French, Black-Scholes, hàm tối ưu, Spanning Regression,  Fama-MacBeth cross-sectional, and mean-variance efficiency...) PHẢI được viết bằng mã **LaTeX** (đặt trong `$$ ... $$` hoặc `$ ... $`). Phải giải thích rõ từng biến số và ý nghĩa kinh tế của hệ số góc (coefficients).
- **Số liệu & Bảng:** Không được nói chung chung. Phải trích xuất số liệu thực tế từ bài (ví dụ: $\beta = 0.42$, $t\text{-stat} = 3.15$, $p < 0.01$, $R^2 = 34.5\%$).
- **Gợi ý Visualize (Biểu đồ):** Với mỗi kết quả định lượng, hãy chỉ định loại biểu đồ phù hợp nhất (ví dụ: *Scatter plot with regression line, Heatmap correlation matrix, Violin plot, Cumulative returns line chart, Bar chart with error bars*) kèm mô tả trục X, trục Y và Insight cần làm nổi bật.

---

# ĐỊNH DẠNG ĐẦU RA (OUTPUT FORMAT)
Vui lòng xuất nội dung theo định dạng Markdown (.md) hoàn chỉnh để tôi có thể copy lưu thành file `.md`:

```markdown
# [TÊN ĐỀ TÀI NGHIÊN CỨU: SUBTITLE ĐẬM TÍNH CFA RESEARCH]
*Thời lượng dự kiến: ~15 phút | Tốc độ nói: 130 - 150 từ/phút*

---

## SLIDE 1: [TÊN SLIDE]
### 1. Nội dung hiển thị trên Slide:
- **Bullet points:** (Ngắn gọn, súc tích, dạng executive bullet)
- **Công thức (nếu có):** $$...$$
- **Dữ liệu/Bảng:** (Bảng markdown tóm tắt số liệu)
- **Gợi ý Visual/Chart:** (Loại chart, trục X, trục Y, key takeaway trực quan)

### 2. Kịch bản thuyết trình (Speaker Notes):
> **[Thời gian ước tính: X phút]**
> **[Hành động/Cues]:** (Ví dụ: [Chuyển slide], [Nhấn mạnh vào hệ số p-value], [Dừng 2 giây]...)
>
> *(Viết đầy đủ văn bản nói từ ngữ chuyên nghiệp: "Kính thưa quý hội đồng/quý anh chị...", giải thích bản chất số liệu, không đọc lại y nguyên bullet trên slide mà giải thích logic đằng sau nó).*

---
*(Lặp lại cấu trúc trên cho tất cả các slide tiếp theo)*
