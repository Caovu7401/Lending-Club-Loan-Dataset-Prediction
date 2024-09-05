# Lending-Clubs-Prediction
 The "Lending Clubs Loan" dataset analysis focuses on understanding loan performance, borrower characteristics, and risk factors. It helps identify patterns in defaults, repayments, and assess overall loan quality.

# GIẢI THÍCH DỮ LIỆU:

1.(OUTPUT)-loan_status: Tình trạng hiện tại của khoản vay: Fully Paid (đã thanh toán) và Charged Off (không thể trả).

2.loan_amnt: Số tiền vay.

3.emp_length: Thời gian làm việc của người vay (theo năm).

4.home_ownership: Tình trạng sở hữu nhà của người vay

5.annual_inc: Thu nhập hàng năm của người vay.

6.issue_d: Ngày phát hành khoản vay.

7.purpose: Mục đích của khoản vay

8.zip_code: Mã vùng bưu điện của người vay.

9.addr_state: Bang nơi người vay sinh sống.

10.dti: Tỷ lệ nợ trên thu nhập của người vay.

11.delinq_2yrs: Số lần trễ hạn thanh toán trong 2 năm qua.

12.earliest_cr_line: Ngày mở tài khoản tín dụng đầu tiên của người vay.

13.fico_range_low: Điểm FICO thấp nhất của người vay.

14.fico_range_high: Điểm FICO cao nhất của người vay.

15.inq_last_6mths: Số lần tra cứu tín dụng trong 6 tháng qua.

16.mths_since_last_delinq: Số tháng kể từ lần trễ hạn thanh toán cuối cùng.

17.mths_since_last_record: Số tháng kể từ lần ghi nhận vi phạm tín dụng cuối cùng.

18.open_acc: Số lượng tài khoản tín dụng đang mở của người vay.

19.pub_rec: Số lần ghi nhận vi phạm công khai.

20.revol_bal: Số dư quay vòng (revolving balance) của người vay.

21.revol_util: Tỷ lệ sử dụng tín dụng quay vòng (revolving credit utilization).

22.total_acc: Tổng số tài khoản tín dụng của người vay.

23.initial_list_status: Trạng thái danh sách ban đầu của khoản vay.

24.mths_since_last_major_derog: Số tháng kể từ lần ghi nhận vi phạm nghiêm trọng cuối cùng.

25.tot_coll_amt: Tổng số tiền trong các khoản thu hồi.

26.tot_cur_bal: Tổng số dư hiện tại của người vay.

27.total_rev_hi_lim: Giới hạn tín dụng cao nhất quay vòng.

28.acc_open_past_24mths: Số lượng tài khoản mở trong 24 tháng qua.

29.avg_cur_bal: Số dư trung bình hiện tại.

30.bc_open_to_buy: Hạn mức tín dụng có sẵn trên thẻ tín dụng quay vòng.

31.bc_util: Tỷ lệ sử dụng tín dụng quay vòng trên thẻ tín dụng.

32.mo_sin_old_il_acct: Số tháng kể từ khi mở tài khoản tín dụng lâu đời nhất.

33.mo_sin_old_rev_tl_op: Số tháng kể từ khi mở tài khoản tín dụng quay vòng lâu đời nhất.

34.mo_sin_rcnt_rev_tl_op: Số tháng kể từ khi mở tài khoản tín dụng quay vòng gần nhất.

35.mo_sin_rcnt_tl: Số tháng kể từ khi mở tài khoản tín dụng gần nhất.

36.mort_acc: Số lượng tài khoản thế chấp.

37.mths_since_recent_bc: Số tháng kể từ khi mở tài khoản tín dụng quay vòng gần nhất.

38.mths_since_recent_bc_dlq: Số tháng kể từ khi trễ hạn thanh toán trên tài khoản tín dụng quay vòng gần nhất.

39.mths_since_recent_inq: Số tháng kể từ lần tra cứu tín dụng gần nhất.

40.mths_since_recent_revol_delinq: Số tháng kể từ khi trễ hạn thanh toán trên tài khoản tín dụng quay vòng gần nhất.

41.num_accts_ever_120_pd: Số lượng tài khoản đã từng trễ hạn thanh toán 120 ngày hoặc hơn.

42.num_actv_bc_tl: Số lượng tài khoản thẻ tín dụng đang hoạt động.

43.num_actv_rev_tl: Số lượng tài khoản tín dụng quay vòng đang hoạt động.

44.num_bc_sats: Số lượng tài khoản thẻ tín dụng đã thanh toán đủ.

45.num_bc_tl: Số lượng tài khoản thẻ tín dụng.

46.num_il_tl: Số lượng tài khoản tín dụng cài đặt.

47.num_op_rev_tl: Số lượng tài khoản tín dụng quay vòng đang mở.

48.num_rev_accts: Số lượng tài khoản tín dụng quay vòng.

49.num_rev_tl_bal_gt_0: Số lượng tài khoản tín dụng quay vòng có số dư lớn hơn 0.

50.num_sats: Số lượng tài khoản đã thanh toán đủ.

51.num_tl_120dpd_2m: Số lượng tài khoản trễ hạn thanh toán 120 ngày hoặc hơn trong 2 tháng qua.

52.num_tl_30dpd: Số lượng tài khoản trễ hạn thanh toán 30 ngày.

53.num_tl_90g_dpd_24m: Số lượng tài khoản trễ hạn thanh toán 90 ngày trong 24 tháng qua.

54.num_tl_op_past_12m: Số lượng tài khoản mở trong 12 tháng qua.

55.pct_tl_nvr_dlq: Tỷ lệ phần trăm tài khoản chưa từng trễ hạn thanh toán.

56.percent_bc_gt_75: Tỷ lệ phần trăm tài khoản thẻ tín dụng có mức sử dụng trên 75%.

57.pub_rec_bankruptcies: Số lần ghi nhận phá sản công khai.

58.tot_hi_cred_lim: Giới hạn tín dụng cao nhất.

59.total_bal_ex_mort: Tổng số dư ngoại trừ tài khoản thế chấp.

60.total_bc_limit: Tổng hạn mức tín dụng thẻ tín dụng.

61.total_il_high_credit_limit: Giới hạn tín dụng cao nhất cho tài khoản tín dụng cài đặt.

62.profit: Lợi nhuận từ khoản vay.
