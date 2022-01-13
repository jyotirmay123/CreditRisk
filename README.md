# CreditRisk

How to share notebooks with Binder:
1. Go to https://mybinder.org/.
2. Paste the repo link: https://github.com/jyotirmay123/CreditRisk.git and click "launch" - this will build the notebook image, push it and make it available on JupyterHub.
3. Get the sharable link: go to File > New > Terminal, type "jupyter notebook list", get the link, replace "http://0.0.0.0:8888" with "https://hub.mybinder.org" and share with collaborator(s).
4. The session ends automatically after 10 min of inactivity.

## Credit Risk Data
| Feature Name        | Description           |
| ------------- | -------------|
| person_age     | Age |
| person_income    | Annual Income     |
| personhomeownership | Home ownership      |
| personemplength | Employment length (in years) |
| loan_intent | Loan intent |
| loan_grade | Loan grade |
| loan_amnt | Loan amount |
| loanintrate | Interest rate |
| loan_status | Loan status (0 is non default 1 is default) |
| loanpercentincome | Percent income |
| cbpersondefaultonfile | Historical default |
| cbpresoncredhistlength | Credit history length |
