---
title: Application for Basefund Hardship Assistance
mainfont: Open Sans
header-includes: \usepackage{digsig}
---

# 1. Personal Information

Full name

\TextField[name=fullname, width=\hsize]{}

Address

\TextField[name=address, width=\hsize]{}

City

\TextField[name=city, width=\hsize]{}

Zip code

\TextField[name=zip, width=\hsize]{}

Country

\TextField[name=country, width=\hsize]{}

Nationality

\TextField[name=nationality, width=\hsize]{}

Phone number

\TextField[name=phone, width=\hsize]{}

Email

\TextField[name=email, width=\hsize]{}

Date of birth (DD-MM-YYYY)

\TextField[name=birthdate, width=\hsize]{}

At what times are you usually available for a phone call? Specify your timezone if it doesn't match your address.

\TextField[name=phonetimes, width=\hsize,multiline=true,height=3\baselineskip]{}

\newpage

# 2. Payment

Fill in one of the following:

## US bank information

Routing number

\TextField[name=usrouting, width=\hsize]{}

Account number

\TextField[name=usaccount, width=\hsize]{}

Name of account holder

\TextField[name=usnameonbank, width=\hsize]{}

\CheckBox[name=savings]{\ \unskip}\ This is a savings account

## IBAN

IBAN

\TextField[name=iban, width=\hsize]{}

Name of account holder

\TextField[name=ibannameonbank, width=\hsize]{}

<!-- ## USDC -->

<!-- USDC is a cryptocurrency. At the time of writing, 1 USDC can be redeemed at Coinbase for $1, and it can be traded for many fiat currencies on other cryptocurrency exchanges. This is a fallback option for people who have neither an IBAN nor a US bank account. -->

<!-- USDC address (starts with 0x) -->

<!-- \TextField[name=usdc, width=\hsize]{} -->

\newpage

# 3. Hardship

What sources of income do you have? What is your monthly income?

\TextField[name=hardship, width=\hsize,multiline=true,height=6\baselineskip]{}

Describe the hardship you are experiencing. What problems do you foresee? What is your financial situation? What things or services do you need?

\TextField[name=hardship, width=\hsize,multiline=true,height=12\baselineskip]{}

How much money do you need to alleviate your hardship? If you are unsure, you may give a range. Specify a currency.

\TextField[name=moneyrequest, width=\hsize,multiline=true,height=6\baselineskip]{}

# 4. Donations

**In this section, only include donations made on or after January 1, 2022.**

What cost-effective charity did you donate most to?

\TextField[name=topcharity, width=\hsize]{}

How much did you donate to this charity?

\TextField[name=topamount, width=\hsize]{}

\newpage

As above, list the amounts you donated to other cost-effective charities. If you are unsure whether a charity is considered cost-effective by Basefund, err on the side of including it.

\TextField[name=othercharities, width=\hsize,multiline=true,height=12\baselineskip]{}

\CheckBox{\ \unskip}\ I have emailed all charities above a request for a copy of my donation receipts, cc'ing info@basefund.org

\CheckBox{\ \unskip}\ I only included donations made on or after January 1, 2022

If any donations originated from shared property (e.g. marital property, joint banking accounts), please describe which donations were shared with whom.

\TextField[name=Field1, width=\hsize,multiline=true,height=3\baselineskip]{}

# 5. Returned Funds

\CheckBox{\ \unskip}\ I understand that I am eligible to receive hardship payments worth up to 50% of my donations to cost-effective charities. I understand that when a charity returns a donation to me, I am no longer eligible for hardship payments on the returned funds. I agree to inform Basefund when charities return donations to me, and to send back hardship payments I am no longer eligible for.

# 6. Application Process

We aim to review your application within 7 days. If your application is accepted, the amount you receive will be the **lowest** of three figures:

1. The payout suggested by the hardship examiner
2. 50% of your donations to cost-effective charities in 2022 and 2023
3. 1,000 USD, or the equivalent amount in another currency

In certain cases where we are unable to pay out the full amount specified in section 3, we will suggest institutions that may be able to assist in bridging the gap. To expedite this process, we could share an outline of your application with other charitable funds.

\CheckBox{\ \unskip}\ (Optional) If I will not receive a payout or if I will receive a lower payout than I need, I give Basefund permission to share an anonymized outline of my application with other charitable funds.

If another fund expresses interest in helping out, we will put you in touch.

Finally, Basefund is currently in its trial phase. As such, we reserve the right to change the application process and the review process at any time.

\vspace*{\fill}
\noindent\begin{tabular}{ll}
\makebox[2.5in]{\hrulefill} & \TextField[name=date, width=2in, height=0.2in]{}\\
\\
Applicant's Signature & Date\\
\end{tabular}

\vspace{1in}

**Please send this form to info@basefund.org.**
