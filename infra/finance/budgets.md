# Budgets

Created the following AWS Budgets.

## Zero-Spend

Intent: Alert the Admin only, as a way to know when/if we have exceeded the AWS free plan.

Email Recipients:

- Admin (<rafael.g.depaulo@gmail.com>)

Value: USD 0,01

## Faról Amarelo

Intent: Info/Verbose level control of spending, to now if non-trivial but low spending has been achieved.

Email Recipients:

- Admin
- Owner (temporary)

Value: USD 1 (R$5,00)

## Faról Vermelho

Intent: Warning level message, implying that there is probably some error that is causing us a lot of unintended cost. Resolve immediately.

Email Recipients:

- Admin
- Owner

Value: USD 10 (R$50,00)

## Faról Preto

Intent: Absolutely disastrous error code. Everything is falling down and the whole account gotta shut down immediately!! This is seriously absurdly important dear god fix it yesterday!!!!!!!
Email Recipients:

- Admin
- Owner
- Super User (considering including in the future, but not now)
