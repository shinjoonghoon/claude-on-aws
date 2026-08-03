# Workshops

## Claude Code on Amazon Bedrock
```
```

## Build Production Strands Agents with Multi-Tool Orchestration
```
```

---
---

# UK Loan Application - Sample Conversation

> Multi-agent 대출 신청 시스템의 E2E 테스트용 샘플 대화입니다.  
> 코드 블록 내 텍스트를 복사하여 테스트에 사용하세요.

---

## Step 1: 대출 신청 시작

**🤖 Assistant:**
> Hello! I'm your UK loan assistant. I can help you apply for a short-term personal loan of up to £5,000.

**👤 User:**
```
I want to apply for a loan
```

---

## Step 2: 고객 정보 입력

**🤖 Assistant:**
> Welcome! I'm delighted to help you as a new customer. Could you please provide me with your details?

**👤 User:**
```
Full Name: John Smith
Date of Birth: 15/03/1985
Address: 123 High Street, London, SW1A 1AA
Employment Status: Salaried at Tesco
Monthly Income: £2,500
Email: john.smith@example.co.uk
Phone: +447700900123
```

---

## Step 3: 정보 확인

**🤖 Assistant:**
> Are these details correct? Once you confirm, I'll proceed with creating your account.

**👤 User:**
```
Confirm
```

---

## Step 4: 규정 준수 정보

**🤖 Assistant:**
> I need two additional pieces for regulatory compliance:
> 1. National Insurance Number (format: AB123456C)
> 2. Open Banking consent token

**👤 User:**
```
NINO: JS123456A
Open Banking consent: OB-CONSENT-JOHNSMITH-2026
```

---

## Step 5: 대출 상세 정보

**🤖 Assistant:**
> Now I need your loan details:
> 1. Loan Amount (£500-£5,000)
> 2. Loan Tenure (30-90 days)
> 3. Loan Purpose
> 4. Bank Name
> 5. Account Number

**👤 User:**
```
Loan Amount: £2,000
Loan Duration: 45 days
Purpose: car repair
Bank: Barclays
Account number: 87654321
Repayment day: 15
```

---

## Step 6: Sort Code 입력

**🤖 Assistant:**
> Your loan has been APPROVED ✅  
> Please provide your Sort Code to complete disbursement.

**👤 User:**
```
Sort Code: 20-00-00
```

---

## Step 7: 대출 승인 및 지급 완료

**🤖 Assistant:**

### ✅ Loan Approval Confirmed

| Item | Value |
|------|-------|
| Loan ID | LN-912205CD |
| Amount Disbursed | £2,000.00 |
| Total Repayable | £2,720.00 |
| Repayment Term | 45 days |
| Daily Interest Rate | 0.8% |

### 💰 Disbursement Confirmation

| Item | Value |
|------|-------|
| Payment Method | Faster Payments Service (FPS) |
| Destination Bank | Barclays |
| Account Number | ****4321 |
| Sort Code | 20-00-00 |
| Expected Arrival | Within 2 hours |
| Status | ✅ Transfer initiated successfully |

### 📅 Repayment Information

| Item | Value |
|------|-------|
| Repayment Method | Direct Debit |
| Repayment Day | 15th of each month |

> Your funds should arrive in your Barclays account within the next 2 hours. 🚀
