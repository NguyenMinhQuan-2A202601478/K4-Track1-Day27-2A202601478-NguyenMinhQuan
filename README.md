# Track 1 - Day 27 — AI Team Lab

- **Team:** Team ABC - AI Tutor
- **Thành viên (3 người):** Nguyễn Minh Quân, Vũ Đình Huy, Đào Văn Đạt
- **Tên dự án:** VLearn AI Tutor - Diagnostic Refresher
- **Link sản phẩm/demo:** [Figma Demo Prototype - Option A/B/C](https://www.figma.com/proto/sHzj89Xc3Jjm8e34Sfle2J/Lab18?node-id=0-1&t=yb5FmfSP3w6cEWo9-1)

## Thông tin team và phạm vi

| Hạng mục | Nội dung |
|---|---|
| Tên team | Team ABC - AI Tutor |
| Tên dự án | VLearn AI Tutor - Diagnostic Refresher |
| Mục tiêu 1-3 tháng | Đưa candidate tiếp theo từ trạng thái HOLD đến pilot có kiểm soát; đạt các gate critical đã chốt trước: schema/citation/in-scope sources 100%, quote và scope ≥ 96%, không có lỗi safety/adversarial; đồng thời xác minh pain với thêm người học thật. |
| Trưởng nhóm / người tổng hợp | Nguyễn Minh Quân |
| Format bài làm | PDF 4 trang trong repository |
| Prototype | [Figma design](https://www.figma.com/design/sHzj89Xc3Jjm8e34Sfle2J/Lab18?node-id=0-1&t=yb5FmfSP3w6cEWo9-1) · [Chạy demo](https://www.figma.com/proto/sHzj89Xc3Jjm8e34Sfle2J/Lab18?node-id=0-1&t=yb5FmfSP3w6cEWo9-1) |
| Eval trace | [Braintrust - Track 1 Day 21 Logs](https://www.braintrust.dev/app/Henry%20Ng/p/track1-day21-2A202601478/logs) |

## Thành viên và vai trò

| STT | Họ và tên | Mã học viên | Vai trò trong dự án | Phần việc/evidence từ lab trước |
|---:|---|---|---|---|
| 1 | **Nguyễn Minh Quân** | `2A202601478` | Trưởng nhóm · AI Product / Eval Lead | Phụ trách Option A - User-led Inline Explain; chốt scope, metric, scorecard và quyết định ship/hold. |
| 2 | **Vũ Đình Huy** | `2A202601288` | AI Engineer / Prototype | Phụ trách Option B - Collaborative Diagnosis; retrieval, routing, prompt, candidate và tracing. |
| 3 | **Đào Văn Đạt** | `2A202601302` | Data / QA / Research Ops | Phụ trách Option C - AI-led Recovery Path; golden cases, human labels, usability test và evidence log. |

## Bài nộp

- `Day27_AI-Team-Lab_TeamABC.pdf` - 4 artefact theo đúng thứ tự của Lab.

## Evidence được dùng

- Day 17: hai Interview Record dùng được (P01, P02). P01 tắc ở RRF và không giải thích được lựa chọn top-k; P02 gặp khó ở bài “phân tích hướng đi”. Hai lượt cho tín hiệu khác nhau nên chưa đủ để kết luận pain phổ biến.
- Day 18-19: ba phương án prototype A/B/C dùng chung một link Figma và được ghi nhận đã test; mỗi thành viên phụ trách một phương án.
- Day 20-21: Eval Pack 25 case; candidate v3 đạt quote nguyên văn 20/25 (80%), scope 21/25 (84%), schema/citation/in-scope sources 25/25; P95 latency 6,63 giây; cost 0,021926 USD/25 traces. Quyết định: HOLD.

## Lưu ý trung thực

- P01/P02 là mã ẩn danh của người tham gia thật, không phải persona giả.
- Điểm Team Health là self-assessment của nhóm để lập kế hoạch, không phải dữ liệu đo khách quan.
- Các stakeholder “mentor/reviewer chương trình” và “Lab Coach/TA” được ghi theo vai trò thực tế trong bối cảnh VLearn; không gán tên người khi repo không có bằng chứng.
- Tên file PDF hiện dùng nhãn `TeamABC`, thống nhất với tên team trong README.

## Pre-submission checklist

- [x] README có team, bảng thành viên, dự án, mục tiêu, owner và link demo.
- [x] Có đúng 01 file PDF bài làm, tối đa 4 trang.
- [x] PDF có Stakeholder Map, Pitch & RACI, AI Team Design, Team Health & Growth Plan.
- [ ] Đổi tên repository theo `Track1_Day27_TeamABC_VLearnAITutor` nếu giảng viên yêu cầu đúng format repository của Lab.
- [ ] Push GitHub và kiểm tra quyền truy cập công khai trước khi nộp.
