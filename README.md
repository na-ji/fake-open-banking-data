<p align="center">
  <a href="http://algoan.com/" target="blank"><img src="https://media.licdn.com/dms/image/C4E0BAQH-hIlc5g9g7w/company-logo_200_200/0?e=2159024400&v=beta&t=j5y9KO1P22GsMx3vBNawrpvyvjD2iyBWGeVPUsRkn5s" width="320" alt="Algoan Logo" /></a>
</p>

# Fake Open Banking data samples

This repository shares different open banking data samples in order to test easily [Algoan Scoring APIs](https://docs.algoan.com). Balance and transaction dates are automatically refreshed by a daily cron job.

> 💡 The story, all names, characters, credits portrayed in this fake data are fictitious. No identification with actual persons (living or deceased), credits, debts, and life style is intended or should be inferred.

## Personae

A JSON file represents what we call a "Personae": a profile with relevant credit risk indicators.
### Harry Potter

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/harry_potter.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/harry_potter.json) |

**Description**:

Risky profile (Credit Score ~150-200/1000)

- Earns 2500€/month
- Pays a rent of 900€/month
- Has 6 consumer credits with three different lenders (3 with lender "A", 2 with lender "B" and 1 with lender "C")
- Has done 3 split payments.
- Has overdraft fees
- Has 1 payment rejection on a credit and on a subscription
- Falling cash flows

### Lara Croft

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/lara_croft.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/lara_croft.json) |

**Description**:

Good profile (Credit Score ~900/1000)

- Earns 2500€/month
- Pays a mortgage of 500€/month
- Has 4 consumer credits with two different lenders (2 with lender "A" and 2 with lender "B")
- Has done 2 split payments.
- Has no incident or fees
- Stable cash flows

### Archibald Haddock

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/archibald_haddock.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/archibald_haddock.json) |

**Description**:

Risky profile (Credit Score <100/1000)

- Has an account seizure
- Presents a high gambling over incomes ratio, frequent gambling
- Their treasury is globally decreasing
- Presents frequent overdraft and significant amount of overdraft fees
- Presence of payment incidents with significant amount
- Has 2 consumer loans

### Harley Quinn

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/harley_quinn.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/harley_quinn.json) |

**Description**:

Good profile (Credit Score ~900/1000)

- Secondary account synchronized

### Ron Weasley

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/ron_weasley.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/ron_weasley.json) |

**Description**:

Good profile (Credit Score ~900/1000)

- Couple with similar wages in the same company
- Has a mortgage and a consumer loan
- Insurances, telecom and power are debited on the account

### Hermione Granger

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/hermione_granger.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/hermione_granger.json) |

**Description**:

Good profile (Credit Score ~900/1000)

- Earns ~2000€/month
- Pays a rent of ~600€/month
- Has a consumer loan and a split payment
- Has neither payment incidents nor fees
- Has light overdraft end of month
- Has a stable treasury
- Has standard expenses: power, telecom, transport, multimedia, gym
- Has some savings
- Has a deferred debit card

### Sherlock Holmes

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/sherlock_holmes.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/sherlock_holmes.json) |

**Description**:

Good profile (Credit Score ~900/1000)

- Their earnings come from self-employment
- Has a rent
- Has direct debits such as power, telecom, insurance

### Padme Amidala

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/padme_amidala.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/padme_amidala.json) |

**Description**:

Good profile (Credit Score ~900/1000)

- Is retired
- Has a reversionary pension
- Has a mortgage
- Has rental income
- Has insurances, power and telecom transactions

### Luke Skywalker

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/luke_skywalker.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/luke_skywalker.json) |

**Description**:

Fair profile (Credit Score ~500/1000)

- Student
- Receives regular transfers
- Receives allowances
- Has a rent
- Has a state subsidy
- Has a student loan
- Has overdraft periods

### Leia Skywalker

**Language**: French 🇫🇷

| Format         | Link                                                                                                               |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| Algoan         | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/samples/fr/leia_skywalker.json)             |
| Budget Insight | [🔗](https://raw.githubusercontent.com/algoan/fake-open-banking-data/main/budget_insight_v2_0/fr/leia_skywalker.json) |

**Description**:

Good profile (Credit Score ~900/1000)

- Earns ~1300€/month
- Has a rent of ~400€/month
- Repays a consumer loan
- Has allowances
- Has neither incidents nor fees
- Has light overdraft at end of month
- Has standard expenses: power, telecom, transport, multimedia, gym
- Has savings
