# Psudocode
Class Diagram to Psudocode
65022498 Nattawut Pasuk

## 26)

> Defind class name "BillPayment"
> Defind attributes into BillPayment field class

> Defind setBuild_CurrentUnit as a function of BillPayment class
>  if not lastUnit valus is less than bill_currentUnit will show "Please insert a correct unit"

> Defind calculateUnit as a function of BillPayment class
>  return the result of bill_currentUnit - bill_lastUnit as decimal number

>Defind calculateBill as a function of BillPayment class
>  if bill_type is "Water" will set bill_Result = calculateUnit() multiply by 5
>  if bill_type is "Electiric" will set bill_Result = calculateUnit() multiply by 6
>  return bill_Result

> Defind displayBill as a function of BillPayment class
>  will show the message

## 27
> Defind bill_payment as instance of BillPayment
>   SET bill_payment.lastUnit = 250
>   SET bill_payment.currentUnit = 450
>   SET bill_type equal to "Electric"
>   Call displayBill to inform the data
