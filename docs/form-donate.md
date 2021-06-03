Форма приёма пожервований.

## Syntax

```
{{< form-donate
wallet="[WALLET_YOOMONEY]"
paypal="[PAYPAL_EMAIL]"
patreon="[PATREON_USER]"
liberapay="[LIBERAPAY_USER]"
ko-fi="[KO-FI_USER]"
buymeacoffee="[BUYMEACOFFEE_USER]"
usd="[CARD_USD]"
eur="[CARD_EUR]"
rub="[CARD_RUB]"
btc="[WALLET_BTC]"
eth="[WALLET_ETH]"
xmr="[WALLET_XMR]" >}}
```

## ru.toml

```toml
[form.donate.targets]
other = "Назначение перевода..."

[form.donate.targets_help]
other = "Укажите назначение перевода."

[form.donate.sum_help]
other = "Укажите сумму."

[form.donate.card]
other = "Банковская карта"

[form.donate.yooMoney]
other = "ЮMoney"

[form.donate.mobile_phone]
other = "Мобильный телефон"

[form.donate.payment_type_help]
other = "Выберите способ перевода."

[form.donate.comment_placeholder]
other = "Введите комментарий (если имеется)..."

[form.donate.comment_help]
other = "Введите сопроводительный комментарий (не более 200 символов)."

[form.donate.name]
other = "ФИО"

[form.donate.name_help]
other = "Отметьте, если хотите указать ФИО отправителя."

[form.donate.email]
other = "E-mail"

[form.donate.email_help]
other = "Отметьте, если хотите указать электронную почту отправителя."

[form.donate.phone]
other = "Телефон"

[form.donate.phone_help]
other = "Отметьте, если хотите указать телефон отправителя."

[form.donate.address]
other = "Адрес"

[form.donate.address_help]
other = "Отметьте, если хотите указать адрес отправителя."

[form.donate.paypal]
other = "PayPal"

[form.donate.patreon]
other = "Patreon"

[form.donate.liberapay]
other = "Liberapay"

[form.donate.kofi]
other = "Ko-fi"

[form.donate.buymeacoffee]
other = "Buy Me a Coffee"

[form.donate.submit]
other = "Перевести"

[form.donate.btc]
other = "BTC"

[form.donate.eth]
other = "ETH"

[form.donate.xmr]
other = "XMR"

[form.donate.cards]
other = "Банковские карты"

[form.donate.crypto]
other = "Crypto"

[form.donate.services]
other = "Сервисы"
```

## en.toml

```toml
[form.donate.targets]
other = "Target transfer..."

[form.donate.targets_help]
other = "Enter target transfer."

[form.donate.sum_help]
other = "Set amount."

[form.donate.card]
other = "Bank Card"

[form.donate.yooMoney]
other = "YooMoney"

[form.donate.mobile_phone]
other = "Mobile Phone"

[form.donate.payment_type_help]
other = "Select a transfer method."

[form.donate.comment_placeholder]
other = "Enter a comment (if available)..."

[form.donate.comment_help]
other = "Enter an accompanying comment (max 200 characters)."

[form.donate.name]
other = "Name"

[form.donate.name_help]
other = "Check if you want to specify name of sender."

[form.donate.email]
other = "E-mail"

[form.donate.email_help]
other = "Check if you want to specify sender's e-mail."

[form.donate.phone]
other = "Phone"

[form.donate.phone_help]
other = "Check if you want to specify sender's phone number."

[form.donate.address]
other = "Address"

[form.donate.address_help]
other = "Check if you want to specify sender address."

[form.donate.paypal]
other = "PayPal"

[form.donate.patreon]
other = "Patreon"

[form.donate.liberapay]
other = "Liberapay"

[form.donate.kofi]
other = "Ko-fi"

[form.donate.buymeacoffee]
other = "Buy Me a Coffee"

[form.donate.submit]
other = "Transfer"

[form.donate.btc]
other = "BTC"

[form.donate.eth]
other = "ETH"

[form.donate.xmr]
other = "XMR"

[form.donate.cards]
other = "Bank Cards"

[form.donate.crypto]
other = "Crypto"

[form.donate.services]
other = "Services"
```
