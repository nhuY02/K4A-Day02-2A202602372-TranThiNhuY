# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trần Thị Như Ý 
- Mã học viên: 2A202602372
- Nhóm: D02
- Candidate problem nhóm chọn: Trông trẻ em nằm nôi

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan các pain point từ công việc hằng tuần và xác định 3 problem chính: tìm/so sánh framework, lên cấu trúc architecture/module và review code cho nhóm. | Cung cấp 3 candidate thuộc nhóm problem kỹ thuật để đưa vào quá trình convergence. |
| Pitch Problem Card | Trình bày 3 problem và giải thích bottleneck, thời gian và impact của từng problem. | Giúp nhóm có thêm các candidate kỹ thuật để so sánh với các problem thuộc domain khác. |
| Challenge bài của bạn khác | Gợi ý cơ chế lọc mail spam của Trường và build một box tương tự box Kute trong Discord của khóa học với problem search/tìm tài liệu/hỏi đáp ở công ty của Tùng. | Đưa ra các solution tham khảo từ những hệ thống đã quen thuộc với người dùng, giúp challenge xem problem có thể giải quyết bằng cơ chế đơn giản/workflow có sẵn hay không, thay vì mặc định cần một Agent phức tạp. |
| Gom trùng / cluster | Gom các candidate có nội dung hoặc bottleneck tương tự, đặc biệt các candidate liên quan đến lập trình, phát triển phần mềm và xử lý thông tin kỹ thuật. | Hình thành Cluster B — Lập trình & Phát triển PM, giúp nhóm giảm các ý trùng và dễ so sánh các nhóm problem. |
| Chọn candidate problem | Tham gia so sánh các candidate dựa trên actor, workflow, bottleneck, impact và khả năng giải quyết bằng AI/Workflow/Rule. | Nhóm shortlist các candidate và cuối cùng thống nhất chọn problem “Trông trẻ em nằm nôi” làm problem chung. |
| Validation / research | Tham gia xem xét các evidence, pain point và cách problem được kiểm chứng; đối chiếu xem problem có đủ cơ sở để tiếp tục hay không. | Giúp nhóm củng cố phần validation trước khi chuyển sang xây dựng Problem Statement. |
| Workflow nhóm | Góp ý cách tách Current State và Future State, xác định bottleneck và điểm AI có thể can thiệp nhưng vẫn giữ human boundary. | Giúp workflow thể hiện rõ các bước xử lý, điểm can thiệp của AI và phần con người vẫn phải kiểm soát. |
| Problem Statement | Tham gia củng cố nội dung Problem Statement, kiểm tra sự nhất quán giữa problem, actor, workflow, bottleneck, impact và metric. | Giúp Problem Statement của nhóm rõ hơn về pain cần giải quyết và cách đo hiệu quả. |
| Rule / Workflow / Agent | Tham gia phân tích xem problem cần Rule, Workflow hay Agent; chú ý đến mức độ phức tạp thực sự của workflow và nhu cầu tự lập kế hoạch/gọi tool. | Góp phần giúp nhóm không mặc định sử dụng Agent khi Workflow đã đủ đáp ứng bài toán. |
| Decision | Tham gia phản biện trước quyết định Go/No-Go và xem xét các rủi ro khi áp dụng AI, đặc biệt khả năng AI đưa ra kết quả sai hoặc bỏ sót. | Nhóm thống nhất hướng Go với pilot offline và xác định các metric/risk cần tiếp tục kiểm chứng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Gom và cluster các candidate problem, góp ý củng cố sự nhất quán giữa problem, workflow, bottleneck và metric, óng góp vào quá trình challenge bằng cách liên hệ các problem của thành viên khác với những cơ chế thực tế như lọc mail spam của Trường và box Kute trong Discord để xem có thể giải quyết bằng Rule/Workflow đơn giản hay không.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Brainstorm thêm các problem từ công việc hằng tuần và phân loại theo các lăng kính Lặp lại, Tốn thời gian, AI có thể tốt hơn và Pain từ người khác.| Giúp mở rộng nhanh số lượng candidate và gợi ý những pain point tôi có thể chưa nghĩ tới.| Một số ý AI đưa ra quá chung chung như muốn quản lý thời gian tốt hơn chưa có actor, workflow và evidence cụ thể.| Tôi loại các ý không chứng minh được pain thật và giữ lại các problem có workflow, actor và số liệu có thể quan sát/đo lường.|
| Problem Card | Phản biện cách viết problem, xác định actor, bottleneck, impact và success metric.| phát hiện những chỗ problem còn rộng hoặc bottleneck chưa được mô tả rõ. | AI đôi khi đi quá nhanh sang giải pháp, dễ biến problem thành “cần một AI tool” thay vì tập trung vào pain hiện tại.| Tôi quay lại mô tả current workflow trước, xác định bottleneck và chỉ sau đó mới đặt AI hypothesis.|
| Workflow | Hỗ trợ chuyển problem thành Current State/Future State và xác định human boundary, fallback.| Giúp nhìn workflow thành các bước cụ thể và dễ nhận ra vị trí AI có thể can thiệp.| Một số thời gian ở từng bước là ước lượng do AI đề xuất, không phải evidence tôi đã đo thực tế.| Tôi giữ các số liệu đã có trong report; những số chưa đo được chỉ xem là giả định để kiểm chứng ở phase sau, không coi là evidence thật.|
| Research | Không dùng AI để thay thế việc kiểm chứng nguồn; chỉ dùng AI khi cần gợi ý hướng tìm hiểu hoặc từ khóa.| Có thể giúp định hướng nhanh các loại solution hoặc công nghệ liên quan cần tìm.| AI có thể đưa ra thông tin hoặc số liệu chưa được kiểm chứng.| Tôi không sử dụng thông tin do AI đưa ra như evidence nếu chưa kiểm tra lại nguồn.|
| Problem Statement | Rà soát sự nhất quán giữa Problem, Actor, Workflow, Bottleneck, Impact, Metric và Boundary.| Như một lớp phản biện để phát hiện field còn thiếu hoặc câu mô tả chưa rõ.| AI có thể viết câu chữ rất hợp lý nhưng không nhất thiết phản ánh đúng evidence thực tế của nhóm.| Tôi đối chiếu lại nội dung với workflow và evidence của nhóm rồi mới giữ hoặc sửa câu trả lời.|
| Rule / Workflow / Agent | Hỗ trợ so sánh ba mức Rule, Workflow và Agent, đặc biệt về mức độ phức tạp của workflow.| Giúp làm rõ khi nào một bài toán cần khả năng tự lập kế hoạch/gọi tool của Agent và khi nào Workflow đã đủ.| AI dễ tạo cảm giác Agent là phương án mạnh hơn nên đáng dùng hơn, dù chưa chắc cần thiết.| Tôi dựa vào workflow thực tế để đánh giá; với bài toán của nhóm, Workflow phù hợp hơn vì luồng tương đối tuyến tính và không cần Agent tự lập kế hoạch phức tạp.|
| Decision | Challenge các rủi ro và điểm yếu của phương án, đặc biệt khả năng AI sai hoặc bỏ sót.| Giúp nhóm có thêm góc nhìn để đặt câu hỏi trước khi quyết định Go/No-Go.| AI không thể tự quyết định Go/No-Go dựa trên evidence thực tế của nhóm.| Tôi xem AI như công cụ phản biện, còn quyết định cuối cùng dựa trên validation, workflow, metric và risk mà nhóm đã thống nhất.|

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text

