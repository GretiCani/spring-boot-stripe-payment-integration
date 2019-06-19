# spring-boot-stripe-payment-integration
Credit card processing using springboot , stripe api and thymeleaf.
Clone project using git clone. Before you start app you should open an account on https://stripe.com if you already haven't one.
Login into your stripe account and go to the section developer->api keys and you will find publishable key and secret key, copy this key then go 
to application.properties and put your key on stripe.key.public = your_public_key and stripe.key.secret = your_secret_key.
Start your springboot app and go to localhost:8080 and you will find two option create recurring subscription and create one-time charge.
In this phase only one time charge will work. If you want to test recurring subscription then you should go to the subscription.html.
Replace radio boxes values (monthly-subscription & annual-subscription) are actual stripe plan id's. You must replace these values with your own product plan IDs
which you will create on your stripe account. After you complet this proccess you will be able to test recurring subscription.

# use test credit cards offered by stipe 
4242 4242 4242 4242 is not a real credit card number. It is one of the several Stripe testing cards available online. These cards only work in testing mode.
