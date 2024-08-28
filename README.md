# digital_option

A Digital Option, also known as a Binary Option, is a type of financial derivative that provides a fixed payout if the underlying asset meets a specified condition at expiration. If the condition is not met, the option expires worthless. The simplicity of the payout structure makes digital options a popular choice for speculators who want to bet on a particular outcome.


Underlying Asset (S): The asset on which the option is based (e.g., a stock, index).
Strike Price (K): The price at which the option's condition is evaluated.
Payout (P): The fixed amount paid to the holder if the option is in-the-money (ITM).
Maturity (T): The time until the option expires.


Call Option: Pays out if the underlying asset's price is greater than the strike price at expiration.
Put Option: Pays out if the underlying asset's price is less than the strike price at expiration.


Option Style:
Cash-or-Nothing: Pays a fixed cash amount if the option is ITM.
Asset-or-Nothing: Pays the value of the underlying asset if the option is ITM.


Cash-or-Nothing Call Option:
The holder receives a fixed payout if the underlying asset's price is greater than the strike price at expiration.
Payoff = P  if  S_T > K
Payoff = 0  if  S_T <= K
Where:
P is the fixed payout.
S_T is the price of the underlying asset at maturity.
K is the strike price.

Cash-or-Nothing Put Option:
The holder receives a fixed payout if the underlying asset's price is less than the strike price at expiration.
Payoff = P  if  S_T < K
Payoff = 0  if  S_T >= K

Asset-or-Nothing Call Option:
The holder receives the value of the underlying asset if the asset's price is greater than the strike price at expiration.
Payoff = S_T  if  S_T > K
Payoff = 0    if  S_T <= K

Asset-or-Nothing Put Option:
The holder receives the value of the underlying asset if the asset's price is less than the strike price at expiration.
Payoff = S_T  if  S_T < K
Payoff = 0    if  S_T >= K