Ban đầu tôi khá tập trung vào technical problem vì đó là thứ mình quen. Nhưng khi nghe problem của các bạn khác cho thấy problem tốt không nhất thiết phải liên quan IT; quan trọng là pain có thật, workflow rõ và đo được. Nhóm có bị solution-first, có lúc dễ nghĩ ngay tới AI/Agent, nhưng tôi đã thử challenge bằng cách liên hệ với những cơ chế đơn giản đã quen thuộc, như bộ lọc mail spam của Trường hoặc box Kute trong Discord, để xem problem có thể được giải quyết bằng Rule hoặc Workflow trước hay không. Điều này cũng làm tôi thay đổi cách nhìn về Agent: một bài toán có AI không đồng nghĩa với việc phải dùng Agent. Sau khi nhóm chọn problem “Trông trẻ em nằm nôi”, tôi thấy Workflow phù hợp hơn vì luồng xử lý tương đối tuyến tính và chưa cần khả năng tự lập kế hoạch phức tạp của Agent. Đóng góp rõ nhất của tôi trong artifact cuối là gom và cluster các candidate problem, đặc biệt nhóm các problem kỹ thuật thành Cluster B sau đó góp phần củng cố report. Khi sử dụng AI, tôi thấy AI hữu ích trong việc brainstorm và phản biện workflow, nhưng đôi khi đưa ra các problem quá chung hoặc đi quá nhanh sang solution. Điều khó nhất với tôi là phân biệt giữa một ý tưởng nghe hợp lý và một pain thực sự có đủ evidence để đưa vào Problem Statement. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ngay từ đầu về evidence của metric và kiểm tra xem từng phần của solution có thực sự cần AI hay không.

```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [ ] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

